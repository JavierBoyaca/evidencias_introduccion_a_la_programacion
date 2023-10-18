<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 1 


<!-- Su documentación aquí -->

# Actividad 1

adskjalsjfskdljfksdlf

- item1
- item2


```java
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.sesion11punto2;

import java.util.Scanner;

/**
 *
 * @author javie
 */
public class Sesion11Punto2 {

    public static void main(String[] args) {
        Scanner obj = new Scanner(System.in);
        //Entrada
        int num, ultimoDigito, c=0, decimal=0;
        System.out.println("Digite un numero binario");
        num= obj.nextInt();
        //Proceso
        while (num!=0){
        ultimoDigito=num%10;
        decimal+=ultimoDigito*Math.pow(2,c);
        c++;
        num/=10;}
        
        System.out.println(decimal);
        
        
    }
}
```

![img](https://docs.github.com/es/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)

[Actividad 1](https://drive.google.com/file/d/0BzeKeb18QJdvUzNnLUM4RkVLeEI1WEJzVWZVMTdCbzhMVGdJ/view?usp=sharing&resourcekey=0-aSfJ33H4X0iNCXmV8h4KMw)









