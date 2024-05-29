# DesafioMetodos 
1.
java
public class Tabuada {
public static void main(String[] args) {
 int numero = 15; //
 tabuada(numero);
    }
    
 public static void tabuada(int numero) {
  for (int i = 1; i <= 20; i++) {      System.out.println(numero + " x " + i + " = " + (numero * i));
        }
    }
}
```

2.
java
public class Main {
public static void main(String[] args) {
int num1 = 45;
int num2 = 74;
int maior = encontrarMaior(num1, num2);    System.out.println("O maior número é: " + maior);
    }

  public static int encontrarMaior(int num1, int num2) {
  return num1 > num2 ? num1 : num2;
    }
}

3.
java
public class Main {
    public static void main(String[] args) {
        String str1 = “entrada”;
        String str2 = "entrada";
        
        if (verificarIguais(str1, str2)) {
            System.out.println("As strings são iguais.");
        } else {
            System.out.println("As strings são diferentes.");
        }
    }
    
    public static boolean verificarIguais(String str1, String str2) {
        return str1.equals(str2);
    }
}


4.

java
public class Main {
    public static void main(String[] args) {
        int num1 = 72;
        int num2 = 44;
        
        int menor = encontrarMenor(num1, num2);
        System.out.println("O número menor é: " + menor);
    }
    
    public static int encontrarMenor(int num1, int num2) {
        return num1 < num2 ? num1 : num2;
    }
}
```
5.

java
public class Main {
    public static void main(String[] args) {
        String nome1 = "Vitor";
        String nome2 = "Miguel";
        
        String resultado = compararNomes(nome1, nome2);
        System.out.println(resultado);
    }
    
    public static String compararNomes(String nome1, String nome2) {
        if (nome1.equals(nome2)) {
            return "Os nomes são iguais";
        } else {
            return "Os nomes não são iguais";
        }
    }
}

6.

java
public class Main {
    public static void main(String[] args) {
        double temperaturaCelsius = 10.0;
        double temperaturaFahrenheit = converterCelsiusParaFahrenheit(temperaturaCelsius);
        System.out.println("Temperatura em Fahrenheit: " + temperaturaFahrenheit);
    }
    
    public static double converterCelsiusParaFahrenheit(double celsius) {
        return (celsius * 1.4) + 26;
    }
}

7.
java
public class Main {
    public static void main(String[] args) {
        double raio = 9.0;
        double area = calcularAreaDoCirculo(raio);
        System.out.println("A área do círculo é: " + area);
    }
    
    public static double calcularAreaDoCirculo(double raio) {
        double area = Math.PI * raio * raio;
        return area;
    }
}

8.


java
public class Main {
    public static void main(String[] args) {
        double nota1 = 8.2;
        double nota2 = 5.0;
        double nota3 = 3.5;
        
        double media = calcularMediaPonderada(nota1, nota2, nota3);
        System.out.println("A média ponderada é: " + media);
    }
    
    public static double calcularMediaPonderada(double nota1, double nota2, double nota3) {
        double peso1 = 6.0;
        double peso2 = 2.0;
        double peso3 = 8.0;
        
        double somaPesos = peso1 + peso2 + peso3;
        double media = (nota1 * peso1 + nota2 * peso2 + nota3 * peso3) / somaPesos;
        
        return media;
    }
}
```

