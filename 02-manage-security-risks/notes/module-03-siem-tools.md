# Módulo 3 — SIEM, Logs e Ferramentas de Segurança

## 1. Logs

Um **log** é um registro de eventos que ocorrem nos sistemas e redes de uma organização.

Os logs fornecem informações importantes para profissionais de cybersecurity investigarem atividades, identificarem comportamentos suspeitos e compreenderem eventos ocorridos dentro da infraestrutura.

### Common Log Sources

#### Firewall Logs

Registram informações relacionadas às conexões e ao tráfego que passa pelo firewall, incluindo tentativas de conexão.

Esses registros podem ajudar na identificação de atividades suspeitas relacionadas ao tráfego de rede.

#### Network Logs

Registram eventos e atividades relacionados aos dispositivos e ao tráfego de uma rede.

Essas informações ajudam os profissionais de segurança a analisar o comportamento da rede e identificar possíveis anomalias.

#### Server Logs

Registram eventos relacionados aos serviços executados pelos servidores, como:

- Websites
- E-mails
- Compartilhamento de arquivos

---

## 2. Security Information and Event Management (SIEM)

**SIEM — Security Information and Event Management** é uma aplicação que coleta e analisa dados de logs para monitorar atividades importantes dentro de uma organização.

Uma ferramenta SIEM permite centralizar informações provenientes de diferentes fontes.

Isso facilita atividades como:

- Monitoramento de eventos;
- Análise de logs;
- Identificação de atividades suspeitas;
- Geração de alertas;
- Investigação de incidentes;
- Visualização de informações através de dashboards.

Um fluxo simplificado pode ser representado como:

Logs → SIEM → Análise → Alerta → Investigação → Resposta

---

## 3. Métricas

**Métricas** são atributos técnicos utilizados para avaliar o desempenho de aplicações e sistemas.

Alguns exemplos incluem:

- Tempo de resposta;
- Disponibilidade;
- Taxas de falha.

Essas informações ajudam a compreender o comportamento e o desempenho de uma aplicação.

---

## 4. Tipos de SIEM

As soluções SIEM podem utilizar diferentes modelos de implantação.

### Self-hosted

A infraestrutura necessária para executar a ferramenta é mantida pela própria organização.

### Cloud-hosted

A ferramenta é hospedada na nuvem e sua infraestrutura é mantida pelo fornecedor.

Isso pode ser útil para organizações que não desejam criar e manter toda a infraestrutura necessária para executar seu próprio SIEM.

### Cloud-native

Ferramentas **Cloud-native** são desenvolvidas especificamente para aproveitar características da computação em nuvem, como:

- Availability;
- Flexibility;
- Scalability.

### Hybrid

Pode combinar características da infraestrutura local com serviços hospedados na nuvem.

---

# 5. Splunk

A **Splunk** oferece soluções utilizadas para coletar, pesquisar, monitorar e analisar dados de logs.

## Splunk Enterprise

O **Splunk Enterprise** pode ser utilizado para reter, analisar e pesquisar dados de logs de uma organização, fornecendo informações e alertas relacionados à segurança.

## Splunk Cloud

O **Splunk Cloud** é uma solução hospedada na nuvem utilizada para coletar, pesquisar, monitorar e analisar dados de logs.

---

# 6. Splunk Dashboards

Os dashboards ajudam profissionais de segurança a transformar grandes quantidades de dados em informações mais fáceis de analisar.

## Security Posture Dashboard

Voltado para **Security Operations Centers (SOC)**.

Apresenta eventos e tendências relevantes de segurança e pode ajudar os analistas a monitorar e investigar possíveis ameaças.

Exemplo:

Identificação de atividades suspeitas originadas de determinado endereço IP.

## Executive Summary Dashboard

Fornece uma visão de alto nível sobre a situação da organização ao longo do tempo.

Pode ser utilizado para apresentar informações como:

