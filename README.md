# Gesture Vote (Hand Like/Dislike Detection)

Um projetinho de treino para **detecção de gestos com as mãos** usando [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) e a câmera do navegador.  
A ideia é **votar nas imagens** exibidas na tela usando os gestos de 👍 **like** (polegar para cima) e 👎 **dislike** (polegar para baixo).

## 🚀 Tecnologias utilizadas
- **HTML5 / CSS3 / JavaScript**
- **MediaPipe Hands** (detecção de pontos da mão)
- **MediaPipe Camera Utils** (acesso à câmera)

## 🎮 Como funciona
1. O usuário habilita a câmera do navegador.  
2. A cada imagem exibida, o usuário mostra com a mão:
   - 👍 **Like** → polegar para cima  
   - 👎 **Dislike** → polegar para baixo  
3. O sistema detecta o gesto e registra a votação.  
4. No final, é exibido o total de likes e dislikes.

## 📂 Estrutura do projeto
projeto/
│
├── hand-like-dislike-detection.html # Página com o código
├── imagens/ # Pasta com as imagens para votação
│ ├── 1.jpg
│ ├── 2.jpg
│ ├── 3.jpg
│ ├── 4.jpg
│ └── 5.jpg

## ▶️ Como executar
1. Clone este repositório:
Abra o arquivo hand-like-dislike-detection.html no navegador.
Permita o acesso à câmera.
Faça os gestos de 👍 ou 👎 para votar nas imagens.

Observei uma certa dificuldade e demora na detecção dos gestos, mas funciona. Tente abrir a mão ou retirar do campo de visão e formar o gesto em seguida.
