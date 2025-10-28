🃏 Super Trunfo – Comparação de Cartas de Países 🌍
Projeto desenvolvido para prática em linguagem C

📌 Descrição do Projeto
Este programa em C simula uma mecânica do jogo Super Trunfo, permitindo o cadastro de duas cartas de países e a comparação entre elas com base em atributos numéricos.
O jogador escolhe no menu qual atributo deseja utilizar para a disputa. O programa então calcula e exibe qual carta venceu ou se houve empate.
Este exercício faz parte da evolução de desafios da disciplina, trabalhando:

✔ Entrada de dados com scanf
✔ Cálculos numéricos (densidade demográfica e PIB per capita)
✔ Estruturas condicionais if/else
✔ Estrutura de seleção switch
✔ Exibição organizada de resultados no terminal

🛠️ Tecnologias Utilizadas

Linguagem C
Compilador GCC (padrão sugerido)
Terminal / Linha de comando

▶️ Como Compilar
No terminal, execute o comando abaixo dentro da pasta do projeto:
gcc super_trunfo.c -o super_trunfo
Se não houver erros, o arquivo executável será criado.

🚀 Como Executar
No Linux/macOS:
./super_trunfo
No Windows (PowerShell ou CMD):
super_trunfo.exe

🎮 Como Jogar
Informe os dados da Carta 1
Informe os dados da Carta 2
O menu de comparação será exibido
Escolha uma das opções digitando o número correspondente

📋 Menu de Atributos
O jogador poderá comparar as cartas utilizando um dos atributos abaixo:

Opção	Atributo	Regra de Vitória
1	População	Maior vence
2	Área (km²)	Maior vence
3	PIB	Maior vence
4	Pontos turísticos	Maior vence
5	Densidade demográfica (hab/km²)	Menor vence ✅

📌 Exemplo de Uso do Menu

===== MENU DE COMPARACAO =====
Escolha o atributo que deseja comparar:
1 - Populacao
2 - Area
3 - PIB
4 - Pontos Turisticos
5 - Densidade Demografica
Opcao: 1

Exemplo de saída após escolha:
Comparando Brasil e Argentina...

Atributo: Populacao
Brasil: 210000000 habitantes
Argentina: 45000000 habitantes
Resultado: Brasil venceu!

🧑‍💻 Estrutura Pedagógica
Este exercício faz parte da evolução lógica do Super Trunfo:
Nível	- Funcionalidades
Básico	Cadastro e exibição das cartas
Intermediário	Cálculo de densidade populacional e PIB per capita
Atual	Menu interativo com switch + comparações com if/else

✨ Autor(a)
Projeto acadêmico desenvolvido por Caroline Paim Muller para prática em programação estruturada em C do curso de Gestão da Tecnologia da Informação