- Incidentes de segurança;
- Tendências;
- Situação geral da segurança.

## Incident Review Dashboard

Auxilia na investigação de incidentes e na identificação de padrões suspeitos.

Uma característica importante é a possibilidade de visualizar uma **timeline dos eventos** relacionados a um incidente.

## Risk Analysis Dashboard

Ajuda a analisar riscos associados a diferentes objetos, como:

- Usuários;
- Computadores;
- Endereços IP.

Exemplos de comportamentos que podem chamar atenção:

- Login fora do horário normal;
- Tráfego de rede anormalmente alto;
- Mudanças incomuns no comportamento de um usuário ou dispositivo.

---

# 7. Google Chronicle

O **Google Chronicle** é uma ferramenta SIEM Cloud-native utilizada para reter, analisar e pesquisar dados de logs.

As pesquisas e análises podem envolver informações relacionadas a:

- Assets;
- Domain names;
- Users;
- IP addresses.

---

# 8. Chronicle Dashboards

## Enterprise Insights

Destaca alertas recentes e pode identificar elementos suspeitos conhecidos como **Indicators of Compromise (IOCs)**.

Os resultados podem apresentar informações como:

- Confidence Score;
- Severity;
- Alertas recentes.

Isso ajuda o analista a determinar quais possíveis ameaças devem receber maior atenção.

## Data Ingestion and Health

Apresenta informações relacionadas à entrada e ao processamento dos logs.

Pode ajudar a verificar se as fontes de logs estão configuradas corretamente e se os dados estão chegando sem erros.

## IOC Matches

Permite acompanhar possíveis **Indicators of Compromise (IOCs)**, incluindo:

- Domain names;
- IP addresses;
- Informações relacionadas a dispositivos.

Isso pode ajudar a identificar tendências e priorizar ameaças.

## Main Dashboard

Fornece uma visão geral de:

- Ingestão de dados;
- Alertas;
- Atividades e eventos.

Também pode auxiliar na análise de tendências ao longo do tempo.

Exemplo:

Um aumento repentino nas tentativas de login malsucedidas.

## Rule Detections

Apresenta informações sobre alertas acionados por regras de detecção.

Exemplo:

Uma regra pode gerar um alerta quando um usuário abre um anexo conhecido como malicioso.

Essas informações ajudam os analistas a identificar incidentes recorrentes e desenvolver estratégias para redução de riscos.

## User Sign In Overview

Fornece informações sobre o comportamento de login dos usuários.

Pode ajudar na identificação de comportamentos incomuns, como:

- Login a partir de locais incomuns;
- Usuário realizando login em diferentes locais simultaneamente.

---

# 9. Open Source vs. Proprietary Tools

## Open Source

Ferramentas **Open Source** disponibilizam seu código-fonte e permitem maior possibilidade de análise, modificação e personalização, respeitando sua licença.

Projetos Open Source podem ser desenvolvidos e aprimorados de forma colaborativa.

Exemplos estudados:

- Linux;
- Suricata.

## Proprietary

Ferramentas **Proprietary** pertencem a uma pessoa ou organização.

O código-fonte normalmente não está disponível aos usuários, e o desenvolvimento e as atualizações são controlados pelo proprietário.

Exemplos estudados:

- Splunk;
- Google Chronicle.

---

# 10. Linux

**Linux** é um sistema operacional Open Source amplamente utilizado.

Um sistema operacional funciona como uma interface entre o hardware do computador e o usuário, além de gerenciar aplicações de software.

O Linux permite a utilização de uma **Command-Line Interface (CLI)** e possui diferentes distribuições voltadas para diferentes necessidades.

---

# 11. Suricata

**Suricata** é uma ferramenta Open Source utilizada para análise de rede e detecção de ameaças.

Ela pode inspecionar o tráfego de rede para:

- Identificar comportamentos suspeitos;
- Gerar registros relacionados à rede;
- Auxiliar na identificação de possíveis ameaças.

