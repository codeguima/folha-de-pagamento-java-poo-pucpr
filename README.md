# Sistema de Folha de Pagamento

Este projeto é um sistema simples de cálculo de folha de pagamento para funcionários, incluindo funcionários concursados e temporários. Ele simula a adição de dependentes, cálculo de bonificação por tempo de serviço e por filhos, além da impressão de holerites com os dados dos funcionários.

## Tecnologias Utilizadas

- **Java 8+**

## Estrutura do Projeto

O projeto é dividido em três classes principais:

1. **`Funcionario`**: Classe abstrata que define os atributos e métodos comuns para os tipos de funcionários. Ela contém informações básicas como nome, código, salário base, data de contratação, além de métodos abstratos que são implementados nas classes filhas.
   
2. **`FuncionarioConcursado`**: Classe que estende `Funcionario` e define funcionalidades específicas para funcionários concursados, incluindo o cálculo de bonificação por tempo de serviço e por filhos.

3. **`FuncionarioTemporario`**: Classe que estende `Funcionario` e define funcionalidades específicas para funcionários temporários, com bonificação diferenciada por tempo de serviço e por filhos.

4. **`Dependente`**: Classe representando um dependente, utilizado para adicionar filhos aos funcionários, com controle de idade e limite de filhos permitidos para bonificação.

## Funcionalidades

### **1. Cálculo de Bonificação**
   - **Bonificação por Tempo de Serviço**: Calcula o valor da bonificação de acordo com o tempo de serviço do funcionário.
   - **Bonificação por Filho**: Calcula a bonificação por filho, com limite de até 5 filhos, de acordo com a faixa etária.

### **2. Impressão de Holerite**
   - O sistema gera um holerite com informações sobre o salário base, tempo de serviço, e bonificação de cada funcionário.

### **3. Limitação de Filhos**
   - O número de filhos para calcular a bonificação é limitado a 5, com diferentes faixas etárias para funcionários concursados e temporários.

## Como Usar

### 1. Clone o repositório:

```bash
https://github.com/codeguima/folha-de-pagamento-java-poo-pucpr.git
