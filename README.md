import java.util.Scanner;

public class JavaApplication3 {
    public static void main(String[] args) {

        // Deklarasi variabel
        String nama_depan, nama_belakang, nama_lengkap, t_lahir, tgl_lahir, alamat, hobi, no_hp, email;
        Scanner input = new Scanner(System.in);

  
        System.out.println("Data Siswa");
        System.out.println("=================");

        System.out.print("Masukan nama depan \t= ");
        nama_depan = input.nextLine();

        System.out.print("Masukan nama belakang \t= ");
        nama_belakang = input.nextLine();

        System.out.print("Tempat lahir \t\t= ");
        t_lahir = input.nextLine();

        System.out.print("Tanggal lahir \t\t= ");
        tgl_lahir = input.nextLine();

        System.out.print("Masukan Alamat \t\t= ");
        alamat = input.nextLine();

        System.out.print("Hobi \t\t\t= ");
        hobi = input.nextLine();

        System.out.print("Masukan no HP \t\t= ");
        no_hp = input.nextLine();

        System.out.print("Masukan email \t\t= ");
        email = input.nextLine();

        System.out.println(""); 
        System.out.println(""); 

        System.out.println("Menyiapkan ringkasan data, harap tunggu..."); // loading menampilkan data
        
      
        try {
            Thread.sleep(4000);  // Delay 4 detik
        } catch (InterruptedException e) {
            e.printStackTrace();
        }
        
        System.out.println("");

        try {
            Thread.sleep(2000); // Delay 2 detik
            System.out.println("Nama lengkap = " + nama_depan + " " + nama_belakang);
            nama_lengkap = nama_depan + " " + nama_belakang;

            Thread.sleep(2000); // Delay 2 detik
            System.out.println("Tempat tanggal lahir = " + t_lahir);

            Thread.sleep(2000); // Delay 2 detik
            System.out.println("Tanggal Lahir = " + tgl_lahir);

            Thread.sleep(2000); // Delay 2 detik
            System.out.println("Alamat = " + alamat);

            Thread.sleep(2000); // Delay 2 detik
            System.out.println("Hobi = " + hobi);

            Thread.sleep(2000); // Delay 2 detik
            System.out.println("Nomor HP = " + no_hp);

            Thread.sleep(2000); // Delay 2 detik
            System.out.println("Email = " + email);
        } catch (InterruptedException e) {
            e.printStackTrace();
        }

        // Menutup Scanner
        input.close();
    }
}
