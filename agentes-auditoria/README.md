# Agentes Especialistas para Auditoria de Bases Operacionais

Este diretório transforma a arquitetura estratégica em agentes operacionais prontos para uso em auditorias de bases operacionais.

## Composição do time

| Ordem | Agente | Função principal |
|---|---|---|
| 00 | Chief Audit Agent | Liderar planejamento, estratégia, consolidação e priorização executiva. |
| 01 | SSMA & Compliance Regulatório | Avaliar requisitos legais, segurança operacional, meio ambiente e licenças. |
| 02 | Qualidade & Integridade Laboratorial | Validar qualidade do produto, rastreabilidade, calibração e integridade laboratorial. |
| 03 | Integridade Volumétrica & Operação | Testar recebimento, expedição, tanques, perdas, sobras e reconciliações. |
| 04 | Financeiro, Faturamento & SAP | Revisar faturamento, pagamentos, fechamento, conciliações e segregação de funções. |
| 05 | Manutenção & Integridade Física | Avaliar manutenção preventiva, integridade de equipamentos e riscos físicos críticos. |
| 06 | Antifraude Operacional | Identificar vulnerabilidades, conluio, bypass de controles e manipulações. |
| 07 | Analytics & Evidências | Executar cruzamentos massivos, outliers, tendências, KPIs e painéis. |
| 08 | Gestão de Plano & Follow-up | Controlar planos de ação, prazos, evidências de fechamento e reincidências. |
| 09 | QA / Revisor Técnico | Revisar coerência, evidência, metodologia, causa, efeito e recomendação. |
| 10 | Relatórios Executivos | Produzir resumo executivo, relatório final, dashboard e materiais de comitê. |

## Fluxo recomendado

1. **Planejamento:** Chief Audit Agent define escopo, riscos, materialidade, matriz 5x5 e programa de auditoria.
2. **Execução técnica:** agentes especialistas executam testes por domínio e registram evidências.
3. **Analytics:** Analytics & Evidências cruza bases, identifica exceções e alimenta os especialistas.
4. **Validação:** QA / Revisor Técnico valida suficiência, coerência e aderência ao modelo DARC.
5. **Comunicação:** Relatórios Executivos consolida linguagem para diretoria, comitê e workgroups.
6. **Follow-up:** Gestão de Plano & Follow-up monitora ações, SLAs, evidências de encerramento e reincidências.

## Padrão DARC para achados

Todo agente deve produzir achados usando o padrão:

- **D — Descrição:** fato observado, local, período, processo e evidência objetiva.
- **A — Análise:** critério violado, teste executado, causa provável e extensão do problema.
- **R — Risco:** impacto operacional, financeiro, regulatório, ambiental, reputacional ou antifraude.
- **C — Correção/Controle:** recomendação, plano de ação sugerido, responsável, prazo e controle preventivo/detectivo.

## Classificação mínima de criticidade

| Nível | Critério orientativo |
|---|---|
| 5 - Crítico | Risco de acidente grave, interdição, fraude material, perda financeira relevante ou sanção regulatória severa. |
| 4 - Alto | Falha sistêmica de controle, exposição financeira/regulatória relevante ou reincidência não tratada. |
| 3 - Médio | Fragilidade relevante, mas localizada, com controles compensatórios parciais. |
| 2 - Baixo | Desvio pontual com baixo impacto e correção simples. |
| 1 - Informativo | Oportunidade de melhoria sem não conformidade material. |

## Evidências mínimas esperadas

- Documento ou registro-fonte.
- Extração sistêmica, quando aplicável.
- Evidência física/fotográfica, quando aplicável.
- Entrevista ou confirmação com responsável do processo, quando necessário.
- Trilha analítica do teste executado.
