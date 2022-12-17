# cwiczenie-butelka

package cwiczeniebutelka;

public class butelka {
    
    private double ilelitrow;

    butelka(double ilelitrow)
    {
        this.ilelitrow = ilelitrow;
    }
    double getlitrow()
       
    {

return ilelitrow;

        }
    
public static void main(String[] args) {

   butelka[] butelka = new butelka[3];
   
   butelka[0] = new butelka(4);

   butelka[1] = new butelka(3);

   butelka[2] = new butelka(6);

   System.out.println(butelka[0].getlitrow());
   System.out.println(butelka[1].getlitrow());  
   System.out.println(butelka[2].getlitrow());
}
}
