# Data Types and Variables
Repositorio para estudos java


##Variáveis
As variáveis são posições na memória do computador que podem armazenar dados. As variáveis são formadas por quatro elementos: nome, tipo, tamanho e valor.
Dependendo da programação, o básico de uma declaração de variável pode ter somente um tipo, um nome e um valor.

```
public class Variaveis {

	public static void main(String[] args) {
		
		int valorA = 33;
		int valorB = 25;
		
		int total = valorA + valorB;		
		
		System.out.printf("A soma total = %d",total);
	}
}

```

O Java possui dois tipos de dados que são divididos em por valor (tipos primitivos) e por referência (tipos por referência).
Os tipos primitivos são boolean, byte, char, short, int, long, float e double. Os tipos por referência, são classes que especificam os tipos de objeto Strings, Arrays Primitivos e Objetos.
Uma variável do tipo primitivo pode armazenar exatamente um valor de seu tipo declarado por vez, quando outro valor for atribuído a essa variável, seu valor inicial será substituído.
As variáveis de instância de tipo primitivo são inicializadas por padrão, as variáveis dos tipos byte, char, short, int, long, float e double são inicializadas como 0, e as variáveis do tipo boolean são inicializadas como false. Esses tipos podem especificar seu próprio valor inicial para uma variável do tipo primitivo atribuindo à variável um valor na sua declaração.
