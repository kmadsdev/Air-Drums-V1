🥁 Bateria Virtual com OpenCV e Pygame

Este projeto permite tocar uma bateria virtual utilizando uma webcam.
A detecção é feita com OpenCV, rastreando objetos vermelhos (como pontas de baquetas marcadas com fita vermelha).
Quando o objeto encosta em uma das regiões definidas na tela, o programa toca o som correspondente (caixa, surdo, prato, etc.), usando Pygame.

🎯 Funcionalidades

Rastreamento em tempo real de objetos vermelhos via webcam.

Áudio responsivo ao toque nas áreas predefinidas (simulando partes de uma bateria).

Sons independentes para cada peça da bateria.

Visualização na tela com círculos representando os tambores e pratos.

🧠 Tecnologias utilizadas

Python 3.x

OpenCV

NumPy

Pygame

📂 Estrutura do projeto
bateria_virtual/
│
├── sons/
│   ├── caixa.wav
│   ├── ximbau.wav
│   ├── tom1.wav
│   ├── prato.wav
│   └── surdo.wav
│
├── main.py
└── README.md

⚙️ Instalação e execução

Clone o repositório:

git clone https://github.com/seu-usuario/bateria-virtual.git
cd bateria-virtual


Instale as dependências:

pip install opencv-python numpy pygame


Adicione os sons da bateria na pasta sons/ (ou utilize os exemplos citados acima).

Execute o programa:

python bateria_virtual.py

🎮 Como usar

Certifique-se de que sua webcam está ligada.

Coloque uma fita vermelha na ponta de uma baqueta ou caneta.

Mire na tela: você verá os círculos representando as partes da bateria.

Quando o objeto vermelho encostar em um círculo, o som correspondente será reproduzido.

Pressione ESC para encerrar o programa.

🥁 Mapeamento dos sons
Posição (x, y)	Som	Descrição
(781, 615)	caixa	Caixa central
(950, 475)	ximbau	Prato de condução
(780, 335)	tom1	Tom pequeno
(580, 335)	prato	Prato crash
(469, 535)	surdo	Surdo ou bumbo lateral
🚀 Possíveis melhorias

Implementar detecção de múltiplas cores (para rastrear as duas baquetas).

Adicionar animações nas áreas tocadas.

Ajustar sensibilidade e ruído da câmera.

🧑‍💻 Autor: Kauã Novaes

Feito com ❤️ usando OpenCV + Pygame
