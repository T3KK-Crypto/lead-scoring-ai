# lead-scoring-ai
Workflow via make. API´s, Webhooks &amp; Modelos LLMs


# 🤖 Lead Scoring com IA — Automação Inteligente de Qualificação de Leads

## Sobre o Projeto
Pipeline de automação que captura leads via formulário, classifica automaticamente com IA e dispara emails personalizados conforme o perfil do lead.

## Fluxo da Automação
Tally (Formulário) → Make (Orquestração) → Gemini IA (Classificação) → Supabase (Banco de dados) → Gmail (Email personalizado) → Cal.com (Agendamento)

## Como Funciona
1. Lead preenche formulário no Tally
2. Make recebe os dados via Webhook
3. Gemini IA analisa e classifica o lead como QUENTE, MORNO ou FRIO
4. Dados são salvos no Supabase automaticamente
5. Lead QUENTE recebe email com link para agendar Sessão Estratégica no Cal.com
6. Lead MORNO/FRIO recebe email de acolhimento

## Critérios de Classificação
- **QUENTE** — Capital acima de R$3.000 e dor específica e urgente
- **MORNO** — Capital entre R$1.500 e R$3.000 ou respostas vagas com potencial
- **FRIO** — Capital abaixo de R$1.500 ou sem clareza de necessidade

## Tecnologias Utilizadas
- Make (automação e orquestração)
- Google Gemini 2.5 Flash (classificação com IA)
- Supabase (banco de dados PostgreSQL)
- Tally (formulário de captação)
- Gmail (disparo de emails)
- Cal.com (agendamento de sessões)

## Resultado
- Qualificação automática de leads sem intervenção humana
- Redução do tempo de resposta para segundos
- Segmentação inteligente para priorizar leads com maior potencial
