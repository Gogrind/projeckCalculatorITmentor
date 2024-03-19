import java.util.Scanner;

public class calculator {
public static void main(String... args) {
Scanner sc = new Scanner(System.in);
System.out.println("Введите первое число");
int a = sc.nextInt();
System.out.println("Введите второе число");
int b = sc.nextInt();
System.out.println("Введите сивмов (*, /, +, -)");
char operation = sc.next().charAt(0);
System.out.println("Ваш Ответ");
// На кретерий задачи "Калькулятор должен принимать на вход числа от 1 до 10 включительно". Я так и не понял как сделать, перепробывал много способов, посмотрел много материала, но  так и не нашел.
if (operation == '*') {
int result = a * b;
System.out.println( result );
} else if (operation == '/') {
int result = a / b;
System.out.println( result );
} else if (operation == '+') {
int result = a + b;
System.out.println( result );
} else if (operation == '-') {
int result = a - b;
System.out.println( result );
} else {
System.out.println("Данный символ не подходит для выполнение действия");
}
}


}# projeckCalculatorITmentor
Тестовое задания калькулятор
