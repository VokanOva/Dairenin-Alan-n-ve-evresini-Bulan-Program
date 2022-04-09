import java.util.Scanner;

       public class CLASS {
           public static void main(String[] args) {
               int r, a;
               double pi = 3.14, daireDilimiAlani;
               Scanner input = new Scanner(System.in);
               System.out.print("Yaricapi  : ");
               r = input.nextInt();
               System.out.print("Merkez acisini  : ");
               a = input.nextInt();
               daireDilimiAlani = (pi * (r * r) * a) / 360;
               System.out.println("Daire Dilimi Alani: " + daireDilimiAlani);
