# PP_ENTREGA2FIGUREROAD
CODIGO_JUEGO_FIGURE_ROAD
public class Principal{
  public static void main(string[]args){
    JFrame Ventana=new JFrame("FIGUREROAD");
    Juego Figureroad=new Juego();
    ventana.add(Figureroad);
    ventana.setSize(1300,1400);
    ventana.setLocation(70,200);
    ventana.setVisible(true);
    ventana.setDefaultCloseOperation(Jframe.EXIT_ON_COLSE);
    
    while(true){
    Figureroad.repaint();
    }
  }
}
// CALSE JUEGO
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
 * Este metodo nos ayudav a validar el nivel actual y generar un nuevo nivel*/
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

      }
   }
