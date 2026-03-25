# 🛡️ Arcanjos - Sistema de Incêndio

Este repositório contém o projeto de sistemas embarcados desenvolvido para a empresa **Arcanjos**. O foco é uma solução inteligente e acessível para a detecção, prevenção e combate a incêndios, projetada e simulada integralmente na plataforma **Tinkercad**.

## 🚀 O Produto

O **Sistema de Incêndio Arcanjos** é um dispositivo de segurança baseado em microcontrolador, focado na proteção de ambientes e vidas. Através da integração de sensores e atuadores, o sistema garante:

1. **Detecção Precisa:** Leitura em tempo real de fumaça e variações térmicas.
2. **Prevenção Ativa:** Alertas visuais e sonoros graduais conforme o nível de risco.
3. **Combate Automático:** Simulação de acionamento de sistemas de contenção (extintores/sprinklers) via hardware.

## 👥 Equipe de Desenvolvimento

Projeto planejado e programado por:

* **Diego Ximenes**
* **Luiz Eduardo**

## 🛠️ Tecnologias e Componentes (Hardware)

* **Plataforma de Simulação:** [Autodesk Tinkercad](https://www.tinkercad.com/)
* **Microcontrolador:** Arduino Uno R3
* **Linguagem:** C++ (Arduino Framework)
* **Principais Componentes Simulados:**
    * **Sensor de Gás (Gas Sensor):** Para detecção de fumaça/GLP.
    * **Sensor de Temperatura (TMP36):** Monitoramento térmico ambiental.
    * **Buzzer (Piezo):** Alerta sonoro de emergência.
    * **LEDs (RGB ou Individual):** Sinalização de status (Verde: Seguro / Vermelho: Perigo).
    * **Display LCD (16x2):** Interface para exibição de mensagens de status.
    * **Micro Servo:** Simulação de abertura de válvulas de combate.

## 📋 Lógica do Sistema

O firmware foi desenvolvido para operar em diferentes níveis de segurança:
* **Monitoramento:** Leitura constante dos sensores e exibição no LCD.
* **Alerta:** Ao detectar níveis anormais, o sistema ativa sinais visuais e o buzzer.
* **Intervenção:** Em caso crítico, o sistema aciona automaticamente o mecanismo de combate (Servo) para mitigar o incêndio.

---

<p align="center">
  <b>Arcanjos</b>
</p>
