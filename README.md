import java.util.Scanner;

public class Main2 {


    public static void main(String[] args) {


    
     // manavdan almış oldukları ürünlerin kilogram değerlerine göre toplam tutarını ekrana yazdıran program

        /*Meyveler ve KG Fiyatları

        Armut : 2,14 TL
        Elma : 3,67 TL
        Domates : 1,11 TL
        Muz: 0,95 TL
        Patlıcan : 5,00 TL*/


        
        double armut=2.14,elma=3.67,domates=1.11,muz=0.95,patlican=5.00,toplam,kg,armutFiyat;


        Scanner sc = new Scanner(System.in);
        
        System.out.print("Armuttan kaç kg: ");
       kg = sc.nextDouble();
        armutFiyat=armut*kg;
        System.out.println(armutFiyat);

        
        System.out.print("elmadan kaç kg: ");
        kg = sc.nextInt();
        elma=elma*kg;
        System.out.println(elma);

        
        System.out.print("domatesten kaç kg: ");
        kg = sc.nextDouble();
        domates=domates*kg;
        System.out.println(domates);

        
        System.out.print("muzdan kaç kg: ");
        kg = sc.nextDouble();
        muz=muz*kg;
        System.out.println(muz);

        
        System.out.print("patlicandan kaç kg: ");
        kg= sc.nextDouble();
        patlican=patlican*kg;
        System.out.println(patlican);

        
        toplam=patlican+elma+armut+muz+domates;
        System.out.println("toplam : "+toplam);







    }
}
