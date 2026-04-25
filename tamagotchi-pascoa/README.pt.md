🇺🇸 [English](README.md) | 🇧🇷 Português

# Projeto Interativo Surpresa — Connect Byte 

Uma experiência de eletrônica criativa onde as participantes constroem um pequeno artefato interativo, combinando criatividade, imaginação e hardware de forma leve e divertida.

Este projeto foi desenvolvido para um workshop da Connect Byte e apresenta conceitos fundamentais de eletrônica através de uma abordagem prática e criativa. 

---

## Visão Geral 

Neste workshop, as participantes irão criar um objeto interativo personalizado utilizando materiais simples e componentes eletrônicos. 

A experiência acontece em dois momentos: 
- um momento criativo, focado em personalização e expressão visual       
- um momento técnico, onde a interação é adicionada com luz e/ou som   

O resultado final é algo que reage ao usuário — transformando uma criação estática em algo vivo e surpreendente.

### Objetivos de Aprendizado 
Este projeto introduz: 
- eletrônica básica (Tensão, Corrente e GND) 
- como LEDs funcionam e por que resistores são importantes 
- montagem de circuitos simples com bateria e botão 
- uso de sensores para captar estímulos do ambiente 
- criação de interações com Arduino 
- integração entre arte e tecnologia 

---

## Circuito 

### Nível 1 — Básico 
Um circuito interativo simples utilizando: 
- LED 
- bateria moeda (CR2032) 
- botão (push-button) 
- resistor 
- fios 

Lógica básica: 
- Bateria (+) → Botão → Resistor → LED (+) 
- Bateria (–) → LED (–) 

Comportamento: 
- pressionar → ativa 
- soltar → desativa 

### Nível 2 — Intermediário 
Um sistema interativo com Arduino: 
- Arduino (Nano ou Uno) 
- sensor de som (KY-038) 
- buzzer 
- LED 
- resistores 
- fios 
- alimentação via USB 

Comportamento: 
- detecta estímulos do ambiente (ex: som) 
- processa com o Arduino 
- ativa saídas (luz + som) 

---

## Código 

O código de exemplo está disponível na pasta `code`. 

Compatível com: 
- Arduino IDE 
- PlatformIO (VS Code) 

Arquivo principal: 
`code/src/main.cpp`

O código aborda: 
- leitura de sensores 
- controle de saídas (LED + buzzer) 
- lógica simples de interação 

### Experiência do Workshop 
Este projeto foi pensado para ser: 
- acessível para iniciantes 
- criativo primeiro, técnico depois 
- exploratório e divertido 

Não é necessário ter experiência prévia com eletrônica. 

---

## Connect Byte 
Website: https://connect-byte.org  
LinkedIn: https://www.linkedin.com/company/connect-byte/  
Instagram: [@connectbyte_](https://www.instagram.com/connectbyte_)
