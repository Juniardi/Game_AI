# Game_AI
import java.util.Scanner;
public class Game_AI {
    public static void main(String[] args) {
        Game_AI panggil = new Game_AI();
        panggil.menu();
    }

    public void menu() {
        Scanner baca = new Scanner(System.in);
        Game_AI panggil = new Game_AI();

        System.out.println("--------------------------------------------------");
        System.out.println("--------------Aplikasi Game Logika----------------");
        System.out.println("--------------------------------------------------");
        System.out.println("1).Kambing Pindah");
        System.out.println("2).Sayuran Pindah");
        System.out.println("3).Serigala Pindah");
        System.out.println("4).Kambing Kembali");
        System.out.println("5).Sayuran Kembali");
        System.out.println("6).Serigala Kembali");
        System.out.println("7).Perahu Kembali");
        System.out.println("--------------------------------------------------");
        panggil.langkah1();
    }

    public void langkah1() {
        Game_AI panggil = new Game_AI();
        Scanner baca = new Scanner(System.in);
        System.out.print("Masukkan Langkah 1    : ");
        int input1 = baca.nextInt();
        if (input1 == 1) {
            System.out.println("Langkah 1 Benar!");
            System.out.println("--------------------------------------------------");
            System.out.print("Masukkan Langkah 2    : ");
            int input2 = baca.nextInt();
            if (input2 == 7) {
                System.out.println("Langkah 2 Benar!");
                System.out.println("--------------------------------------------------");
                System.out.print("Masukkan Langkah 3    : ");
                int input3 = baca.nextInt();
                if (input3 == 3) {
                    System.out.println("Langkah 3 Benar!");
                    System.out.println("--------------------------------------------------");
                    System.out.print("Masukkan Langkah 4    : ");
                    int input4 = baca.nextInt();
                    if (input4 == 4) {
                        System.out.println("Langkah 4 Benar!");
                        System.out.println("--------------------------------------------------");
                        System.out.print("Masukkan Langkah 5    : ");
                        int input5 = baca.nextInt();
                        if (input5 == 2) {
                            System.out.println("Langkah 5 Benar!");
                            System.out.println("--------------------------------------------------");
                            System.out.print("Masukkan Langkah 6    : ");
                            int input6 = baca.nextInt();
                            if (input6 == 7) {
                                System.out.println("Langkah 6 Benar!");
                                System.out.println("--------------------------------------------------");
                                System.out.print("Masukkan Langkah 7    : ");
                                int input7 = baca.nextInt();
                                if (input7 == 1) {
                                    System.out.println("Langkah 7 Benar");
                                    System.out.println("--------------------------------------------------");
                                    System.out.println("Selamat Langkah Yang Anda Lakukakn Berhasil!");
                                    System.out.println("--------------------------------------------------");
                                    System.out.println("Urutan Langkah    : " + input1 + " - " + input2 + " - " + input3 + " - "
                                            + input4 + " - " + input5 + " - " + input6 + " - " + input7);
                                } else {
                                    System.out.println("--------------------------------------------------");
                                    System.out.println("Langkah Yang Anda Lakukan Salah!");
                                    panggil.langkah1();
                                }
                            } else {
                                System.out.println("--------------------------------------------------");
                                System.out.println("Langkah Yang Anda Lakukan Salah!");
                                panggil.langkah1();
                            }
                        } else {
                            System.out.println("--------------------------------------------------");
                            System.out.println("Langkah Yang Anda Lakukan Salah!");
                            panggil.langkah1();
                        }
                    } else {
                        System.out.println("--------------------------------------------------");
                        System.out.println("Langkah Yang Anda Lakukan Salah!");
                        panggil.langkah1();
                    }
                } else {
                    System.out.println("--------------------------------------------------");
                    System.out.println("Langkah Yang Anda Lakukan Salah!");
                    panggil.langkah1();
                }
            } else {
                System.out.println("--------------------------------------------------");
                System.out.println("Langkah Yang Anda Lakukan Salah!");
                panggil.langkah1();
            }
        } else {
            System.out.println("--------------------------------------------------");
            System.out.println("Langkah Yang Anda Lakukan Salah!");
            panggil.langkah1();
        }
    }

}
