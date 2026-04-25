# 🥩 POC +CARNE: Inteligência Nutricional Bovina

Ferramenta desktop de alta performance desenvolvida para automação da análise nutricional de pastagens e sugestão inteligente de suplementação.

## 🎯 Objetivo
Identificar carências nutricionais na dieta base (pasto) e sugerir o suplemento ideal (Linha Bovicort) para atingir metas de Ganho Médio Diário (GMD) pré-definidas.

## 🛠️ Stack Tecnológica
- **Framework:** Electron.js
- **Frontend:** React + Vite + Tailwind CSS
- **Persistência:** Local (Arquivos JSON/CSV + electron-store) - *Zero SQL/Cloud DB nesta fase.*
- **Fonte de Dados:** [Planilha Banco de Alimentos - +Carne](https://docs.google.com/spreadsheets/d/1X_mP6-yHlU-XgS-Fh78A1D3A5p4N1Y0Z-Q-V4L9_K6M)

## 🧮 Lógica do Motor de Cálculo
1. **Entradas:** Peso Inicial, GMD Desejado, Período do Ciclo, Tipo de Pasto e Consumo (% PV).
2. **Cálculo de Meta:** Peso Final = Peso Inicial + (GMD × Dias).
3. **Análise de Gap:** Confronto entre o aporte do pasto selecionado vs. exigência nutricional da meta.
4. **Output:** Sugestão do melhor suplemento e dosagem diária recomendada.

## 📅 Roadmap e Prazos (Sprints)
- **Fase 1 (Nivelamento):** Capacitação técnica em Electron (Máx. 21 dias).
- **Fase 2 (Desenvolvimento):** Estruturação de arquivos e motor de cálculo.
- **Fase 3 (Design/UI):** Desenvolvimento concomitante no Figma e integração.

---
*Este repositório é de uso exclusivo da Hut 8 Jr. e parceiros autorizados.*