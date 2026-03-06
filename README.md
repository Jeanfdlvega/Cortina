Simulação de Malha com Física - Pygame
📌 Descrição

Este projeto é uma simulação interativa de uma malha (grid) com física simples usando a biblioteca Pygame em Python.
Os pontos da malha são conectados por linhas e se comportam como um tecido ou rede elástica.

O usuário pode interagir com o mouse, puxando pontos ou quebrando conexões entre eles.

⚙️ Tecnologias utilizadas

Python

Pygame

Math

▶️ Como executar

Instale o Python.

Instale a biblioteca Pygame:

pip install pygame

Execute o script:

python main.py
🎮 Controles
Ação	Descrição
Mouse esquerdo	Arrasta pontos da malha
Mouse direito	Quebra conexões da malha
ESC	Sai da aplicação
🧠 Como funciona

O programa cria uma grade de pontos conectados por linhas.

Cada ponto possui posição atual e posição anterior para simular movimento.

A física aplicada inclui:

Gravidade

Limite de velocidade

Distância entre pontos conectados

As conexões se comportam como molas, mantendo uma distância aproximada entre os pontos.

🎯 Objetivo do projeto

Demonstrar uma simulação simples de física baseada em pontos e restrições, semelhante a um tecido ou rede elástica, utilizando Python e Pygame.
