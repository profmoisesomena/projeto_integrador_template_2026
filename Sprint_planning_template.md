# Sprint Planning - Sprint 01

**Data:** 12/02/2026  
**Participantes:** Facilitador (Scrum Master),(Development Team)  
**Sprint Duration:** 1 semanas (5 dias úteis)  
**Sprint Goal:** Criar documentação fundamental que permita desenvolvimento do projeto
---

## 📊 Sprint Capacity

- **Velocity anterior:** N/A (primeira sprint)
- **Capacidade estimada:** 17,5h pontos
- **Dias úteis disponíveis:** 5 dias
- **Impedimentos conhecidos:** Nenhum conhecido no momento / Alinhar padrão visual antes de seguir / Dependência de validação externa

- Cálculo da velocidade estimada:
  -  Capacidade por horas → converte para pontos
    -   Horas disponíveis = (dias úteis) × (horas/dia) × (nº pessoas) × (fator de foco)
    -   Exemplo de dados de entrada:  
        - Dias úteis: 5
        - Horas/dia: depende do seu time (2,5 horas)
        -  Fator de foco: 0,7 (desconta reuniões, interrupções, revisão, retrabalho)
    -  Exemplo de cálculo: se a equipe trabalha 2,5h/dia equivalente por 10 dias):
        - Horas brutas = 5 × 2,5 × 2 = 25h (num exemplo de 2 pessoas no time)
        - Horas efetivas (foco 0,7) = 25 × 0,7 = 17,5h

---

## 🎯 Sprint Goal

> Estabelecer a base de documentação necessária para que desenvolvedores possam adotar e utilizar os templates Agile AI de forma efetiva, incluindo guia de início rápido, exemplos práticos de workflows, e template de bug report para completar o conjunto básico.

---

## 📋 User Stories Selecionadas

### [US-001] Criar documentação de quick start do projeto
- **Prioridade:** Alta
- **Story Points:** 5
- **Assignee:** Time de Desenvolvimento
- **Epic:** EPIC-001 - Documentação e Guias de Uso
- **Critérios de Aceitação:**
  - [ ] Guia cobre instalação e setup inicial para desenvolvimento (Softwares e ferramentas necessários)
  - [ ] Inclui primeiro exemplo de fluxo de telas principal (workflow)
  - [ ] Possui links para documentação detalhada e no Readme do projeto
  - [ ] Adição de todos usuários no repositório projeto e no kanban de acompanhamento
  - [ ] Formatação visualmente organizada e seções claras

**Notas técnicas:**
- Deve ser o ponto de entrada principal no README
- Incluir comandos copy-paste para agilizar

---

### [US-002] Documentar workflows com exemplos práticos
- **Prioridade:** Alta
- **Story Points:** 8
- **Assignee:** Time de desenvolvimento
- **Epic:** EPIC-001 - Documentação de cada workflow
- **Critérios de Aceitação:**
  - [ ] Screenshots das telas em sequencia apropriada
  - [ ] Use de arquivos do tipo .md para criar e explicar o fluxo adicionando as imagens
  - [ ] Links para templates, figma e documentos relacionados ao fluxo específico
  - [ ] Exemplos mostram possíveis problemas no fluxo esperado (falta de validação dos dados, usuário escolha o fluxo de páginas acessadas, etc)

**Notas técnicas:**
- Criar um documento separado para cada workflow principal
- Usar formato consistente em todos os exemplos
- Considerar criar vídeo screen recording para workflow mais complexo

**Dependências:**
- Necessita que templates estejam estáveis (já concluído)

---

### [US-007] Revisar e atualizar backlog do projeto para desenvolvimento
- **Prioridade:** Alta 
- **Story Points:** 3
- **Assignee:** Time de desenvolvimento
- **Epic:** EPIC-002 - Templates Avançados
- **Critérios de Aceitação:**
  - [ ] Reavaliar documentação de backlog
  - [ ] Incluir no Kanban do GitHub no campo de backlog as atividades necessarias para o sprint atual
  - [ ] Campo para História de usuário, prioridade/Moscow
  - [ ] Checklist para verificar disponibilidade de softwares/ferramentas para o desenvolvimento
  - [ ] Atribuir cada tarefa a um membro da equipe (obrigatório)

**Notas técnicas:**
- Manter simples e direto

---

**Total Comprometido: 16 pontos** (dentro da capacidade estimada)

---

## ✅ Definition of Done

- [ ] Código revisado (peer review ou auto-review com IA)
- [ ] Documentação atualizada (README, índices)
- [ ] Exemplos funcionais criados e testados
- [ ] Markdown formatado corretamente (sem erros)
- [ ] Links internos verificados (não quebrados)
- [ ] Testado por pelo menos 1 pessoa da equipe seguindo as instruções
- [ ] Commitado no repositório com mensagem descritiva
- [ ] Validação do Professor

---

## 🎲 Riscos e Dependências

| Risco/Dependência | Impacto | Mitigação | Responsável |
|-------------------|---------|-----------|-------------|
| Documentação muito extensa pode exigir muito tempo | Médio | Separar em detalhamento (curto) e guia detalhado (completo somente se necesário) |Time de desenvolvimento |

**Dependências entre stories:**
- US-001 deve referenciar US-002 (documentação detalhada)
- Todas as stories devem atualizar README principal de forma a verificarmos o andamento do projeto

---

## 📝 Notas e Decisões

### Decisões Tomadas
- **Formato da documentação:** Markdown puro para máxima compatibilidade
- **Estrutura:** Quick start separado de documentação detalhada
- **Exemplos:** Focar em casos de uso reais (autenticação, CRUD, etc.)
- **US-007 justificativa:** Incluído para completar conjunto básico de templates, permitindo feedback completo

### Action Items
- [ ] Identificar usuário voluntário para testar documentação (até 14/02)
- [ ] Revisar templates existentes para garantir consistência (até 15/02)
- [ ] Definir padrão de formatação para exemplos (até 13/02)

### Discussões Importantes
- **Sobre vídeos tutoriais (US-003):** Decidimos não incluir na Sprint 01 pois documentação escrita é prioridade. Vídeo pode ser criado em sprint futura baseado na documentação.
- **Sobre idioma:** Manter tudo em português brasileiro por enquanto. Internacionalização pode ser considerada no futuro.

---

## 🤖 Assistência IA (opcional)

- [x] Refinamento de user stories (critérios de aceitação validados com IA)
- [x] Estimativa de complexidade (validada com IA)
- [x] Identificação de riscos técnicos (análise de dependências)
- [x] Sugestões de arquitetura (estrutura de documentação)
- [ ] Outros: -

