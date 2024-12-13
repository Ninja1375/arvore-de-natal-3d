# Árvore de Natal 3D 🎄

Este é um projeto de visualização interativa em 3D que representa uma Árvore de Natal estilizada e decorada com elementos geométricos, iluminação dinâmica e efeitos visuais avançados. Criado com a biblioteca [Three.js](https://threejs.org/), o projeto oferece uma experiência imersiva, combinando animação, shaders e pós-processamento.

---

## 🎨 Características do Projeto

### 🌟 Funcionalidades principais:
- **Árvore de Natal estilizada**: Feita com geometria cônica e decorada com formas como esferas e icosaedros.
- **Texto animado**: Uma mensagem de "Feliz Natal" percorre uma curva 3D ao redor da árvore.
- **Iluminação avançada**: Inclui luzes coloridas, reflexões e efeitos de **Unreal Bloom** para realçar os elementos da cena.
- **Elementos dinâmicos**: Decorações piscantes, animações suaves de câmera e rotação automática da cena.
- **Shaders personalizados**: Uso de Vertex e Fragment Shaders para criar efeitos visuais únicos.
- **Responsividade**: A cena se ajusta automaticamente ao tamanho da janela do navegador.

---

## 🛠️ Tecnologias Utilizadas

O projeto faz uso de tecnologias modernas para renderização 3D:

- **[Three.js](https://threejs.org/)**: Biblioteca JavaScript para criação e renderização de gráficos 3D.
- **Shaders customizados**: Para controlar a aparência visual dos objetos na cena.
- **Efeitos de pós-processamento**:
  - **Unreal Bloom**: Realça áreas brilhantes para um efeito de brilho mágico.
  - **RenderPass e ShaderPass**: Para controle e manipulação da cena renderizada.
- **Controle de câmera**:
  - [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls): Permite rotacionar, aproximar e explorar a cena.

---

## 📂 Estrutura do Projeto

O projeto é organizado em três arquivos principais:

### `index.html`
Este arquivo contém:
- A estrutura básica da página.
- Links para os scripts necessários, incluindo a biblioteca Three.js e seus módulos adicionais.
- Definição dos shaders personalizados (Vertex e Fragment Shaders).

### `style.css`
Define o estilo da página:
- Define o **canvas** como elemento principal, ocupando 100% da tela.
- Remove seleções e margens para uma experiência de tela cheia.

### `script.js`
É onde a mágica acontece:
- Configura a cena, câmera e renderizador.
- Cria os elementos 3D como a árvore, as decorações e o texto animado.
- Aplica os efeitos de luz e shaders personalizados.
- Configura animações e ajustes responsivos para a janela.

---

## 🎥 Pré-visualização

### Captura de Tela:
(Adicione aqui uma imagem ou GIF mostrando o projeto em execução)

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/arvore-natal-3d.git
