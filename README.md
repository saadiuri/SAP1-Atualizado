# SAP1-Atualizado

Este projeto visa a melhoria e expansão funcional da arquitetura do processador SAP-1, no contexto da disciplina de Arquitetura de Computadores 1.

O trabalho é uma evolução dos projetos desenvolvidos anteriormente pelos alunos:
- André Luís Silva de Paula
- André Santos Alves
- Nathan de Araújo Cunha Lisboa
- Pedro Malta Boscatti
- Sophia Damasceno Satuf

O projeto foi disponibilizado pelo professor Cláudio Dias Campos.

> [!WARNING]
> Compatibilidade: Este projeto é compatível exclusivamente com o simulador [Logisim](http://www.cburch.com/logisim/). Não é garantido

## Melhoria Proposta
Este projeto é uma implementação do modelo [sap1-turbo](https://github.com/andreeluis/sap1-turbo) do aluno André Luís Silva de Paula com diversas melhorias em suas funcionalidades originais, permitindo a execução de programas mais complexos. As melhorias incluem:
  Melhorias Implementadas:
    
    Operações matemáticas adicionais
    Divisão: Instrução para realizar a divisão de valores.
    Multiplicação: Instrução para multiplicar dois valores.
    Comparadores lógicos
    Maior que: Permite verificar se um valor é maior que outro.
    Igual: Permite verificar se dois valores são iguais.
    Menor que: Permite verificar se um valor é menor que outro.
    Controle de fluxo
    Jump: Instrução para alterar o fluxo de execução, permitindo saltos no código baseado em condições lógicas.
    Armazenamento
    Save: Função para armazenar valores intermediários em memória durante a execução do programa.
    Execução do Cálculo de Fibonacci
    Este SAP-1 aprimorado também foi projetado para executar um programa que calcula a sequência de Fibonacci. O programa de Fibonacci está implementado como um programa em outro SAP independente e utiliza as funcionalidades aprimoradas descritas acima.

    

## Como Executar
O sistema utiliza duas ROMs no contador-sequenciador: uma para endereços e outra para o controle. Caso as ROMs não contenham o conteúdo correto, você pode carregá-las a partir de arquivos de texto.
Arquivos de ROM
Os arquivos necessários para as ROMs estão disponíveis na pasta [`/instucoesSap1`](/instucoesSap1/).

