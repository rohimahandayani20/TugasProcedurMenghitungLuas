TugasProcedurMenghitungLuas
===========================
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package id.co.blits.tugasrohima;

/**
 *
 * @author Star
 */
public class MainMenu {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        System.out.println(" ~~~ MENGHITUNG LUAS ~~~ "+"\n");
        PersegiPanjang rohima = new PersegiPanjang();
        rohima.panjang=20;
        rohima.lebar=10;
        rohima.tampilPersegiPanjang();
        
        Lingkaran hanny = new Lingkaran();
        hanny.jarijari= 3 ;
        hanny.tampilLingkaran();
        
        Segitiga handayani = new Segitiga();
        handayani.alas= 10 ;
        handayani.tinggi=5;
        handayani.tampilSegitiga();
    
    }
    
    
    
}
