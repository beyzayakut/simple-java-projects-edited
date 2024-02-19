import java.util.Scanner;

class Scratch {
    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        int mat, turkce, sosyal, muzik;
        int toplam=0, sayac=0;
        System.out.print("matematik notunuzu giriniz:");
        mat=input.nextInt();
        if(mat<0 || mat>100){
            System.out.println("bu ders notu ortalamaya dahil edilmeyecektir...");
        }
        else{
            System.out.println("gecerli ders notu");
            toplam+=mat;
            sayac++;
        }

        System.out.print("turkce notunuzu giriniz:");
        turkce=input.nextInt();
        if(turkce<0 || turkce>100){
            System.out.println("bu ders notu ortalamaya dahil edilmeyecektir...");
        }
        else{
            System.out.println("gecerli ders notu");
            toplam+=turkce;
            sayac++;
        }

        System.out.print("sosyal notunuzu giriniz:");
        sosyal=input.nextInt();
        if(sosyal<0 || sosyal>100){
            System.out.println("bu ders notu ortalamaya dahil edilmeyecektir...");
        }
        else{
            System.out.println("gecerli ders notu");
            toplam+=sosyal;
            sayac++;
        }

        System.out.print("muzik notunuzu giriniz:");
        muzik=input.nextInt();
        if(muzik<0 || muzik>100){
            System.out.println("bu ders notu ortalamaya dahil edilmeyecektir...");
        }
        else{
            System.out.println("gecerli ders notu");
            toplam+=muzik;
            sayac++;
        }
        double ortalama;
        ortalama=toplam/sayac;

        if(ortalama < 55){
            System.out.println("Sınıfta kaldınızzz...");
        }
        else{
            System.out.println("Sınıfı gectininz tebrikler...");
        }
        System.out.println("ortalamanız:"+ortalama);
    }
}
