import java.util.*;
class GuessGame {
public static void main(String[] args){
int num = new Random().nextInt(100) + 1;
Scanner sc = new Scanner(System.in);
int guess;
do{
System.out.println("Guess (1_100): ");
guess = sc.nextInt();
System.out.println(guess < num ? "too low " guess >num ? "to high ");
}
while (guess != num);
}
}

