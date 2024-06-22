```markdown
# Ilusão Interativa Avançada em 3D do Triângulo de Reutersvärd

Este projeto demonstra uma ilusão interativa em 3D do Triângulo de Reutersvärd usando p5.js. Os usuários podem ajustar a rotação do triângulo e a posição da luz para explorar diferentes perspectivas e efeitos visuais.

## Variáveis Globais

- **rotationX**: Armazena o ângulo de rotação no eixo X.
- **rotationY**: Armazena o ângulo de rotação no eixo Y.
- **rotationZ**: Armazena o ângulo de rotação no eixo Z.
- **lightX**: Define a posição da luz no eixo X.
- **lightY**: Define a posição da luz no eixo Y.
- **lightZ**: Define a posição da luz no eixo Z.

## Estrutura do Projeto

- **index.html**: Arquivo HTML principal contendo a estrutura da página.
- **css/style.css**: Arquivo CSS para os estilos da página.
- **js/sketch.js**: Arquivo JavaScript com o código p5.js para renderizar a ilusão e controlar a interatividade.

## Como Usar

1. **Clone este repositório**:
    ```sh
    git clone https://github.com/tatyquebralayout/3D-of-the-Reutersv-rd-Triangle.git
    ```

2. **Abra o arquivo `index.html` em seu navegador**:
    - Navegue até o diretório do projeto clonado.
    - Abra o arquivo `index.html` diretamente no seu navegador preferido.

3. **Interaja com os controles**:
    - Ajuste os sliders para alterar a rotação do triângulo nos eixos X, Y e Z.
    - Modifique a posição da luz usando os sliders correspondentes.
    - Pressione o botão "Redefinir" para voltar às configurações iniciais.

## Tecnologias Utilizadas

- **p5.js**: Biblioteca JavaScript para renderização e interatividade.
- **HTML**: Estrutura da página web.
- **CSS**: Estilos da página web.
- **JavaScript**: Lógica de interatividade e renderização.

## Funções e Configurações

### Função setup

- **Canvas**: Cria um canvas 3D de 600x600 pixels e o anexa ao contêiner no HTML.
- **Modo de Ângulo**: Define o modo de ângulo para graus.
- **Loop de Desenho**: Desativa o loop contínuo de desenho.
- **Controles Interativos**:
    - **Angle Slider**: Configura um controle deslizante para ajustar o ângulo de rotação.
    - **Size Slider**: Configura um controle deslizante para ajustar o tamanho do triângulo.
    - **Color Picker**: Configura um seletor de cor para ajustar a cor das formas.
    - **Reset Button**: Configura um botão para redefinir os valores iniciais.

### Função draw

- **Fundo**: Limpa o fundo do canvas com branco.
- **Transformações**:
    - **Translação**: Move o ponto de origem para o centro do canvas.
    - **Rotação**: Rotaciona o canvas de acordo com o ângulo definido.
- **Desenho**:
    - **Cor e Contorno**: Define a cor de preenchimento e remove o contorno das formas.
    - **Triângulo de Reutersvärd**: Chama a função para desenhar o triângulo com o tamanho especificado.

### Função drawReutersvardTriangle3D

- **Cálculos Geométricos**:
    - Calcula a raiz quadrada de 3 e usa esse valor para determinar a largura e altura do triângulo.
- **Desenho**:
    - **Triângulo Principal**: Desenha o triângulo principal.
    - **Formas Complementares**: Desenha as formas complementares à esquerda e à direita.

## Autora

- **Tatiana Barros**: Desenvolvimento e implementação do projeto.

