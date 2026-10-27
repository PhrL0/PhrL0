<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0B0E14,55:111827,100:F5B700&text=Pedro%20Henrique&fontSize=52&fontColor=E6EDF3&fontAlignY=36&desc=DEVOPS%20ENGINEER%20%C2%B7%20DI%C3%81RIO%20DE%20BORDO&descSize=16&descAlignY=56&animation=fadeIn" alt="Banner com gradiente do preto espacial ao dourado: Pedro Henrique, DevOps Engineer, diário de bordo" />

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1200&color=F5B700&background=0B0E14&center=true&vCenter=true&width=640&height=44&lines=%3E+SISTEMAS+RESTAURADOS...;%3E+IDENTIFICANDO+TRIPULANTE...;%3E+PEDRO+HENRIQUE+%C2%B7+DEVOPS+ENGINEER+%C2%B7+SP%2C+BR;%3E+DE+EMBARCADOS+A+PLATAFORMAS.+STATUS%3A+OK" alt="Terminal da nave inicializando: sistemas restaurados, identificando tripulante, Pedro Henrique, DevOps Engineer em São Paulo" />
</div>

```text
   .        *         .            .        *          .         *
       .         .         *        __        .    .         .
  (O)  - - - - - - - - - - - -  >==[__]>  - - - - - - - - - - - (*)
  SOL      *        .        .         *     ~1,2 x 10^1 a.l.   TAU CETI
```

## 📓 Registro do tripulante

> **Diário de bordo · registro 2026.300**

Os sistemas reiniciaram e a primeira coisa que voltou foi o crachá: **Pedro Henrique**, **Analista DevOps Júnior na CSD BR** desde fevereiro de 2026, base em São Paulo, Brasil.

O resto da memória veio em camadas. Primeiro a física: **Eletroeletrônica**, depois **Análise e Desenvolvimento de Sistemas** e Técnico em Desenvolvimento de Sistemas pelo **SENAI**. Anos entre ESP32, Arduino, C++, MQTT, HTTP, LoRa e CAN me ensinaram a respeitar detalhes, telemetria e falhas sem glamour, porque sistema embarcado não aceita "na minha máquina funcionou".

Então veio a hipótese que mudou a rota: os princípios de confiabilidade que mantêm um dispositivo vivo valem para a plataforma inteira ao redor dele. Assim nasceu o DevOps. **Objetivo da missão:** deploys repetíveis, segredos no lugar certo, clusters observáveis e menos espaço para improviso.

## 🛰️ Sistemas da nave

