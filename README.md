### Santiago

*Cloud Computing (GitHub)*

![Alt](https://lh3.googleusercontent.com/XSDv6XYZ973bdxMBDJ1adLHpSSUv4vsZJaePpms21eZDl-27JIfTHIYXnnudwPfAg_1-59bKAarMhWGNagsTR2Gq0pAWBUw6CwYwH2V0TzDXZT9z1fKvr1vCOrk8nxZ-U7wVfOJq)

- Soy Santiago Luna
- Tengo 17 años
- Estoy aprendiendo Java y Phyton 

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=santi10103cr7&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=santi10103cr7&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=santi10103cr7&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=santi10103cr7&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
  
<!---
santi10103cr7/santi10103cr7 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# Apo2
![Logo Java](https://seeklogo.com/images/J/java-logo-7833D1D21A-seeklogo.com.png)

# Apo2 Funciones.

Usamos el lenguaje JAVA para crear un programa que requiera que el usuario ingrese dos números enteros y luego use estos valores para generar operaciones de suma, resta, multiplicación y división.

### Requisitos previos

Instalar una buena IDE en este caso usamos Eclipse:


Link de instalación de Eclipse: https://www.eclipse.org/downloads/


### Instalación

Importar la libreria para que funcione JOptionPane.



import javax.swing.JOptionPane 


## Ejecutando las pruebas

Para ejecutar la prueba tenemos que presionar control+f11 o el botón de inicio para ejecutar el código.


### Dividir en pruebas de principio a fin


Este proyecto nos ayuda a solucinar las siguientes operaciones:
Suma, resta, multiplicacion y division
De numeros enteros ingresados por el usuario


### Y pruebas de estilo de codificación.


package proyecto;

package JAVA;

//Se importa una libreria que permite mostrar una interfaz (JOptionPane) 
import javax.swing.JOptionPane;

public class PROYECTO {
	
		public static void main(String[]args) {
			//Se muestra un mensaje al usuario para que digite un valor
			JOptionPane.showMessageDialog(null,"Digite un valor\n");
        	//Se muestra un mensaje para que el usuario ingrese el primer numero en el programa
			int x=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese el primer numero"));
	        //Se muestra un mensaje para que el usuario ingrese el segundo numero en el programa
			int y=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese el segundo numero"));
			
		    //Se define t como suma y como un valor entero
			int t=suma(x,y);
			//Define z como resta y como un valor entero
			int z=resta(x,y);
			//Define m como multiplicacion y como un valor entero
			int m=multiplicacion(x,y);
			//Define d como division y como un valor entero
			int d=division(x,y);
	
			//Se muestra un mensaje de lo que realizo el programa
			JOptionPane.showMessageDialog(null,"El total de la suma es: " + t ,"suma",1);
			JOptionPane.showMessageDialog(null,"El total de la resta es: " + z,"resta",1);
			JOptionPane.showMessageDialog(null,"El total de la multiplicacion es: " + m,"multiplicacion",1);
			JOptionPane.showMessageDialog(null,"El total de la division es: " + d,"division",1);

		}
		    //Permite hacer la operacion y retornar en los parametos para  dar la suma
			public static int suma(int a,int b) {
				return a+b;
			}
			
			//Permite hacer la operacion y retornar en los parametos para poder dar la resta
			public static int resta(int x,int y) {
				return x-y;
				
			}
			//Permite hacer la operacion y retornar en los parametos para poder dar la multiplicacion 
			public static int multiplicacion(int a,int b) {
				return a*b;
	
		}
			//Esto permite hacer la operacion y retornar en los parametos para poder dar la division
			public static int division(int a,int b) {
				return a/b;
	}
	}



## Construido con

JOptionPane: Se usa para darle una mejor interfaz al codigo.

## Versionado

Eclipse 2023-09 R

## Autores

* *Santiago Luna* 
* *Nicolas Maya*
* *Julian Ceballos*
 
## Licencia

Este proyecto tiene la licencia MIT; consulte el archivo LICENSE.md para obtener más detalles.







