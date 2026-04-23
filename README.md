# Projeto da ULA
Projeto de Sistemas Digitais do Curso de Engenharia da Computação na UFPE

# Descrição:
Objetivo: Desenvolver uma ULA (Unidade Lógica e Aritmética) integrada a um decodificador binário para display de 7 segmentos.

Restrição Principal: O projeto deve ser construído exclusivamente utilizando portas lógicas.

Software: Intel Quartus Prime 25.1 (para a criação dos diagramas de portas lógicas).

Hardware: Placa de prototipação Altera DE2-115 (equipada com o chip da família Cyclone IV E) para a execução do projeto.

# Grupo:
Geovana Pereira de Santana Soares (gpss)

Gustavo Franco Pires (gfp)

João Victor Siqueira (jvsbs)

Kayque Tavares Marcelino da Costa (ktmc)

# Projeto:
# 1. ULA

1. Entradas:

Operandos A e B: 5 bits cada (1 para sinal, 4 para magnitude). Sinal 1 = negativo, 0 = positivo. O usuário insere o valor direto, sem se preocupar com complemento de 2.

Seletor S: 3 bits para definir a operação.

2. Saídas:

Resultado F: 6 bits (1 para sinal, 5 para magnitude). O tratamento de complemento de 2 ocorre apenas internamente.

LED de Status (1 bit): Mostra o resultado de operações booleanas de comparação (=, >, <).

LEDs de Replicação: Replicam a saída F para operações aritméticas e lógicas bit a bit.

# 2. Decodificador BCD para Display de 7 Segmentos

Regra de Funcionamento: Os displays acendem com nível lógico 0. Eles devem ser ativados apenas para soma e subtração (devem permanecer apagados nas outras operações).

1. Entrada: 5 bits do resultado (magnitude + carry). O bit de sinal é isolado e enviado diretamente para um LED específico.

2. Saídas: Controle para 2 displays (dezenas e unidades), projetados para exibir um valor máximo de até 30.

# Imagens:
<img width="579" height="266" alt="image" src="https://github.com/user-attachments/assets/50d6693b-b60e-4eaf-807b-47c224637711" />

<img width="586" height="277" alt="image" src="https://github.com/user-attachments/assets/a6c8e21b-8eb3-405b-9d89-23d942326711" />

# Links:
* Tabela da Verdade e Mapa de Karnaugh: https://docs.google.com/spreadsheets/d/1VzDZzGMTBDK7ysYWcsD35G4WGZj6BByjK8DRsoYJKxw/edit?usp=sharing
<<<<<<< HEAD
Tabelas e Mapa de Karnaugh para Unidade Aritimética: https://docs.google.com/spreadsheets/d/1-m4WqJ639HKql3GFfasfa7XLne40sfkX79NmtemCtkQ/edit?usp=sharing
=======
Tabela da Verdade e Mapa de Karnaugh para Unidade Aritimética: https://docs.google.com/spreadsheets/d/1-m4WqJ639HKql3GFfasfa7XLne40sfkX79NmtemCtkQ/edit?usp=sharing
>>>>>>> d1787beb81aa57943c0475fb24fff348377f4c08
