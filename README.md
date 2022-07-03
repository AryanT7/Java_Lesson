# Java_Lesson
Basic syntax for programming in Java.

package com.javalesson;

import java.io.*;

//class Vehicle{
// String name;
// static String type;
//}

//interface Animal{ //Interface //Multiple inheritance
// void walk();
//}
//interface Herbivore{
//
//}
//class Horse implements Animal,Herbivore {
// public void walk(){
// System.out.println("Walks on 4 legs");
//
// }
//}

//abstract class Animal{ //Abstraction
// abstract void walk();
// Animal(){
// System.out.println("Created an animal");
// }
//}
//
//class Horse extends Animal{
// Horse(){
// System.out.println("Created a horse");
// }
// public void walk(){
// System.out.println("Walks on 4 legs");
// }
//}
//
//class Chicken extends Animal{
// public void walk(){
// System.out.println("Walks on 2 legs");
// }
//}

//class Account{ //Encapsulation
// public String name;
// protected String email;
// private String password;
//
// public String getPassword(){
// return this.password;
// }
// public void setPassword(String pass){
// this.password = pass;
// }
//}

//class Shape{ //Inheritance
// public void area(){
// System.out.println("Displays area");
// }
//}
//
//class Triangle extends Shape{
// public void area(int l,int h){
// System.out.println(1/2lh);
// }
//}
//
//class EquilateralTriangle extends Triangle{
// public void area(int l,int h){
// System.out.println(1/2lh);
// }
//}
//
//class Circle extends Shape{
// public void area(int r){
// System.out.println(3.14rr);
// }
//}

//class Student{ //Polymorphism
// String name;
// int age;
// public void printInfo(String name){
// System.out.println(name);
// }
// public void printInfo(int age){
// System.out.println(age);
// }
// public void printInfo(String name,int age){
// System.out.println(name + " " + age);
// }
//
//}

public class Main {

// public static void printName(String num){
// System.out.println(num);
// }

public static void main(String[] args) {
// byte age = 21;
// long views = 3_123_456_789L;
// float price = 10.99F;
// char letter = 'A';
// boolean check = true;
// Date date = new Date();
// // System.out.println(date);
//
// byte x = 1;
// byte y = x;
// x = 2;
// // System.out.println(y);
//
// Point p1 = new Point(1, 1);
// Point p2 = p1;
// // System.out.println(p2);
//
// String message = "C:\Windows\...";
// System.out.println(message);

// int[] arr = { 1, 2, 3, 4, 5 };
// // System.out.println(Arrays.toString(arr));
//
// int[][] array = { { 1, 2, 3 }, { 4, 5, 6 } };
// // System.out.println(Arrays.deepToString(array));

// short a = 1; //implicit
// int b = a+2;
// System.out.println(b);

// double m = 1.1; //explicit
// int n = (int) m + 2;
// System.out.println(n);
// String str = "1.1";
// double i = Double.parseDouble(str) + 2;
// System.out.println(i);

// int result = (int)Math.floor(1.1F);
// System.out.println(result);
// int res = Math.max(7,11);
// System.out.println(res);

// int result = (int)(Math.random()*100);
// System.out.println(result);

// System.out.println(NumberFormat.getCurrencyInstance().format(12345.678));

// Scanner sc = new Scanner(System.in);
// System.out.print("Name: ");
// String name = sc.nextLine().trim();
// System.out.println(name);

// Scanner sc = new Scanner(System.in);
// System.out.print("Principal: ");
// int prinpl = sc.nextInt();
// System.out.print("Annual Interest Rate: ");
// float rate = sc.nextFloat();
// System.out.print("Period (Years): ");
// byte yrs = sc.nextByte();
// float si = (prinplrateyrs)/100;
// System.out.print("Mortgage: "+ NumberFormat.getCurrencyInstance().format(si));

// int x = 1;
// int y = 1;
// System.out.println(x == y);

// int temperature = 22;
// boolean isWarm = temperature>20 && temperature<30;
// System.out.println(isWarm);

// boolean hasHighIncome = true;
// boolean hasGoodCredit = true;
// boolean hasCriminalRecord = false;
// boolean isEligible = (hasGoodCredit || hasHighIncome) && !hasCriminalRecord;
// System.out.println(isEligible);

// int income = 120_000;
// String className = income > 100_000 ? "First" : "Economy";
// System.out.println(className);

// String role = "admin";
// switch (role){
// case "admin":
// System.out.println("Admin");
// break;
// case "moderator":
// System.out.println("Moderator");
// break;
// default:
// System.out.println("Guest");
// }

// Scanner sc = new Scanner(System.in);
// System.out.print("Number: ");
// byte num = sc.nextByte();
// if (num % 5 == 0 && num % 3 == 0)
// System.out.println("FizzBuzz");
// else if (num % 3 == 0)
// System.out.println("Buzz");
// else if(num % 5 == 0)
// System.out.println("Fizz");
// else
// System.out.println(num);

// Scanner sc = new Scanner(System.in);
// String input = "";
// while (!input.equals("quit")){
// System.out.print("Input: ");
// input = sc.next().toLowerCase();
// if (input.equals("quit"))
// break;
// System.out.println(input);
// }

// String[] fruits = {"Apple","Mango","Orange"};
// for (String fruit : fruits)
// System.out.println(fruit);

// int i = 0;
// while (true){
// if (i == 3){
// i += 1;
// continue;
// }
// System.out.println(i);
// i += 1;
// if (i>5){
// break;
// }
// }

// int a = 1,b = 0;
// try {
// int div = a/b;
// System.out.println(div);
// }
// catch (Exception e){
// System.out.println("Invalid");
// }

// printName("7");

// Student s1 = new Student();
// s1.name = "Aryan";
// s1.age = 20;
// s1.printInfo(s1.name);
// s1.printInfo(s1.age);
// s1.printInfo(s1.name,s1.age);

// Account ac1 = new Account();
// ac1.name = "OrionTech";
// ac1.email = "xyz@gmail.com";
// ac1.setPassword("abcd");
// System.out.println(ac1.getPassword());

// Horse horse = new Horse();
// horse.walk();

// Horse horse = new Horse();

// Vehicle.type = "Petrol";
// Vehicle v1 = new Vehicle();
// v1.name = "BMW";
// System.out.println(v1.type);

// try {
// BufferedWriter bw = new BufferedWriter(
// new FileWriter("C:\Users\HP\OneDrive\Desktop\Test\output.txt"));
// bw.write("It was a busy day.\n");
// bw.write("---27/6/2022---\n");
// bw.write("Regards.");
// bw.close();
// } catch (IOException e) {
// e.printStackTrace();
// }

// try {
// BufferedWriter bw = new BufferedWriter(
// new FileWriter("C:\Users\HP\OneDrive\Desktop\Test\output_copy.txt"));
// BufferedReader br = new BufferedReader(
// new FileReader("C:\Users\HP\OneDrive\Desktop\Test\output.txt"));
// String s;
// while ((s = br.readLine()) != null){
// System.out.println(s);
// bw.write(s + "\n");
// }
// br.close();
// bw.close();
// } catch (FileNotFoundException e) {
// e.printStackTrace();
// } catch (IOException e) {
// e.printStackTrace();
// }

}
}
