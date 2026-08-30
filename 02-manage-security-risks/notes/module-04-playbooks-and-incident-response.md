# Módulo 4 — Playbooks e Incident Response

## 1. Playbook

Um **Playbook** é um manual que fornece detalhes sobre ações operacionais que devem ser realizadas em determinadas situações.

Na cybersecurity, os playbooks ajudam as equipes de segurança a seguirem procedimentos definidos durante a identificação e resposta a possíveis incidentes.

---

## 2. Incident Response

**Incident Response (Resposta a Incidentes)** é a tentativa rápida de uma organização de:

- Identificar um ataque;
- Conter os danos;
- Corrigir os efeitos de uma violação de segurança.

O objetivo é permitir que a organização responda de maneira estruturada aos incidentes e reduza seus possíveis impactos.

---

# 3. Fases do Incident Response Playbook

## Preparação

Antes que incidentes ocorram, a organização busca reduzir seus possíveis impactos.

Isso envolve atividades como:

- Documentar procedimentos;
- Estabelecer planos de pessoal;
- Educar usuários;
- Preparar a organização para possíveis incidentes.

---

## Detecção e Análise

Consiste em detectar e analisar eventos utilizando:

- Processos previamente definidos;
- Tecnologias apropriadas.

Nessa etapa, a equipe busca compreender os eventos identificados e determinar como eles devem ser tratados.

---

## Contenção

A **Contenção** busca impedir que o incidente cause danos adicionais e reduzir seu impacto imediato.

---

## Erradicação e Recuperação

Consiste em remover completamente os artefatos relacionados ao incidente para permitir que a organização retorne às operações normais.

---

## Atividade Pós-Incidente

Depois que o incidente é tratado, é importante:

- Documentar o ocorrido;
- Informar a liderança da organização;
- Identificar e aplicar as lições aprendidas.

As informações obtidas podem ajudar a organização a melhorar sua resposta a incidentes futuros.

---

## Coordenação

A **Coordenação** envolve reportar incidentes e compartilhar informações durante todo o processo de resposta, seguindo os padrões estabelecidos pela organização.

---

# 4. SIEM e Playbooks

Ferramentas **SIEM (Security Information and Event Management)** e playbooks trabalham em conjunto para auxiliar na resposta a possíveis incidentes de segurança.

De forma simplificada:

SIEM detecta atividade
        ↓
Alerta é gerado
        ↓
Analista avalia o alerta
        ↓
Playbook orienta as ações
        ↓
Resposta ao incidente

O SIEM fornece informações e alertas que ajudam a identificar possíveis incidentes, enquanto o playbook fornece procedimentos para orientar a resposta da equipe.

---

# 5. Avaliação de um SIEM Alert

Durante o módulo, foi realizada uma atividade envolvendo a resposta a um alerta gerado por um SIEM.

Em um dos cenários, o SIEM identificou o download de um arquivo suspeito.

Antes de iniciar imediatamente uma ação de contenção, o alerta deve ser avaliado e mais informações devem ser coletadas.

Um fluxo simplificado é:

SIEM Alert
    ↓
Assess the Alert
    ↓
Gather Information
    ↓
Determine Appropriate Response
    ↓
Follow the Playbook

Essa análise ajuda a equipe a compreender melhor o evento antes de determinar a resposta apropriada.

---

# 6. Estratégia e Plano dos Playbooks

Os playbooks são acompanhados por uma **Estratégia**.

A estratégia descreve as expectativas dos membros da equipe responsáveis por determinada tarefa.

Alguns playbooks também identificam os indivíduos responsáveis pelas ações.

As expectativas são acompanhadas por um **Plano**, que determina como a tarefa específica descrita no playbook deve ser concluída.

De forma simplificada:

Playbook
   ↓
Estratégia
   ↓
Expectativas e responsáveis
   ↓
Plano
   ↓
Execução da tarefa

---

# 7. Playbooks como Living Documents

Os playbooks devem ser tratados como **Living Documents (documentos vivos)**.

Isso significa que precisam ser atualizados conforme as necessidades da organização e as mudanças no cenário de cybersecurity.

Atualizações podem ser necessárias quando:

### Uma falha é identificada

Por exemplo, quando existe uma deficiência nas políticas, procedimentos ou no próprio playbook.

### Padrões do setor mudam

Mudanças em:

- Leis;
- Regulamentações;
- Requisitos de compliance.

podem exigir alterações nos procedimentos existentes.

### O cenário de cybersecurity muda

As táticas e técnicas utilizadas por threat actors continuam evoluindo.

Consequentemente, os procedimentos utilizados pelas organizações também precisam acompanhar essas mudanças.

---

# 8. Diferenças entre Organizações

Cada organização pode possuir diferentes:

- Ferramentas;
- Metodologias;
- Protocolos;
- Procedimentos;
- Playbooks.

Os indivíduos envolvidos em cada etapa do processo de resposta também podem variar.

Essas diferenças podem depender da própria organização e do país em que ela opera.

---

# 9. SOAR e Playbooks

Os playbooks também podem ser utilizados juntamente com ferramentas **SOAR — Security Orchestration, Automation and Response**.

SOAR pode ser utilizado para automatizar tarefas repetitivas geradas por ferramentas como:

- SIEM;
- Managed Detection and Response (MDR).

Isso permite automatizar determinadas ações relacionadas à resposta a eventos de segurança.

### Exemplo

Caso um usuário tente realizar login várias vezes utilizando uma senha incorreta, uma ferramenta SOAR poderia executar automaticamente uma ação definida para impedir uma possível intrusão.

De forma simplificada:

SIEM / MDR
     ↓
Evento ou alerta
     ↓
SOAR
     ↓
Workflow automatizado
     ↓
Ação de resposta

---

# 10. SIEM, SOAR e Playbooks

Os conceitos estudados nos Módulos 3 e 4 podem ser relacionados da seguinte maneira:

### SIEM

Ajuda a coletar e analisar logs, monitorar atividades e gerar alertas.

### Playbook

Define procedimentos e orienta como a equipe deve responder a determinadas situações.

### SOAR

Pode automatizar determinadas tarefas e workflows relacionados à resposta.

Um fluxo simplificado seria:

Logs
  ↓
SIEM
  ↓
Detecção / Alerta
  ↓
Análise
  ↓
Playbook
  ↓
Resposta
  ↓
SOAR pode automatizar determinadas ações

---

# Principais Aprendizados

- Playbooks fornecem procedimentos para ações operacionais.
- Incident Response busca identificar ataques, conter danos e corrigir seus efeitos.
- As fases estudadas incluem Preparação, Detecção e Análise, Contenção, Erradicação e Recuperação, Atividade Pós-Incidente e Coordenação.
- SIEM e playbooks podem trabalhar em conjunto durante a identificação e resposta a incidentes.
- Um alerta SIEM deve ser avaliado para obter informações suficientes antes de determinar a resposta apropriada.
- Playbooks possuem estratégias, expectativas e planos para orientar as ações da equipe.
- Playbooks são Living Documents e devem acompanhar mudanças nas ameaças, procedimentos, leis e requisitos de compliance.
- Organizações podem utilizar diferentes ferramentas, metodologias e procedimentos de Incident Response.
- SOAR pode automatizar tarefas repetitivas relacionadas a eventos e alertas de segurança.
- SIEM, SOAR e playbooks podem fazer parte de um processo integrado de detecção e resposta a incidentes.
