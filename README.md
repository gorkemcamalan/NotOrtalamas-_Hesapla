# NotOrtalamas-_Hesapla


import  java.util.Scanner;
 
public class NotOrtalaması {

	public static void main(String[] args) {
		//Değişkenleri oluştur
		int mat,fzk,kmy,trk,mzk;
		
		
		//Scaner sınıf tanımladık
		 Scanner ınp= new Scanner(System.in);
		 
		 //Kullanıcıdan değer al
		  System.out.print("Matematik Notunuz:");
          mat=ınp.nextInt();
         
          System.out.print("Fizik Notunuz:");
          fzk=ınp.nextInt();
          
          System.out.print("Kimya Notunuz:");
          kmy=ınp.nextInt();
          
          System.out.print("Türkçe Notunuz:");
          trk=ınp.nextInt();
          
          System.out.println("Müzik Notunuz:");
          mzk=ınp.nextInt();
          
          
         double ort;
          
          ort=(mat+mzk+fzk+kmy+trk)/5;
          
          System.out.println("Sınıf Ortalamanız:" + ort);
         System.out.println(ort>=60 ? "Sınıf Geçti" :" Sınıfta Kaldı");
         
          
	}

}
