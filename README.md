# Project-about-dart-program-
import 'dart:io';

void main() {
   triangle();
}

void triangle() {
  stdout.write("Enter the base of the triangle: ");
  double base = double.parse(stdin.readLineSync()!);
 stdout.write("Enter the height of the triangle: ");
  double height = double.parse(stdin.readLineSync()!);

  double area = 0.5 * base * height;
   print("The area of the triangle is: $area");
}
