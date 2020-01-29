# Gentleman
import java.util.Scanner;
public class Dungeon {

public static void main(String[] args) {
Player Pro= new Player ()
Pro.start(choice)

}
public static void fight()
Scanner input= new Scanner(System.in);

int choice=0;
int choice= input.nextInt();
System.out.println("You attack.");
System.out.println("1: You attack.");
System.out.println("2: You heal.");
System.out.println("3: You ");
System.out.println("4: ");
switch(choice) {
    case 1:
     System.out.println("You attack.");
    break;
    case 2:
        
    break;
    case 3:
        
    break;
}

public static void location() {
    
}





public class Player {

    private String name
    private int health
    private int healthMAX
    private int damage
    private int money
    private int defense

    public void start(int choice) {
        switch(choice) {
            case 1:
            setHealth(20);
            setMoney(0);
            setDamage(8);
            break;
            case 2:
            setHealth(15);
            setMoney(0);
            setDamage(8);
            break;
        }
    }
    public void setName(String N) {
        name=N
    }
    public String getName() {
        return name;
    }
    public void setHealth (int h) {
        if (h+health<healthMAX)
        health=healthMAX;
        else
        health=h+health;
    }
    public getHealth;
        return health;
        
    public void setMoney(int m){
        money=m+money;
    }

    public getMoney(){
        return money;
    }
    public void setDefense (int d){
        defense=d+defense
    }
    public getDefense(){
        return defense;
    }
}
