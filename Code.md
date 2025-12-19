//this is a code
import java.util.*;
class A{
    Scanner sc = new Scanner(System.in);
    int flr_dec;
    int flr_loc;
    void yes(){
        System.out.println("welcome to the lift");
        System.out.println("on which floor are you");
        flr_loc = sc.nextInt();
        System.out.println("you are on "+flr_loc+" floor");
        System.out.println("so on which floor you want to go between 1-10");
        flr_dec = sc.nextInt();
        flr_confirm();
    }
    void for_infinite(){
        System.out.println("so on which floor you are");
        int z = sc.nextInt();
        if (flr_dec<z){
            for(int i =flr_dec;i<=z;i++){
                System.out.println(i);
            }
            System.out.println("your lift have arrived to your floor"+z);
            yes();
        }
        if (z<flr_dec){
            for (int i = flr_dec; i >= z; i--) {
                System.out.println(i);
            }
            System.out.println("your lift have arrived to your floor"+z);
            yes();
        }
        System.out.println("your lift have arrived ");
    }
    void infinite(){
        System.out.println("you have pressed button for the lift so you want to go? press 0 or 1 or -1 for ending the program");
        int use;
        Scanner sc = new Scanner(System.in);
        use = sc.nextInt();
        if(use == 0){
            System.out.println("if you don't want to go why the hell you pressed the button");
        }
        else if (use == 1) {
            for_infinite();
        } else if (use == -1) {
            System.out.println("program is ending");
        }
    }
    void flr_confirm(){
        switch (flr_dec){
            case 1:
                System.out.println("so you want to go on floor 1st");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 2:
                System.out.println("so you want to go on floor 2nd");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 3:
                System.out.println("so you want to go on floor 3rd");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 4:
                System.out.println("so you want to go on floor 4th");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 5:
                System.out.println("so you want to go on floor 5th");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 6:
                System.out.println("so you want to go on floor 6th");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 7:
                System.out.println("so you want to go on floor 7th");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 8:
                System.out.println("so you want to go on floor 8th");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 9:
                System.out.println("so you want to go on floor 9th");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            case 10:
                System.out.println("so you want to go on floor 10th");
                if (flr_loc<flr_dec){
                    for(int i =flr_loc;i<=flr_dec;i++){
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                if (flr_loc>flr_dec){
                    for (int i = flr_loc; i >= flr_dec; i--) {
                        System.out.println(i);
                    }
                    System.out.println("arrived at your floor thank you for using lift");
                    infinite();
                }
                break;
            default:
                System.out.println("invalid floor");

        }
    }
}
public class Main {
    public static void main(String[] args) {
        A a1 = new A();
        System.out.println("Do you want to go through lift press 0 or 1");
        int use;
        Scanner sc = new Scanner(System.in);
        use = sc.nextInt();
        if(use == 0){
            System.out.println("if you don't want to go why the hell you pressed the button");
        }
        else if (use == 1) {
            a1.yes();
        }
        else{
            System.out.println("invalid answer");
        }
    }
}
