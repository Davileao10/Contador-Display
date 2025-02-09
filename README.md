<<<<<<< HEAD
# contador-numeros-display-bitdoglab
=======
# Projeto: Interface de Comunicação Serial no RP2040 com BitDogLab

## Descrição
Este projeto tem como objetivo explorar as interfaces de comunicação serial no microcontrolador RP2040 utilizando a placa de desenvolvimento BitDogLab. Ele combina hardware e software para manipulação de LEDs, entrada de caracteres via UART e interação com botões.

## Objetivos
- Compreender o funcionamento da comunicação serial (UART e I2C) em microcontroladores.
- Manipular LEDs comuns e LEDs endereçáveis WS2812.
- Implementar o uso de botões com interrupção e debounce.
- Exibir caracteres em um display SSD1306.

## Componentes Utilizados
- **Matriz 5x5 de LEDs WS2812** (GPIO 7)
- **LED RGB** (GPIOs 11, 12 e 13)
- **Botão A** (GPIO 5)
- **Botão B** (GPIO 6)
- **Display SSD1306 via I2C** (GPIOs 14 e 15)

## Funcionalidades Implementadas
### 1. Modificação da Biblioteca `font.h`
- Adição de caracteres minúsculos personalizados.

### 2. Entrada de Caracteres via Serial (UART)
- Digitação de caracteres pelo Serial Monitor do VS Code.
- Exibição de caracteres no display SSD1306.
- Exibição de símbolos correspondentes a números (0 a 9) na matriz de LEDs 5x5 WS2812.

### 3. Interação com o Botão A
- Alterna o estado do **LED RGB Verde** (ligado/desligado).
- Exibe uma mensagem sobre a operação no display SSD1306.
- Envia uma mensagem informativa ao Serial Monitor.

### 4. Interação com o Botão B
- Alterna o estado do **LED RGB Azul** (ligado/desligado).
- Exibe uma mensagem sobre a operação no display SSD1306.
- Envia uma mensagem informativa ao Serial Monitor.

## Requisitos do Projeto
- **Uso de Interrupções (IRQ)** para interação com os botões.
- **Implementação de Debounce** via software.
- **Controle de LEDs** WS2812 e comuns.
- **Utilização do Display SSD1306** para exibição de caracteres maiúsculos e minúsculos.
- **Envio de dados pela UART** para comunicação com o PC.
- **Código bem estruturado e comentado**.

## Entrega
### 1. Código-Fonte
O código do projeto está disponível neste repositório, contendo todos os arquivos necessários para sua execução.

### 2. Vídeo de Demonstração
Um vídeo demonstrativo foi produzido, contendo:
- Apresentação do autor.
- Explicação das funcionalidades implementadas.
- Demonstração do projeto em funcionamento.
- [Link para o vídeo](INSERIR_LINK_AQUI)

## Considerações Finais
Este projeto proporciona uma excelente oportunidade para consolidar conhecimentos em programação de microcontroladores, manipulação de hardware e desenvolvimento de interfaces de comunicação. O código foi estruturado para facilitar a compreensão e manutenção.

**Boa sorte e bom desenvolvimento!**

>>>>>>> 0a206ef0f20db0775705085a36450724c40405c6
