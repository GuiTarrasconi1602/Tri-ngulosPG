# TriangulosPG
Atividade Vivencial 1 – Processamento Grafico - Criando Triangulos a partir do Clique do Mouse

Descrição da Tarefa
O objetivo do exercício é revisar o conteúdo sobre criação de buffers de geometria e envio de informações para o
programa de shader. Para isso, você vai fazer uma versão modificada do Exercício 3 da resposta ao desafio, que
atende os seguintes requisitos:
1) Ao clicar na tela, você agora estará criando apenas 1 vértice
2) A cada 3 vértices criados, você criará um triângulo
3) Para cada novo triângulo criado, você deve usar uma cor nova.

Dicas:
− Você pode criar um VAO único ou diversos VAOs
− Você pode alterar a estrutura Triângulo do Exercício 3, para armazenar não mais a posição, e sim a
geometria (vértices) do triângulo
− Para facilitar o mapeamento, utilize projeção paralela ortográfica e defina a janela do mundo com as
mesmas dimensões da tela (por ex. 800 x 600 unidades). Assim cada unidade do mundo corresponderá a
um pixel na tela.
− Utilize o GLFW Input Guide para tratar eventos do clique do mouse.
-----------------------------------------------------------------------------------------------------------------
Exercício mencionado:

A partir deste exercício, sugere-se utilizar a biblioteca GLM para cálculos matemáticos.

Exercício 3
Crie uma estrutura (struct ou classe) chamada Triangle que armazene:

 A posição do triângulo (x, y);
 A cor do triângulo (componentes RGB).
Utilizando a função criada anteriormente, gere um único VAO para um triângulo padrão com os seguintes vértices:  v0(-0.1, -0.1),   v1(0.1, -0.1),  v2(0.0, 0.1)

Usando um array, vector ou list de estruturas Triangle e o VAO criado, o programa deverá criar novos triângulos posicionados a partir do clique do mouse na tela. A cor de cada triângulo deve variar, sorteando-se valores para as componentes RGB da cor.
