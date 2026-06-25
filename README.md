# Robotica-STELAS
# PORTFÓLIO – PROJETO FINAL DE ROBÓTICA COM C

## Sistema de Iluminação Automática com Sensor de Presença

### Identificação do Projeto

**Módulo:** Módulo 12 – Robótica com C

**Tema:** Automação residencial utilizando Arduino Uno e sensor de presença.

**Título do Projeto:** Sistema de Iluminação Automática com Sensor PIR

---

##  Introdução

A automação residencial tem se tornado cada vez mais presente no cotidiano das pessoas, proporcionando maior conforto, praticidade e economia de energia. Neste projeto foi desenvolvido um sistema simples de iluminação automática utilizando um Arduino Uno e um sensor de presença PIR, capaz de detectar movimentos em um ambiente e acionar uma lâmpada ou LED automaticamente.

---

##  Objetivo

Desenvolver um sistema automatizado que ligue uma fonte de iluminação quando detectar a presença de pessoas em um ambiente e a desligue após um determinado período sem movimentação.

---

##  Fundamentação Teórica

A robótica é uma área da tecnologia que integra eletrônica, programação e mecânica para criar sistemas capazes de executar tarefas de forma automática.

O Arduino Uno é uma plataforma de prototipagem eletrônica amplamente utilizada em projetos educacionais devido à sua facilidade de programação e baixo custo.

O sensor PIR (Passive Infrared Sensor) detecta variações na radiação infravermelha emitida pelos corpos, identificando movimentos dentro de sua área de alcance.

---

##  Materiais Utilizados

* 1 Arduino Uno;
* 1 Sensor PIR HC-SR501;
* 1 LED;
* 1 Resistor de 220 Ω;
* Jumpers;
* Protoboard.

---

##  Montagem do Circuito

### Conexões do Sensor PIR

* VCC → 5V do Arduino;
* GND → GND do Arduino;
* OUT → Pino digital 2.

### Conexões do LED

* Ânodo (perna maior) → Pino 13 através do resistor de 220 Ω;
* Cátodo → GND.

---

##  Funcionamento do Sistema

O funcionamento do sistema ocorre da seguinte forma:

1. O sensor PIR monitora continuamente o ambiente.
2. Quando um movimento é detectado, o sensor envia um sinal ao Arduino.
3. O Arduino interpreta o sinal recebido.
4. O LED é acionado, simulando o funcionamento de uma lâmpada.
5. Após alguns segundos sem novas detecções de movimento, o Arduino desliga o LED automaticamente.

---

##  Aplicações Práticas

Esse sistema pode ser utilizado em diversos ambientes, tais como:

* Corredores;
* Garagens;
* Banheiros;
* Áreas externas;
* Depósitos;
* Ambientes corporativos.

Além de proporcionar comodidade, o sistema contribui para a redução do desperdício de energia elétrica.

---

##  Resultados Esperados

Espera-se que o sistema seja capaz de detectar a presença de pessoas com eficiência, acionando a iluminação apenas quando necessário. Dessa forma, o projeto demonstra uma aplicação prática da robótica e da automação no contexto doméstico.

---

##  Conclusão

O desenvolvimento deste projeto permitiu compreender a integração entre sensores, programação e eletrônica por meio do Arduino Uno. O sistema de iluminação automática representa uma solução simples e eficiente para automação residencial, evidenciando como a robótica pode ser aplicada para melhorar o conforto e promover o uso consciente da energia elétrica.

---

##  Referências

ARDUINO. Arduino Uno Rev3. Disponível em: https://www.arduino.cc

ARDUINO. Documentação Oficial. Disponível em: https://docs.arduino.cc

HC-SR501 PIR Motion Sensor – Datasheet Técnico.
