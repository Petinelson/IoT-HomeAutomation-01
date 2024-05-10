# Projeto IoT com ESP32

Este repositório contém um projeto de sistema inteligente utilizando um microcontrolador ESP32, focado em exibir informações sobre diversos dispositivos como Ar-Condicionado, Iluminação, Portão e sistema de câmeras. Utilizando componentes como LED, pushbutton e tela OLED, o sistema permite que o usuário visualize o status dos dispositivos de forma interativa e visual.

![Imagem do Projeto](https://github.com/Petinelson/IoT-HomeAutomation-01/blob/main/imagem_do_projeto.jpg)

## Sobre o Projeto

O objetivo deste projeto é fornecer uma ferramenta educacional para alunos de cursos técnicos aprenderem sobre a aplicação de tecnologias IoT na prática. O sistema não controla os dispositivos diretamente, mas exibe informações na tela OLED, permitindo que o usuário observe o status operacional de cada dispositivo. Um LED complementa a interface, indicando visualmente se os dispositivos estão ativos ou não.

## Componentes

- **ESP32**: Microcontrolador utilizado para o processamento das informações.
- **LED**: Indica visualmente o status dos dispositivos.
- **Pushbutton**: Permite ao usuário interagir com o sistema para atualizar ou alterar o que está sendo exibido.
- **Tela OLED**: Mostra informações detalhadas sobre o status dos dispositivos.

## Pré-Requisitos

Para utilizar este projeto, você precisa ter o seguinte ambiente configurado:

- Python com suporte para Micropython
- Plataforma Wokwi para simulação do projeto

## Arquivos no Repositório

- `main.py`: Script principal contendo a lógica do sistema.
- `diagrama.json`: Diagrama elétrico do projeto, utilizado no simulador Wokwi.
- `ssd1306.py`: Biblioteca para controle da tela OLED via I2C.
- `imagem_do_projeto.jpg`: Imagem representativa do projeto.

## Como Usar

1. Faça o clone deste repositório.
2. Abra o simulador Wokwi e importe o arquivo `diagrama.json` para visualizar o esquema elétrico.
3. Carregue os scripts Python no simulador para executar o projeto.

## Conclusões

Este projeto oferece uma excelente oportunidade para estudantes de tecnologia entenderem melhor as aplicações práticas de IoT. Ele demonstra como integrar hardware e software para criar soluções inteligentes e interativas em um contexto educacional.

## Licença

Este projeto é livre, permitindo a utilização e modificação por parte dos alunos e interessados em tecnologia IoT.
