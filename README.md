# 🔍 Do Alerta à Resposta: Investigação de Achados do Amazon GuardDuty

Este repositório contém o prompt desenvolvido para o **Desafio Criativo da DIO**, focado em segurança na nuvem e resposta a incidentes na AWS.

## 🎯 Objetivo
Transformar um alerta bruto do **Amazon GuardDuty** (`Policy:IAMUser/RootCredentialUsage`) em uma investigação estruturada, guiando uma IA a:
- Traduzir o achado para uma linguagem clara voltada à tomada de decisão.
- Levantar hipóteses ordenadas por probabilidade, sem inventar dados ausentes.
- Indicar exatamente onde buscar evidências (como logs do **AWS CloudTrail**).
- Separar ações de contenção reversíveis de irreversíveis.

## 📄 Arquivos
- `prompt-guardduty.md`: Prompt final completo com contexto do ambiente, formato de saída e guardrails contra alucinações.
