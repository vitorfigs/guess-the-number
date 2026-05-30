# Projeto: Guess the Number
**Início: 24/05**  
**Disciplina:** Circuitos Digitais | **UFCA** - Universidade Federal do Cariri | **Professor:** Ramon Nepomuceno

## Sobre o projeto
Sistema de **adivinhação de números binários** aleatórios de 4 bits desenvolvido no **Logisim**. O circuito avalia o palpite do jogador, calcula a distância em relação ao valor correto e fornece a distância baseada na intensidade das cores **vermelha** (perto) e **azul** (longe).  


  ## 📅 Desenvolvimento
| Data | Atividade |
| :--- | :--- |
| 24/05 | Planejamento e organização do projeto|
| 25/05 | Início da implementação do subcircuito `circuito_diferenca`. |
| 28/05 | Início da implementação do subcircuito `circuito_comparador`. |

## - Subcircuitos 2/4...

### I. Circuito "Diferença"

* **Objetivo:** Calcular a distância $|A - B|$ entre o chute do usuário e a resposta.
   
* **Componentes:**  
    * 2 subtratores de 4 bits feitos manualmente, um para A-B, outro para B-A.
    * 1 Multiplexador (MUX) manual 2x1 para seleção do resultado positivo $|A - B|$.
    * 3 pinos: Escolha do Usuário, da CPU e Distância.
        
* **Desafios/Bugs**
   * Implementação manual dos subtratores.
   * Falha na lógica de Borrow-out.
   * Inversão dos BITS no Distribuidor.

<br>
<br>

### II. Circuito "Comparador" (...)

* **Objetivo:** Verificar a possível igualdade entre o número A _(chute do usuário)_ e B _(resposta)_.
   
* **Componentes:**
  * 1 Comparador de identidade de 4 bits.
  * 3 pinos: Escolha do Usuário, da CPU e bool da igualdade entre A e B.
        
* **Desafios/Bugs**
    <p>$$\Huge\emptyset$$</p>
    
<br>
<br>

### III. Circuito “Cores” (Não iniciado)


### IV. Decodificador para Display de 7 segmentos (Não iniciado)