O Suricata é desenvolvido pela **Open Information Security Foundation (OISF)** e pode ser integrado com ferramentas SIEM e outras ferramentas de segurança.

---

# 12. Security Orchestration, Automation and Response (SOAR)

**SOAR — Security Orchestration, Automation and Response** é um conjunto de aplicações, ferramentas e workflows que utiliza automação para responder a eventos de segurança.

A automação permite que determinadas atividades relacionadas a incidentes sejam executadas com menor necessidade de intervenção manual.

Isso pode liberar os profissionais de segurança para concentrarem seus esforços em incidentes mais complexos.

Uma representação simplificada é:

Evento → Detecção → Automação → Resposta

---

# 13. SIEM e SOAR

SIEM e SOAR podem participar de diferentes partes do processo de segurança.

De forma simplificada:

SIEM:
Coleta de logs → Análise → Detecção → Alertas

SOAR:
Alerta/Evento → Workflow → Automação → Resposta

Dessa forma, ferramentas de segurança podem trabalhar de maneira integrada para melhorar a capacidade de detectar e responder a possíveis incidentes.

---

# 14. Evolução das ferramentas SIEM

As ferramentas SIEM continuam evoluindo devido a mudanças na tecnologia e nas técnicas utilizadas por threat actors.

Algumas tendências estudadas incluem:

### Cloud Computing

Soluções SIEM estão cada vez mais presentes em ambientes hospedados ou nativos da nuvem.

### Internet of Things (IoT)

O aumento de dispositivos conectados também aumenta a **Attack Surface** e a quantidade de dados que precisam ser monitorados.

### Artificial Intelligence e Machine Learning

AI e ML podem ampliar capacidades relacionadas à identificação e análise de ameaças e ao tratamento de grandes volumes de dados.

### Automation

A automação pode reduzir o trabalho manual necessário para lidar com determinados eventos de segurança.

---

# 15. Uso de SIEM durante uma investigação

Um SIEM ajuda profissionais de segurança a centralizar e analisar informações provenientes de diferentes logs.

Em uma situação envolvendo tentativas suspeitas de acesso a contas, por exemplo, informações importantes podem incluir:

- Source IP;
- Conta afetada;
- Horário;
- Origem da atividade;
- Quantidade de tentativas;
- Outros eventos relacionados.

Os dashboards ajudam a organizar essas informações e permitem identificar padrões, tendências e anomalias.

Alertas automatizados também ajudam a reduzir o tempo necessário para que a equipe perceba uma possível atividade suspeita.

Um possível fluxo de investigação seria:

Atividade anômala
        ↓
Logs são gerados
        ↓
SIEM centraliza os eventos
        ↓
Regra/Análise identifica comportamento suspeito
        ↓
Alerta
        ↓
Analista investiga
        ↓
Possível resposta ao incidente

---

# Principais aprendizados

- Logs registram eventos importantes de sistemas e redes.
- Firewall, Network e Server Logs são fontes importantes de informações.
- SIEM centraliza e analisa dados provenientes de diferentes logs.
- Splunk e Chronicle são exemplos de ferramentas SIEM estudadas.
- Dashboards ajudam analistas a identificar tendências, anomalias e possíveis ameaças.
- IOCs podem auxiliar na identificação de possíveis comprometimentos.
- Ferramentas podem ser Open Source ou Proprietary.
- Linux e Suricata são exemplos de ferramentas Open Source estudadas.
- Suricata pode ser utilizado para análise de rede e detecção de ameaças.
- SOAR utiliza automação para auxiliar na resposta a eventos de segurança.
- Cloud Computing, IoT, AI/ML e automação estão influenciando a evolução das ferramentas SIEM.
- O valor de um SIEM não está apenas em armazenar logs, mas em ajudar profissionais de segurança a transformar eventos em informações úteis para investigação e resposta.
