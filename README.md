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
