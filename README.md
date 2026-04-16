
# Monitoramento de Luminosidade com Arduino1
## 📌 Descrição
 
  Este projeto consiste em um sistema de monitoramento de luminosidade utilizando Arduino, desenvolvido com base no caso da Vinheria Agnello.  O objetivo é garantir que os vinhos sejam armazenados em condições adequadas, evitando exposição excessiva à luz, que pode prejudicar sua qualidade.

## ⚙️ Componentes Utilizados

- Arduino Uno
- Sensor LDR
- Resistor 10kΩ
- 3 LEDs (verde, amarelo e vermelho)
- 3 resistores 220Ω
- Buzzer
- Protoboard
- Jumpers

## 🔌 Funcionamento

O sistema utiliza um sensor LDR para medir a luminosidade do ambiente.

Com base nos valores lidos pelo Arduino, o sistema classifica o ambiente em três estados:

- LED Verde: ambiente com luminosidade ideal
- LED Amarelo: nível de alerta
- LED Vermelho: luminosidade inadequada

Quando a luminosidade está fora do ideal, o buzzer é acionado por 3 segundos para alertar o usuário.

## 📊 Lógica de Decisão

- Leitura menor que 50 → Problema (LED vermelho + buzzer)
- Leitura entre 50 e 500 → Alerta (LED amarelo)
- Leitura maior que 500 → Ideal (LED verde)

## ▶️ Como Executar

1. Monte o circuito no Tinkercad
2. Conecte o LDR na porta analógica A0
3. Conecte os LEDs nas portas digitais 8, 9 e 10
4. Conecte o buzzer na porta 11
5. Insira o código no Arduino
6. Inicie a simulação
7. Varie a luminosidade do LDR para testar o sistema

## ⚠️ Importância do Projeto

A luminosidade influencia diretamente na qualidade do vinho, podendo causar alterações químicas indesejadas.

Este sistema permite monitorar e controlar o ambiente, garantindo melhores condições de armazenamento.

## 🚀 Possíveis Melhorias

- Adicionar sensor de temperatura
- Adicionar sensor de umidade
- Criar um sistema de monitoramento remoto
- Enviar alertas para o celular
## Link do tinkercard
https://www.tinkercad.com/things/1Ksg3ozFYDG-frantic-migelo-uusam/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=Jnjb5Yc8HUxR1CMnXxee23Zj7kLpigfYEPy6Or1Uwyw

## 🎥 Simulação do arduíno em Vídeo

[![Assista ao vídeo](https://img.youtube.com/vi/S5ldT6d_qgc/maxresdefault.jpg)](https://www.youtube.com/watch?v=S5ldT6d_qgc)

## 🎥 Explicando o projeto em Vídeo

[![Assista ao vídeo](https://img.youtube.com/vi/75CyhTiD054/maxresdefault.jpg)](https://www.youtube.com/watch?v=75CyhTiD054)

## 👨‍💻 Autores

Projeto desenvolvido por: 
Henrique Fredi RM:570257
Henrique Vieira RM:569586 
Leonardo Barrocal RM:571031


  
