
# 📟 STM32F401RE ADC Example – Read Voltage from PA0

## 🧾 Description

This project demonstrates how to configure the ADC on the STM32F401RE microcontroller to read analog voltage from pin **PA0 (ADC1_IN0)**. The ADC is set in **continuous conversion mode** with **12-bit resolution**.

---

## 🛠️ Hardware Requirements

- STM32F401RE board (e.g., Nucleo-F401RE)
- Potentiometer or analog voltage source
- USB Mini B cable for programming
- Optional: Serial monitor for UART output

---

## 🧰 Software Requirements

- STM32CubeIDE
- ST-LINK USB driver
- Git (for version control)

---

## ⚙️ Configuration Summary

| Parameter                | Value         |
|-------------------------|---------------|
| MCU                     | STM32F401RE   |
| ADC Channel             | ADC1_IN0      |
| Pin                     | PA0           |
| Resolution              | 12-bit        |
| Conversion Mode         | Continuous    |
| Vref                    | 3.3V (default)|

---

## 🚀 How to Use

1. Clone the repository:
```bash
   git clone https://github.com/your-username/stm32f401re-adc-pa0.git