| Subsistema | Equipamento |
| :-- | :-- |
| ☁️ **Órbita** · cloud | ![AWS](https://img.shields.io/badge/AWS-111827?style=for-the-badge) |
| 🚀 **Propulsão** · containers e orquestração | ![Docker](https://img.shields.io/badge/Docker-111827?style=for-the-badge&logo=docker&logoColor=F5B700) ![Kubernetes](https://img.shields.io/badge/Kubernetes-111827?style=for-the-badge&logo=kubernetes&logoColor=F5B700) |
| ⭐ **Navegação** · CI/CD e GitOps | ![Jenkins](https://img.shields.io/badge/Jenkins-111827?style=for-the-badge&logo=jenkins&logoColor=F5B700) ![GitLab](https://img.shields.io/badge/GitLab-111827?style=for-the-badge&logo=gitlab&logoColor=F5B700) ![ArgoCD](https://img.shields.io/badge/ArgoCD-111827?style=for-the-badge&logo=argo&logoColor=F5B700) |
| 📡 **Sensores** · observabilidade | ![Grafana](https://img.shields.io/badge/Grafana-111827?style=for-the-badge&logo=grafana&logoColor=F5B700) ![Prometheus](https://img.shields.io/badge/Prometheus-111827?style=for-the-badge&logo=prometheus&logoColor=F5B700) |
| 🧪 **Laboratório** · dados e infra distribuída | ![Apache Cassandra](https://img.shields.io/badge/Apache%20Cassandra-111827?style=for-the-badge&logo=apachecassandra&logoColor=F5B700) ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-111827?style=for-the-badge&logo=apachekafka&logoColor=F5B700) |
| ☀️ **Suporte de vida** · sistema | ![Linux](https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=F5B700) |
| 🔬 **Módulo de origem** · raízes embarcadas | ![C++](https://img.shields.io/badge/C%2B%2B-E23D28?style=for-the-badge&logo=cplusplus&logoColor=E6EDF3) ![Arduino](https://img.shields.io/badge/Arduino-E23D28?style=for-the-badge&logo=arduino&logoColor=E6EDF3) ![ESP32](https://img.shields.io/badge/ESP32-E23D28?style=for-the-badge&logo=espressif&logoColor=E6EDF3) ![MQTT](https://img.shields.io/badge/MQTT-E23D28?style=for-the-badge&logo=mqtt&logoColor=E6EDF3) |

## 🧪 Experimentos em andamento

**EXPERIMENTO #1 — Sealed Secrets → External Secrets Operator** · Status: 🟢 padrão aplicado em 3 × 10⁰ ambientes

- **Hipótese:** segredos espalhados entre manifestos ficam mais seguros e simples de manter com uma fonte de verdade adequada ao ambiente.
- **Procedimento:** liderei a migração de **Sealed Secrets** para **External Secrets Operator (ESO)**, com **AWS Secrets Manager** como backend, em todos os ambientes: **dev, QA e HML**.
- **Resultados:** segredos desacoplados dos manifestos versionados · gestão centralizada e mais flexível das credenciais · fluxo alinhado ao GitOps · base mais limpa para rotação, manutenção e evolução dos ambientes.

**EXPERIMENTO #2 — Gerenciador de nodes Cassandra** · Status: 🟢 ativo nos ambientes de QA para baixo

- **Hipótese:** manutenção de Cassandra não pode depender de lembrete, planilha ou intervenção manual toda vez que algo precisa acontecer.
- **Procedimento:** lidero uma ferramenta própria para gerenciar nodes Cassandra, com **agendamento automatizado de repairs**, monitoramento dos clusters e o **Cassandra Reaper** operando por trás da aplicação.
- **Resultados:** rotinas recorrentes tratadas como processo, não como tarefa avulsa · mais visibilidade sobre o estado dos clusters · operação mais previsível nos ambientes não produtivos · menos atrito para quem cuida da plataforma no dia a dia.

## 📡 Telemetria

<div align="center">
  <a href="https://github.com/PhrL0">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./profile/stats-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="./profile/stats-light.svg" />
      <img height="165" src="./profile/stats-dark.svg" alt="Estatísticas do GitHub de Pedro Henrique: estrelas, commits, PRs e issues" />
    </picture>
  </a>
  <a href="https://github.com/PhrL0">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./profile/top-langs-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="./profile/top-langs-light.svg" />
      <img height="165" src="./profile/top-langs-dark.svg" alt="Linguagens mais usadas nos repositórios de Pedro Henrique" />
    </picture>
  </a>
  <br />
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=PhrL0&locale=pt_BR&hide_border=true&background=00000000&ring=F5B700&fire=E23D28&stroke=F5B700&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=FFC94A&sideLabels=E6EDF3&dates=E6EDF3" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=PhrL0&locale=pt_BR&hide_border=true&background=00000000&ring=F5B700&fire=E23D28&stroke=E23D28&currStreakNum=111827&sideNums=111827&currStreakLabel=E23D28&sideLabels=111827&dates=111827" />
    <img height="165" src="https://streak-stats.demolab.com?user=PhrL0&locale=pt_BR&hide_border=true&background=00000000&ring=F5B700&fire=E23D28&stroke=F5B700&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=FFC94A&sideLabels=E6EDF3&dates=E6EDF3" alt="Sequência de contribuições no GitHub: total, sequência atual e maior sequência" />
  </picture>
  <br />
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PhrL0/PhrL0/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PhrL0/PhrL0/output/github-contribution-grid-snake-light.svg" />
    <img src="https://raw.githubusercontent.com/PhrL0/PhrL0/output/github-contribution-grid-snake-dark.svg" alt="Animação de cobra percorrendo o gráfico de contribuições do último ano" />
  </picture>
</div>

## 📻 Canal de comunicação

<div align="center">

♪ &nbsp; frequências de contato abertas &nbsp; ♫

<a href="https://www.linkedin.com/in/pedroleme11"><img src="https://img.shields.io/badge/LinkedIn-pedroleme11-111827?style=for-the-badge&labelColor=F5B700" alt="LinkedIn: pedroleme11" /></a>
<a href="mailto:ph137163@gmail.com"><img src="https://img.shields.io/badge/E--mail-ph137163%40gmail.com-E23D28?style=for-the-badge&logo=gmail&logoColor=E6EDF3&labelColor=111827" alt="E-mail: ph137163@gmail.com" /></a>
<img src="https://img.shields.io/badge/Base-S%C3%A3o%20Paulo%2C%20Brasil-111827?style=for-the-badge&logo=googlemaps&logoColor=F5B700&labelColor=111827" alt="Base: São Paulo, Brasil" />

♫ &nbsp; ♪ &nbsp; ♫

</div>

<details>
<summary>📁 <b>Arquivos confidenciais da missão</b></summary>

<br />

- 🎬 Gênero preferido no cinema: romance e drama. Se tem Ryan Gosling no elenco, a probabilidade de eu assistir tende a 1. A temporada anterior deste perfil se passava sob uma *City of Stars*: mesmo ator favorito, outra galáxia.
- ♪ Maior passatempo: ouvir música, de qualquer gênero. O receptor da nave não filtra frequência.
- 🔬 Filosofia, principalmente a existencial. Autor favorito: **Albert Camus**. Rodar o mesmo pipeline todo dia e ainda encontrar sentido nisso é praticamente um exercício de Sísifo.
- 🔌 Antes de clusters, eram sensores: LoRa e barramento CAN estão no currículo de origem.
- 📏 Tolerância a "na minha máquina funcionou": 0 × 10⁰.
- 🔐 Ambientes migrados para External Secrets Operator: 3 × 10⁰ (dev, QA e HML).
- 🌌 Distância até Tau Ceti: ~1,2 × 10¹ anos-luz. Distância até o próximo deploy: menor.

</details>

<div align="center">
  <br />
  <code>🛰️ STATUS: Missão em andamento. Combustível: café. ☕</code>
  <br /><br />
  <img src="https://komarev.com/ghpvc/?username=PhrL0&style=for-the-badge&color=F5B700&label=SINAIS%20RECEBIDOS" alt="Contador de visitas ao perfil" />
  <br /><br />
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:0B0E14,55:111827,100:F5B700" alt="Banner de encerramento com gradiente do preto espacial ao dourado" />
</div>
