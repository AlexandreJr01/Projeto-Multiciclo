# 🧠 Projeto Multiciclo MIPS

Simulador de um processador **MIPS Multiciclo** implementado em **C**, desenvolvido por uma equipe de três integrantes ao longo de **quatro sprints**.

---

## 😎 Descrição

Este simulador interpreta e executa **instruções binárias no formato MIPS**, utilizando a **arquitetura multiciclo**, em que cada instrução é dividida em múltiplos ciclos de clock, otimizando o uso dos componentes do processador.

Durante a execução, o simulador é capaz de:

- Carregar um arquivo `.mem` contendo as **instruções binárias e os dados**.  
- Salvar:
  - Um arquivo `.asm` com as instruções **decodificadas**.  
  - Um arquivo `.mem` com o **conteúdo atualizado da memória**.  
- Realizar **retrocesso (back)** de estados, por meio de uma **pilha de estados**, permitindo retornar a múltiplas etapas anteriores da simulação.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** C  
- **Arquitetura:** MIPS Multiciclo  
- **Estruturas de Dados:** Pilha (Stack)  
- **Bibliotecas:** `stdio.h`, `stdlib.h`, `string.h`, `math.h`

---

## 🚀 Como Executar

1. Compile o código com o compilador de sua preferência:
   ```bash
   gcc Multiciclo.c TAD.c -o Multiciclo
2. Execute
   ```bash
   ./Multiciclo
