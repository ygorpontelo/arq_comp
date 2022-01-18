# Disciplina SCE541 - Arquitetura de Computadore


Nome: Altair Fernando Pereira Junior            Nº USP: 9391831

Nome: Guilherme Holanda Sanches              Nº USP: 10734370

Nome: Ygor Pontelo                                       Nº USP: 10295631

## O quê estes dois dispositivos icônicos de uma era tão próspera têm em comum?
 * Processador Qualcomm MSM7000 series
  * Possui 4 núcleos de processamento, mas apenas um é utilizado para rodar o sistema operacional e aplicativos.
  1. Este é o ARM11(ARM1136J-S)
  1. Os outros núcleos lidam com a telefonia celular e processamento de mídias

## ARM 11
 * Arquitetura RISC
 * Interpreta dois conjuntos de instruções: ARM 32 bit e Thumb 16 bit instruction sets
 * Modo ARM
* 16 registradores de uso geral
* 7 registradores que indicam o modo de operação(usuário, sistema..)
* 17 registradores para gerenciamento de exceções
 * Thumb instruction set: Reduz o tamanho do código para dispositivos que possuem pouca memória
* 11 registradores

## Previsão de branches
Duas abordagens:
 * Predição estática pelo core:
  * Por padrão aceita jumps para trás(loops) e recusa jumps para frente
 * Predição dinâmica
  * BTAC(Branch Target Address Cache) - Prefetch Unit
    * Armazena o endereço de branch e dois bits para indicar a probabilidade de ela acontecer
      * strongly predict branch - taken
      * weakly predict branch - taken
      * wakly predict branch - not taken
      * strongly predict branch - not taken
    * A predição é atualizada quando o resultado do condicional é resolvido
      

## Video Apresentação

* Link da apresentação no youtube: https://www.youtube.com/watch?v=TxoDH6ibqf8&ab_channel=YgorPontelo

  
 

