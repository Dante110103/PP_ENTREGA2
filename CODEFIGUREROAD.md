# PP_ENTREGA2FIGUREROAD
CODIGO_JUEGO_FIGURE_ROAD
package Juego;
import java.lang.System.Logger;
import java.lang.System.Logger.Level;
import javax.swing.JFrame;
public class Main_Class {
	public static void main(String[]args){
	    JFrame ventana=new JFrame("FIGURE ROAD");
	    juego jueguito=new juego();
	    ventana.add(jueguito);
	    ventana.setSize(1300,1400);
	    ventana.setLocation(70,200);
	    ventana.setVisible(true);
	    ventana.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	    
	    while(true){
	    	jueguito.repaint();
	    	try {
	    		Thread.sleep(10);	
	    	} catch (InterruptedException ex) {
	    		 
	    	}
	    	
	    }
	  }
	}
// CLASE JUEGO
import javax.swing.JPanel;
import java.awt.BasicStroke;
import java.awt.Color;
import java.awt.Dimension;
import java.awt.Graphics;
import java.awt.Graphics2D;
import java.awt.RenderingHints;
import java.awt.geom.AffineTransform;
import java.awt.geom.Ellipse2D;
import javax.swing.JPanel;

public class Juego extends JPanel{
  public Juego(){
  }
}
public static void main () {
   System.out.println(¨Bienvenido, ¿nombre
jugador?");
   //Obtenemos el nombre del jugador        
   Scanner sc = new Scanner(System.in);        
   String pirateName = sc.nextLine();
   //Constructor de Figureroad        
   jugador = new jugador(jugadorName);        
   jugador.saludar();
   System.out.println("\n 1. Continuar \n 2. Abandonar
partida");
   int continuar = sc.nextInt();
   if (continuar == 1){
      //Llamamos a la función que nos lleva al siguiente nivel
      nextLevel();
   }
   
  }

/**
 * Este metodo nos ayuda a validar el nivel actual y generar un nuevo nivel*/
public static void nextLevel(){
    //evaluamos el nivel utilizando la estatica Figureroad  level
    switch (Figureroad.getFigureroad level()) {
        case 0:
        Figureroad  Figureroad1 = new Figureroad(¨circulo operaciones matematicas¨);
        ejecutarNivel(Figureroad1);
        break;
        case 1:
        Figureroad  Figureroad2 = new Figureroad(¨cuadrado operaciones matematicas¨);
        ejecutarNivel(Figureroad2);
        break;
        case 2:
        Figureroad  Figureroad3 = new Figureroad(¨ovalo operaciones matematicas¨);
        ejecutarNivel(Figureroad3);
        break;
        case 3:
        Figureroad  Figureroad4 = new Figureroad(¨triangulo operaciones matematicas¨);
        ejecutarNivel(Figureroad4);
        break;
        case 4:
        Figureroad  Figureroad5 = new Figureroad(¨estrella Figureroad final¨);
        ejecutarNivel(Figureroad5);
        break;
        case 5:
        wingame() ;
        break;
        
/Cargamos una imagen y la pintamos en el tablero. 
package com.zetcode;

import java.awt.Dimension;
import java.awt.Graphics;
import java.awt.Image;
import javax.swing.ImageIcon;
import javax.swing.JPanel;

public class Board extends JPanel {

    private Image ESTABLECER;

    public Board() {

        initBoard();
    }
    
    private void initBoard() {
        
        loadImage();
        
        int w = bardejov.getWidth(this);
        int h =  bardejov.getHeight(this);
        setPreferredSize(new Dimension(w, h));        
    }
    
    private void loadImage() {
        
        ImageIcon ii = new ImageIcon("src/resources/ESTABLECER.png");
        bardejov = ii.getImage();        
    }

      }
   }
