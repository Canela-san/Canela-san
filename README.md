<div align="center">

# Gabriel Canela

**Engenharia de Controle e Automação · Unicamp**

Sistemas embarcados de tempo real, instrumentação e controle aplicado

![Status](https://img.shields.io/badge/Status-Aberto%20a%20Est%C3%A1gio-2ea44f?style=flat-square)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-canela-ti/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gabriel.canela.ti@gmail.com)
![Localização](https://img.shields.io/badge/Campinas%2C%20SP-555555?style=flat-square&logo=googlemaps&logoColor=white)
![Seguidores](https://img.shields.io/github/followers/Canela-san?style=flat-square&logo=github&logoColor=white&label=Seguidores&color=24292f)

</div>

<br>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Canela-san/Canela-san/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Canela-san/Canela-san/output/github-contribution-grid-snake.svg" />
  <img alt="cobra comendo o gráfico de contribuições do GitHub" src="https://raw.githubusercontent.com/Canela-san/Canela-san/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

</div>

<br>

## Sobre

Estudante de Engenharia de Controle e Automação na Unicamp (8º semestre), com formação técnica dupla em Informática pela ETEC. Hoje sou bolsista de Iniciação Científica pela FAPESP na FEEC (Faculdade de Engenharia Elétrica e de Computação), desenvolvendo instrumentação embarcada para redes elétricas — um projeto que mistura modelagem de sistemas de controle, processamento digital de sinais e programação de baixo nível num coprocessador de tempo real.

Antes disso, passei dois anos como técnico no LabREI (Laboratório de Redes Elétricas Inteligentes), dando suporte a pesquisadores de pós-graduação na montagem e validação de conversores de potência e cuidando da infraestrutura de TI do laboratório.

## No momento

- Reescrevendo o firmware do SH-Analyzer, migrando de um protótipo em C puro para uma arquitetura híbrida ARM + PRU-ICSS (Assembly), buscando superar o limite de ~102 kHz do protótipo original
- Depurando um bug de saturação no barramento SPI, já isolado até um padrão de assimetria de tempo de subida/descida característico de um optoacoplador
- Cursando as disciplinas de controle da Unicamp — projeto recente: sintonia de um controlador PID por lugar das raízes (root locus) para controle de velocidade de um motor DC, validado em MATLAB/Simulink

## Projetos em destaque

**[SH-Analyzer](https://github.com/Canela-san/SH-Analyzer)** ![Stars](https://img.shields.io/github/stars/Canela-san/SH-Analyzer?style=flat-square)
Instrumentação embarcada para identificar supraharmônicos — distúrbios de dezenas de kHz que costumam escapar dos analisadores de qualidade de energia convencionais. Arquitetura híbrida na BeagleBone Black: a PRU-ICSS faz *bit-banging* determinístico do protocolo SPI com um ADC de 16 bits (ADS8688), gravando amostras em buffers *ping-pong* direto na DDR, enquanto o ARM só copia os blocos prontos para o disco. Iniciação Científica (FAPESP), orientada pelo Prof. Dr. José Antenor Pomilio (FEEC/Unicamp).
`C` `Assembly (PRU)` `Altium Designer` `Python`

**[ProcessorFromScratch](https://github.com/Canela-san/ProcessorFromScratch)** ![Stars](https://img.shields.io/github/stars/Canela-san/ProcessorFromScratch?style=flat-square)
Processador simples modelado do zero: da arquitetura em blocos (ULA, banco de registradores, unidade de controle) até a validação de cada porta lógica em nível de transistor (MOSFET), com um conjunto de instruções e montador Assembly próprios para rodar uma animação num display simulado.
`Digital (simulador lógico)` `Arquitetura de Computadores` `Assembly`

**[Nuvem-Privada](https://github.com/Canela-san/Nuvem-Privada)** ![Stars](https://img.shields.io/github/stars/Canela-san/Nuvem-Privada?style=flat-square)
NAS self-hosted baseado em Nextcloud, orquestrado com Docker Compose (health checks entre app/banco/cache) e acessível remotamente via Tailscale, sem expor portas na internet. Scripts de provisionamento, manutenção periódica e backup a frio com verificação de integridade automática.
`Docker Compose` `Shell Script` `Linux` `Tailscale`

**[isp-benchmark-suite](https://github.com/Canela-san/isp-benchmark-suite)** ![Stars](https://img.shields.io/github/stars/Canela-san/isp-benchmark-suite?style=flat-square)
Ferramenta de auditoria de qualidade de conexão à internet: coleta contínua de latência, jitter e perda de pacotes em Bash, com detecção automática de degradação de link físico e análise em série temporal com Python/Pandas/Seaborn.
`Bash` `Python` `Pandas`

## Competências técnicas

**Controle & Simulação**
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=flat-square)
![LTspice](https://img.shields.io/badge/LTspice-CC0000?style=flat-square)

**Sistemas Embarcados, Tempo Real & Hardware**
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Assembly](https://img.shields.io/badge/Assembly-654FF0?style=flat-square)
![ARM Cortex-A8](https://img.shields.io/badge/ARM%20Cortex--A8-0091BD?style=flat-square&logo=arm&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Altium Designer](https://img.shields.io/badge/Altium%20Designer-CD1F3E?style=flat-square)

**Programação & Dados**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

**DevOps & Ferramentas**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

## Formação & Idiomas

**Unicamp** — Engenharia de Controle e Automação (2022 – 2028, previsto)

**ETEC** — Técnico em Informática · Técnico em Informática para Internet (2017 – 2019)

Português (nativo) · Inglês (avançado, CCAA) · Japonês (básico, JLPT N5)

---

<div align="center">

📩 [gabriel.canela.ti@gmail.com](mailto:gabriel.canela.ti@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/gabriel-canela-ti/) &nbsp;·&nbsp; 📍 Campinas, SP

![Visitas](https://komarev.com/ghpvc/?username=Canela-san&style=flat-square&color=6c757d&label=Visitas+ao+perfil)

</div>
