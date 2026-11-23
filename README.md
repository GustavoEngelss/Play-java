# Escola Sistêmica · Lógica de Programação com Java

> **Para orientadores e colaboradores**
>
> **Leia-me** — Trilha de Lógica de Programação com Java: organização do material e orientações

---

## Sobre esta trilha

Esta trilha ensina os fundamentos de lógica de programação usando **Java**. Ela segue a mesma sequência de assuntos e os mesmos exercícios das trilhas de VisuAlg e de Python, para que estudantes das três trilhas possam ser acompanhados da mesma forma.

O conteúdo foi adaptado ao que é próprio do Java: compilação e JVM, tipos declarados, `Scanner`, comparação de textos com `equals`, `switch`, `do-while` e vetores de tamanho fixo.

A trilha cobre apenas **lógica de programação**. Classes, objetos, encapsulamento, herança e os demais temas de orientação a objetos ficam para uma trilha posterior. Até lá, a classe é usada só como "embalagem" do programa, e o desafio final introduz métodos `static`.

---

## Ordem dos materiais

| Ordem   | Material                                  | Tipo                    |
| ------- | ----------------------------------------- | ----------------------- |
| 0.0     | Introdução ao Java (Parte 1)              | Explicação              |
| 0.1     | Introdução ao Java (Parte 2)              | Explicação              |
| 1       | Lista 1 — Entrada e saída                 | Exercícios              |
| 2 / 2.1 | Estrutura condicional `if` / Lista 2      | Explicação / Exercícios |
| 3 / 3.1 | Estrutura `switch-case` / Lista 3         | Explicação / Exercícios |
| 4 / 4.1 | Estrutura de repetição `for` / Lista 4    | Explicação / Exercícios |
| 5 / 5.1 | Estruturas `while` e `do-while` / Lista 5 | Explicação / Exercícios |
| 6 / 6.1 | Vetores (arrays) / Lista 6                | Explicação / Exercícios |
| 7 / 7.1 | Matrizes / Lista 7                        | Explicação / Exercícios |
| 8       | Desafio final                             | Projeto                 |

O estudante lê cada explicação, testa os exemplos no IntelliJ e valida com um orientador **antes** de começar a lista correspondente. As resoluções comentadas e o gabarito são de uso exclusivo dos orientadores.

---

## Convenções adotadas em todos os materiais

- **Versão do Java:** JDK 17 ou superior; recomendamos a LTS mais recente (Java 25). Todo o código foi testado com o JDK 21.
- **Ambiente:** IntelliJ IDEA. A partir da versão 2025.3 ele é distribuído como um único produto, e todos os recursos usados na trilha são gratuitos.
- **Estrutura dos programas:** forma tradicional, com `public class` e `public static void main(String[] args)`. Os arquivos compactos do Java 25 (`void main()` e `IO.println`) são apresentados apenas como curiosidade, porque a forma tradicional funciona em qualquer versão e é a encontrada nos projetos reais.
- **Organização:** um único projeto no IntelliJ, com uma classe por exercício (`Lista1Ex01`, `Lista1Ex02`...).
- **Nomes:** `camelCase` para variáveis e métodos, `PascalCase` para classes e `MAIÚSCULAS` para constantes, como é a convenção do Java.
- **Entrada:** `Scanner` com `nextLine`, `next`, `nextInt` e `nextDouble`. A armadilha do `nextInt()` seguido de `nextLine()` é explicada na introdução.
- **Números reais digitados:** os exemplos consideram o computador configurado em português, em que o `Scanner` espera **vírgula** (`1,75`). Em um sistema em inglês, o estudante deve digitar ponto. Os valores mostrados com `printf` seguem a mesma regra.
- **`switch`:** a forma com seta (`case 1 ->`) é a principal. A forma clássica com `break` é apresentada para que o estudante a reconheça.
- **Repetições:** `for`, `while` e `do-while`, equivalentes ao *para-faça*, *enquanto-faça* e *repita-até* do VisuAlg.
- **Índices:** vetores e matrizes começam no índice 0; quando o usuário escolhe uma posição, ele digita a partir de 1 e o programa faz a conversão.
- **Exercícios:** mesma numeração das outras trilhas. Exercícios novos aparecem apenas na seção "Desafios extras (opcionais)" de cada lista.

---

## Pontos de atenção na validação

Alguns erros são típicos de quem está aprendendo Java e merecem atenção especial:

- Comparar textos com `==` em vez de `equals` (o programa compila, mas não funciona como esperado).
- Divisão entre dois `int` quando se esperava resultado com casas decimais (`7 / 2` dá `3`).
- `;` logo depois do `if (...)` ou do `for (...)`, que deixa o bloco vazio.
- Esquecer o `break` no `switch` clássico.
- Usar uma variável fora do bloco em que ela foi declarada (por exemplo, a condição do `do-while` usando uma variável declarada dentro dele).
- `nextInt()` seguido de `nextLine()`, que "pula" uma leitura.

---

## Resoluções e gabarito

Junto com esta trilha há uma resolução comentada para cada lista, com o código completo, exemplos reais de execução e pontos de atenção, e uma pasta de **gabarito** com os arquivos `.java` de todas as soluções, inclusive dos desafios extras e dos dois jogos do desafio final.

Outras soluções corretas devem ser aceitas, desde que o estudante saiba justificá-las.
