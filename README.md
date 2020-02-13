public class PassByValue {

 public static void main(String[] args) {
  int number = 100;
  System.out.println("Original: " + number);

  change(number);

  System.out.println("After :" + number);
 }

 private static void change(int number) {
  number += 55;
 }

}
