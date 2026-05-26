<div align="center">

# Matheus Sant'Ana Oliveira

**Backend Developer · .NET · Elastic Stack · RabbitMQ · Docker**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/matheus-sant-ana)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Matheus-SantAnaOliveira)

</div>

---

## Sobre mim

Desenvolvedor back-end com foco em **processamento de eventos**, **observabilidade** e **automação de dados**.

Formado em **Análise e Desenvolvimento de Sistemas** pela USJT e finalizando **Bacharelado em Ciência da Computação** (também USJT).

No dia a dia, trabalho com pipelines que processam **dezenas de milhares de mensagens diárias** via RabbitMQ, indexação e análise no Elasticsearch, e construção de plataformas de observabilidade usadas por times inteiros. Também desenvolvi um **chatbot que interpreta linguagem natural e consulta o Elastic dinamicamente** — sem queries manuais.

Fora do trabalho: projeto pessoal de **telemetria em tempo real para o F1 25** com comandos de voz offline. Porque por que não?

---

## Stack principal

**Back-end**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Mensageria & Dados**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Logstash](https://img.shields.io/badge/Logstash-005571?style=flat-square&logo=logstash&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white)
![Metricbeat](https://img.shields.io/badge/Metricbeat-005571?style=flat-square&logo=elastic&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

**Infra & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

---

## 🏎️ Projeto em destaque — Telemetry F1 25 + Voice Command

> **O problema:** acompanhar telemetria durante uma corrida sem sair da tela do jogo.
> **A solução:** comandar dashboards com a voz, sem Alt+Tab, sem teclado.

```
F1 25 (UDP)  →  .NET Worker  →  Elasticsearch  →  Kibana Dashboards
                                                          ↑
                              Vosk (offline STT)  →  Voice Worker
```

**[Ver repositório →](https://github.com/Matheus-SantAnaOliveira/Telemetry-F125-VoiceCommand)**

| Componente | Tecnologia | O que faz |
|---|---|---|
| Telemetry Worker | C# / .NET 8 | Lê pacotes UDP da EA, normaliza e indexa no Elastic |
| Voice Worker | C# / Vosk | Reconhecimento de fala 100% offline em PT-BR |
| Dashboards | Kibana | Pneus, ERS, danos, voltas, clima — tudo em tempo real |

---

## Outros projetos

| Projeto | Descrição | Stack |
|---|---|---|
| [TrabalhoA3Grafos](https://github.com/Matheus-SantAnaOliveira/TrabalhoA3Grafos) | Análise de grafos e matrizes com visualizações | C# · Python · Jupyter |
| [Agenda Django](https://github.com/Matheus-SantAnaOliveira/agenda_projeto_DJANGO-FINALIZADO) | Sistema de agenda web com CRUD completo | Python · Django |
| [Projeto A3 Dados](https://github.com/Matheus-SantAnaOliveira/Projeto-A3-DADOS-USJT-SemVenv-) | Análise de dados — projeto acadêmico | Python |

---

## Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Matheus-SantAnaOliveira&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&include_all_commits=true" alt="GitHub Stats" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Matheus-SantAnaOliveira&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff" alt="Top Languages" />

</div>

---

<div align="center">
<sub>Backend Developer · Ciência da Computação @ USJT · São Paulo</sub>
</div>
