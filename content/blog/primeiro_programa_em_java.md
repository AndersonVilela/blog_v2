---
title: 'Primeiro Programa em Java'
description: 'Criando nosso primeiro programa em java'
img: 'img/primeiro_program.jpg'
tags: [Java, Code, Learning]
---
# Meu primeiro código em java
Se você está interessado em aprender a programar em Java, este guia é perfeito para você. Vamos passar por todos os passos necessários para criar seu primeiro programa em Java, desde a instalação até a execução.

## O que é Java?
Java é uma linguagem de programação de alto nível, orientada a objetos e amplamente utilizada em todo o mundo para desenvolvimento de software. É uma linguagem versátil que pode ser usada para desenvolver aplicativos de desktop, aplicativos web, aplicativos móveis e jogos. Além disso, a linguagem Java é multiplataforma, o que significa que os programas escritos em Java podem ser executados em qualquer sistema operacional.

## Instalando o Java
Antes de começarmos, é necessário ter o Java instalado em seu computador. Você pode baixar a versão mais recente do Java no site oficial da Oracle. Certifique-se de selecionar a versão adequada para o seu sistema operacional.

## Criando um programa simples em Java
Vamos criar um programa simples em Java que exibe a mensagem "Olá, mundo!" na tela. Abra o bloco de notas ou o seu editor de texto preferido e digite o seguinte código:

```js
public class OlaMundo {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
```
## Vamos explicar cada linha do código:

- A primeira linha define a classe OlaMundo. Em Java, todos os programas devem estar em uma classe.
- A segunda linha define o método main, que é o ponto de entrada do programa. Todas as instruções dentro do método main serão executadas quando o programa for executado.
- A terceira linha usa o objeto System.out para imprimir a mensagem "Olá, mundo!" na tela.

Salve o arquivo com o nome OlaMundo.java. Certifique-se de salvá-lo em um local fácil de encontrar no seu computador.

## Compilando o programa
Agora que você escreveu o código, é hora de compilá-lo. O compilador Java é responsável por transformar o código em linguagem de máquina que pode ser executada pelo computador.

Abra o prompt de comando ou o terminal do seu sistema operacional e navegue até o diretório onde o arquivo OlaMundo.java foi salvo. Digite o seguinte comando:

```bash
javac OlaMundo.java
```
Se o código estiver correto, o compilador Java gerará um arquivo chamado OlaMundo.class no mesmo diretório.

Executando o programa
Agora que você compilou o programa com sucesso, é hora de executá-lo. Ainda no prompt de comando ou no terminal, digite o seguinte comando:

```bash
java OlaMundo
```
Isso executará o programa e a mensagem "Olá, mundo!" será exibida na tela.

## Conclusão
Neste guia, você aprendeu a criar e executar um programa simples em Java. Embora este programa não faça muito, é um ótimo ponto de partida para começar a aprender Java. À medida que você se torna mais confortável com a linguagem, você pode começar a criar programas mais complexos e úteis. Lembre-se de que a prática é a chave para o sucesso na programação!
