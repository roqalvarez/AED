# **01 - Adicion**

## **Etapa #1 Análisis del problema**

### **Transcripción del problema**
* Mostrar la suma de dos números ingresados por un usuario. Escribir el codigo del programa que realizara la suma. Modelo IPO.

### **Refinamiento e Hipótesis de trabajo**

-Refinamiento del problema: Desarrollar un programa capaz de realizar la adición de dos números enteros ingresados por un usuario.

-Hipótesis: Se pide al usuario que ingrese los valores por consola. Una vez ingresados comenzara a realizar la adición de los valores y mostrará el resultado en la consola. 

NOTA: *Para que los valores sean válidos tienen que pertenecer al grupo de los enteros*

Acotación: En esta fase definimos la idea de que es lo necesitamos y proyectar la forma que va a trabajar el programa.

### **Modelo IPO**
Este lo utilizamos para darle dominio a nuestro problema como los pasos anteriores pero esta vez de una manera mas visual.

![modeloipo](https://user-images.githubusercontent.com/63470026/81332593-b5936600-9079-11ea-94d3-53a4416fcc08.jpg)


# **Etapa #2: Diseño de la solución del problema**

## **Léxico**

El léxico es la definición de elementos utilizados en el algoritmo. Pensandolo como una función matemática podriamos decir que le damos un dominio a la solución.

**a,b ϵ Z**


## **Representación del Algoritmo**

### **Representación Visual**

Pseudocódigo:

1. Ingrese un numero entero "a"
2. Ingrese otro numero entero "b"
3. La adicion de los numeros es:

Diagrama de Flujo:

![diagramadeflujo](https://user-images.githubusercontent.com/63470026/81332956-37838f00-907a-11ea-9ed6-78acb5846889.png)


### **Representación Textual**

textual:

1. Mostrar "ingrese un numero entero: "
2. Leer un numero entero y almacenarlo en a
3. Mostrar "ingrese otro numero entero: "
4. Leer un numero entero y almacenarlo en b
5. mostrar "la adicion de los numeros es: "
6. mostrar a + b

Representacion textual en C++

```c++
int main()
{
cout << "ingrese un numero entero: \n";
int a;
cin >> a;
cout << "ingrese otro numero entero: \n";
int b;
cin >> b;
int s;
s = a + b;
cout << "la adicion de los numeros es: " << s << endl;
system("pause");
return 0;
}
```
