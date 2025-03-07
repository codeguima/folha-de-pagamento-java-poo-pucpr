# folhapagamento.java
# Projeto Básico de POO em Java

Este é um exemplo simples de um projeto em Java, utilizando os conceitos de Programação Orientada a Objetos (POO). O objetivo deste projeto é demonstrar a aplicação de classes, objetos, herança, encapsulamento e polimorfismo de maneira prática e acessível.

## Tecnologias Utilizadas

- **Java 11+**
- **IDE recomendada:** IntelliJ IDEA, Eclipse, NetBeans ou qualquer editor de sua preferência.

## Estrutura do Projeto

Este projeto contém as seguintes classes e funcionalidades principais:

1. **Classe `Funcionario`**: Representa uma funcionario com atributos como codigo, salario e bonus.
2. **Classe `FuncionarioConcursado`**: Herda de `Funcionario` e adiciona atributos como matrícula e curso.
3. **Classe `FuncionarioTemporario`**: Herda de `Pessoa` e adiciona atributos como especialidade e departamento.
4. **Classe `Main`**: Contém o método principal para rodar o programa e testar a funcionalidade das classes.

## Funcionalidades

- **Encapsulamento**: Os atributos das classes são privados e acessados através de métodos getter e setter.
- **Herança**: A classe `Aluno` e a classe `Professor` herdam de `Pessoa`, compartilhando os mesmos atributos e métodos.
- **Polimorfismo**: Métodos como `imprimirInformacoes()` são sobrescritos nas classes filhas `Aluno` e `Professor` para fornecer implementações específicas.

## Como Usar

### 1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/projeto-poo-java.git

