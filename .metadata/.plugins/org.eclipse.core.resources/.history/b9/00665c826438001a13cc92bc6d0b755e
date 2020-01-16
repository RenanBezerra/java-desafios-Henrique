package br.com.main;

import java.util.ArrayList;
import java.util.List;

import br.com.model.Pessoa;

public class teste {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Pessoa p1 = new Pessoa("João", 15);
		Pessoa p2 = new Pessoa("Leandro", 21);
		Pessoa p3 = new Pessoa("Paulo", 17);
		Pessoa p4 = new Pessoa("Jessica", 18);

		List<Pessoa> pessoas = new ArrayList<>();
		pessoas.add(p1);
		pessoas.add(p2);
		pessoas.add(p3);
		pessoas.add(p4);

// imprime o nome de todos 
		for (Pessoa pessoa : pessoas) {
			System.out.println("Nome: " + pessoa.getNome() + "  Idade: " + pessoa.getIdade());
		}
// imprime o nome do mais velho
		int maior = 0;
		String nomeMaior = "", nomeMenor = "";
		for (Pessoa pessoa : pessoas) {
			if (pessoa.getIdade() > maior) {
				maior = pessoa.getIdade();
				nomeMaior = pessoa.getNome();
			}

		}
		System.out.println("A pessoa mais velha é " + nomeMaior + " " + maior);
		int menor = maior;
//imprime o nome do menor
		for (Pessoa pessoa : pessoas) {
			if (pessoa.getIdade() < menor) {
				menor = pessoa.getIdade();
				nomeMenor = pessoa.getNome();
			}
			;
		}
		System.out.println(" A pessoa mais nova é " + nomeMenor + " " + menor);

// removendo o mais novo
		System.out.println("impressão antes de removido");
		for (int i = 0; i < pessoas.size(); i++) {
			System.out.println(pessoas.get(i).getNome()+ "");
		}
		
		for (int i = 0; i < pessoas.size(); i++) {
			Pessoa p = pessoas.get(i);
			
			if (p.getIdade() < 18) {		
				pessoas.remove(p);
			}

		}
		System.out.println("impressão depois de removido");
		for (int i = 0; i < pessoas.size(); i++) {
			System.out.println(pessoas.get(i).getNome()+ "");
		}
		
//	exibindo o nome de jessica
		for (Pessoa pessoa : pessoas) {
			if(pessoa.getNome() == "Jessica") {
				System.out.println(pessoa.getNome()+" "+pessoa.getIdade());
			}
			
}

	}
}
