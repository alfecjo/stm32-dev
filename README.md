# 🔧 Projetos com STM32 e Sistemas Embarcados

🔗 [![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow?style=for-the-badge)]()

🔗 [![Tecnologia](https://img.shields.io/badge/Plataforma-STM32-blue?style=for-the-badge)](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html)

🔗 [![Linguagem](https://img.shields.io/badge/Linguagem-C%2FC++-informational?style=for-the-badge)]()

🔗 [![Licença](https://img.shields.io/badge/Licença-MIT-green?style=for-the-badge)](LICENSE)

## 📌 Descrição

Este repositório reúne projetos e experimentos práticos com microcontroladores **STM32**, com ênfase em automação, controle de sensores e atuadores, comunicação serial, redes industriais, e aplicações IoT. Os projetos utilizam placas como a **STM32F767ZI** (NUCLEO), com desenvolvimento em C/C++ usando ambientes como STM32CubeIDE, FreeRTOS e bibliotecas HAL/LL.

> ⚠️ **Este projeto está em desenvolvimento.** Alguns códigos e testes ainda estão sendo aprimorados ou reorganizados.

---

## 🚀 Tecnologias Utilizadas

- ⚙️ **STM32F767ZI (NUCLEO)**
- 🖥️ **STM32CubeIDE**
- 📡 **FreeRTOS**
- 🔌 **UART / SPI / I2C / CAN**
- 🌐 **Ethernet (LwIP) / MQTT**
- 📲 **Aplicações IoT**
- 📚 **HAL / LL Drivers**

---

## 📁 Estrutura do Projeto

```bash
stm32-dev/
├── drivers/
│   ├── sensor-dht22/
│   └── modbus-rtu/
├── examples/
│   ├── blink-led/
│   ├── uart-com/
│   └── ethernet-mqtt/
├── freertos/
│   └── task-manager/
├── utils/
│   └── delay.c
├── LICENSE
└── README.md
```

---

### 🔌 Aplicações Desenvolvidas
- ✅ Temporizador (bare-metal)
- ✅ Comunicação UART com PC + Java-Spring
- ✅ Leitura de sensores analógicos e digitais
- ✅ Controle de atuadores via PWM
- ✅ Comunicação via MQTT com broker público
- 🔄 RTOS multitarefa com controle de estado
- 🌐 Servidor HTTP embarcado com LwIP
- ⏳ Integração com displays LCD/OLED
- 🔧 Configuração de timers, ADC e DMA

### 🛠️ Instalação e Uso

```bash
# Clone o repositório
git clone https://github.com/SEU_USUARIO/stm32-dev.git
cd stm32-dev

# Importe os projetos no STM32CubeIDE
# Compile e faça o upload na sua placa STM32

```
---

### ✅ Requisitos
- Placa STM32 (ex: STM32F767ZI)
- STM32CubeIDE instalado
- Drivers ST-Link instalados
- (Opcional) Broker MQTT local ou online]
- Cabo USB tipo mini/micro

---

### 📦 Em Desenvolvimento
- Integração com sensores via Modbus RTU
- Comunicação com ESP32/ESP8266 via UART
- Dashboards IoT com integração HTTP/MQTT
- Aplicações com FreeRTOS e timers cooperativos
- Aplicações de automação residencial

---

### 🤝 Contribuindo
Contribuições são muito bem-vindas! Se você quiser propor melhorias, sugerir novos testes ou enviar exemplos práticos com outras placas STM32, sinta-se à vontade para abrir uma issue ou um pull request.

---

### 📄 Licença
- Este projeto está licenciado sob a Licença MIT.

---

- ## Return to the main page
  [![Main Page](https://img.shields.io/badge/Main-Page?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alfecjo)
