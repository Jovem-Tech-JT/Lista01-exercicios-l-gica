# 💜🧠 Lista de Exercícios 01 de Lógica de Programação - Jovem Tech - Polo Estaleiro 💜💜

Bem-vindo(a) à nossa lista de exercícios! Esta é uma coleção prática para te ajudar a dominar os fundamentos da programação. Os desafios estão divididos por nível de dificuldade e cobrem conceitos essenciais como variáveis, condicionais, laços, operadores e muito mais.

> **🎯 Objetivo:** Praticar lógica de programação usando a linguagem de sua preferência!

---

## 📚 Organização dos Exercícios

Clique em cada módulo para ver os exercícios completos:

<details>
<summary>🔹 Módulo 1 — Iniciante</summary>

1. **Soma e comparação**  
Faça um algoritmo que leia os valores de A, B e C. Em seguida, calcule a soma entre A e B. Mostre essa soma na tela e diga se ela é menor que C.

2. **Antecessor e sucessor**  
Peça para o usuário digitar um número inteiro. O programa deve mostrar o número anterior e o número seguinte.

3. **Quantos salários mínimos?**  
Leia o valor do salário do usuário e calcule quantos salários mínimos ele recebe.  
Use como base o salário mínimo de R$ 1.293,20.

4. **Valor com reajuste**  
Peça ao usuário um valor qualquer e mostre o novo valor com reajuste de 5%.

5. **Média de três notas**  
Leia três notas de um aluno e mostre a média entre elas.

6. **Maior ou menor de idade**  
Leia o nome e a idade de uma pessoa. Mostre o nome e se ela é maior ou menor de idade.

7. **Troca de valores**  
Receba dois valores: A e B. Troque os valores entre si e mostre o novo conteúdo de A e B.

8. **Conversão de temperatura**  
Receba uma temperatura em Fahrenheit e mostre o valor equivalente em Celsius.  
Fórmula: C = (5 * (F - 32)) / 9

9. **Divisão inteira com resto**  
Peça dois números inteiros A e B. Mostre o quociente (resultado da divisão inteira) e o resto.

10. **Verificando o maior número**  
Receba dois valores e mostre qual deles é o maior. Se forem iguais, avise o usuário.

11. **Número dentro de intervalo**  
Peça ao usuário para informar um número. Mostre se ele está entre 10 e 50 (inclusive).

</details>

<details>
<summary>🔸 Módulo 2 — Intermediário</summary>

12. **Par ou ímpar, positivo ou negativo**  
Receba um número qualquer. Mostre se ele é par ou ímpar, e se é positivo ou negativo.

13. **Soma ou multiplicação**  
Peça dois números A e B.  
Se forem iguais, some-os.  
Se forem diferentes, multiplique.  
Guarde o resultado em C e exiba-o.

14. **Operadores lógicos**  
Peça dois valores lógicos (booleanos). Verifique se ambos são VERDADEIROS ou FALSOS.

15. **Números em ordem decrescente**  
Receba três números inteiros diferentes e mostre-os em ordem decrescente.

16. **Média e aprovação**  
Peça o nome de um aluno e quatro notas. Calcule a média.  
Se a média for maior ou igual a 7, mostre que ele foi aprovado.  
Caso contrário, reprovado.

17. **Forma de pagamento**  
Leia o valor de um produto e o código da forma de pagamento. Mostre o valor final a ser pago.  
Tabela de códigos:  
1 - À vista (Dinheiro/Pix): 15% de desconto  
2 - À vista (Cartão): 10% de desconto  
3 - 2x no cartão: preço normal  
4 - 3x ou mais: juros de 10%

18. **Tipo de triângulo**  
Receba três valores e verifique se eles podem formar um triângulo.  
Se sim, diga se é:  
- Equilátero (3 lados iguais)  
- Isósceles (2 lados iguais)  
- Escaleno (todos diferentes)

19. **Salário líquido do professor**  
Receba:  
- Valor da hora/aula  
- Quantidade de aulas no mês  
- Porcentagem de desconto do INSS  
Calcule e mostre o salário líquido do professor.

20. **Combustível gasto na viagem**  
Peça o tempo de viagem (em horas) e a velocidade média.  
Sabendo que o carro faz 12km/L, calcule:  
- A distância  
- A quantidade de combustível usada  
Fórmulas:  
- distância = tempo × velocidade  
- litros = distância ÷ 12

</details>

<details>
<summary>🔺 Módulo 3 — Avançado</summary>

21. **Cálculo do IMC**  
Receba peso e altura. Calcule o IMC com a fórmula:  
IMC = peso / (altura²)  
Mostre a categoria conforme a tabela:

| IMC              | Condição                   |
|------------------|----------------------------|
| Abaixo de 18,5   | Abaixo do peso             |
| 18,6 a 24,9      | Peso ideal (parabéns)      |
| 25,0 a 29,9      | Levemente acima do peso    |
| 30,0 a 34,9      | Obesidade grau I           |
| 35,0 a 39,9      | Obesidade grau II (severa) |
| 40 ou mais       | Obesidade grau III (mórbida)|

22. **Idade em anos, meses e dias**  
Peça o ano de nascimento do usuário e calcule:  
- Quantos anos  
- Quantos meses  
- Quantos dias ele já viveu  
(Considere o ano com 365 dias e mês com 30 dias)

23. **Crescimento de Francisco e Sara**  
Francisco: 1,50m e cresce 2cm/ano  
Sara: 1,10m e cresce 3cm/ano  
Mostre em quantos anos Sara ficará mais alta que Francisco.

24. **Tabuada de 1 até 10**  
Mostre a tabuada de multiplicação do 1 até o 10.

25. **Tabuada personalizada**  
Peça ao usuário um número inteiro. Mostre a tabuada desse número de 1 a 10.

26. **Valor aleatório**  
Mostre um número aleatório entre 0 e 100.  
Dica: Use bibliotecas como `Math.random()` (em JavaScript, por exemplo).

</details>

---

## 🚀 Como Entregar os Exercícios

Siga os passos abaixo para enviar suas respostas:

1. **Faça um fork** deste repositório para sua conta.
2. **Clone** o fork para sua máquina:
   ```bash
   git clone https://github.com/SEU_USUARIO/Lista01-exercicios-logica.git
   ```
3. Crie uma pasta com o **seu nome ou usuário**, por exemplo:
   ```bash
   mkdir joao
   ```
4. Resolva os exercícios dentro dessa pasta, cada exercício em um arquivo separado. Use **a linguagem de sua preferência** (`.py`, `.js`, `.java`, etc).

5. Depois de resolver, **dê um commit e um push**:
   ```bash
   git add .
   git commit -m "Resolução dos exercícios do Módulo 1"
   git push origin main
   ```

6. Por fim, **crie um Pull Request** para este repositório original.

---

## 🗣️ Observações Importantes

- ✅ Você pode usar **qualquer linguagem de programação**.
- 💬 Se tiver dúvidas, avise.
- 🧹 Mantenha seu código organizado e nomeie os arquivos de forma clara, por exemplo: `exercicio01.py`, `exercicio02.js`, etc.

---

**Autor:** Caio Moreira
