# Protótipo RiskGuard 1.0

Dispositivo IoT + IA para prevenção de sinistros em equipamentos agrícolas, desenvolvido como parte do Challenge Sompo Seguros.

## Descrição

Protótipo de dispositivo IoT + IA para prevenção de sinistros em equipamentos agrícolas (tratores, caminhões, colheitadeiras), desenvolvido para o Challenge Sompo Seguros. Capta dados ambientais via ESP32+DHT22, armazena no Supabase e usa a API do Gemini para gerar recomendações de risco explicáveis para operadores e gestores de frota.

## Sobre o projeto

O RiskGuard tem como objetivo instalar sensores em frotas de equipamentos agrícolas para identificar fatores ambientais e operacionais que aumentam o risco de danos e sinistros, gerando alertas e recomendações preventivas por meio de inteligência artificial.

Este repositório contém o protótipo inicial (v1.0), desenvolvido durante a Sprint 3, com foco na validação do núcleo técnico da solução: captação de dado ambiental → armazenamento → processamento por IA → geração de recomendação.

## Status atual

🚧 Protótipo em desenvolvimento — núcleo técnico parcialmente validado, integração entre camadas ainda não automatizada. A comunicação entre a API do Gemini e o Supabase ainda depende de execução manual via terminal.

## Estrutura do repositório
