# MAGALU
Exercicios
package br.com.gama.Aula2;

import java.util.Scanner;

public class Custo {

	public static void main (String[] args) {
		float vr, pc, vc;
		
		Scanner sc = new Scanner(System.in);
		
		
		System.out.println("Digite o valor do custo de fabrica");
		vr = sc.nextFloat();
		
		pc = ((28.0/100)+(45.0/100));
		vc = vr + pc;
		
		System.out.println("O valor do custo de fabrica: "+vr);
		
		
		System.out.println("O valor final ao distribuidor e : "+vc);
		
		
	}

}

