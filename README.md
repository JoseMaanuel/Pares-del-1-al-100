# Pares-del-1-al-100
package paresdel1al100;

import java.util.*;
public class Paresdel1al100 {

   
    public static void main(String[] args) {
        Scanner lec=new Scanner(System.in);
        int n=1, c=0, s=0;
    while(n<=100){
    if(n%2==0){
    
    c++;
    }s=s+c;
    n++;
    }
        System.out.println("Los numeros pares es:" +c);
        System.out.println("");
        System.out.println("La suma de los numeros impares es:" +s);
        
    }
    
}
