t # 💡 Projeto LDR Arduino

## Controle de LED por LDR com Arduino

Sistema desenvolvido com **Arduino Uno** para realizar a leitura da luminosidade do ambiente por meio de um sensor **LDR (Light Dependent Resistor)** e controlar um LED de acordo com os valores capturados.

O projeto demonstra, na prática, a utilização de **sensores, entradas analógicas e controle de saída** em uma aplicação simples de automação.

 

---
 
## 📝 Descrição do Projeto

O projeto utiliza um **Arduino** para monitorar a intensidade luminosa do ambiente através de um **sensor LDR**.

O LDR envia ao Arduino um sinal analógico relacionado à quantidade de luz detectada. A partir dessa leitura, o sistema pode processar o valor recebido e controlar o **LED**, ajustando sua saída conforme a variação da iluminação.

A proposta é apresentar de forma prática como um sensor pode ser utilizado para automatizar uma saída do Arduino.
 
## 🛠️ Materiais e Componentes

| Componente              | Quantidade | Observação                   |
| ----------------------- | ---------: | ---------------------------- |
| **Arduino Uno**         |      1 un. | Ou modelo equivalente        |
| **Sensor LDR (5mm)**    |      1 un. | Leitura de luminosidade      |
| **LED (5mm)**           |      1 un. | Cor à escolha                |
| **Resistor 220 Ω**      |      1 un. | Limitação de corrente do LED |
| **Protoboard**          |      1 un. | Montagem do circuito         |
| **Jumpers Macho-Macho** |     Vários | Conexão entre os componentes |

---
 ## 📸 Circuito em Funcionamento

 
  <img src="https://github.com/robertodaniel01/arduino./blob/48391d088a902ead67e894156a031fea49f53c59/IMG_4157.jpg" alt="Circuito LDR com Arduino" width="200">

## 💻 Código — Entrada do Sensor LDR

O código abaixo representa a configuração inicial do sensor. O **LDR está conectado ao pino analógico A0**, que é configurado como entrada (`INPUT`).

```cpp
int LDR = A0;  // Entrada do sensor LDR

void setup() {
  pinMode(LDR, INPUT);  // Define o pino A0 como entrada
}
```
 
 # ⚙️ Como o Sistema Funciona

O funcionamento básico do projeto segue três etapas:

1. **Leitura:** o LDR detecta a intensidade da luz no ambiente.
2. **Processamento:** o Arduino recebe e processa o valor enviado pelo sensor.
3. **Saída:** o sistema utiliza o valor obtido para controlar o LED.

Dessa forma, o circuito demonstra uma aplicação básica de **automação utilizando Arduino e sensor de luminosidade**.

---

## 🎯 Objetivo

Demonstrar o funcionamento de um **sensor LDR conectado ao Arduino**, apresentando a relação entre uma entrada analógica e o controle de uma saída.

O projeto também serve como base para aplicações mais avançadas de **automação e controle de iluminação**.

---

## 🚀 Tecnologias Utilizadas

* Arduino Uno
* Sensor LDR
* LED
* Resistor 220 Ω
* Protoboard
* Jumpers
* Linguagem C/C++ para Arduino

---

## 👨‍💻 Projeto

**Projeto_LDR_Arduino**

Desenvolvido para demonstrar, de forma prática, o uso de sensores e automação com Arduino.
