# Mulher Digital Cibersegurança
Documentação de ferramentas, comandos e práticas que realizei durante o programa Mulher Digital promovido pela Junior Achievement Americas!!

**Sumário**
1. [Introdução à Cibersegurança](#1-introdução-à-cibersegurança)
   - [Laboratório 01 - Nmap: Descoberta de Serviços e Fingerprinting](#laboratório-01---nmap-descoberta-de-serviços-e-fingerprinting)
2. [Gerenciamento de Ameaças Cibernéticas](#2-gerenciamento-de-ameaças-cibernéticas)
3. [Segurança de Endpoints](#3-segurança-de-endpoints)
4. [Conceitos de Redes](#4-conceitos-de-redes)
5. [Defesa de Redes](#5-defesa-de-redes)
6. [Dispositivos de Rede](#6-dispositivos-de-rede)

## 1. Introdução à Cibersegurança
Anotações, exercícios e laboratórios realizados durante o módulo de Introdução à Cibersegurança.

### 🧪Laboratórios

#### Laboratório 01 - Nmap: descoberta de serviços e fingerprinting

**Objetivo:** Identificar portas abertas, serviços em execução e características do sistema operacional utilizando o Nmap.
  
**Habilidades praticadas:**
- Reconhecimento de rede
- Enumeração de serviços
- Identificação de portas abertas
- Fingerprinting de sistemas operacionais
- Interpretação de resultados do Nmap

**Comandos utilizados**

Durante o laboratório eu executei diferentes tipos de scans para compreender as capacidades do Nmap.

#### Scan completo com detecção de serviços e sistema operacional

```bash
nmap -T4 -A -v <IP_ALVO>
```

| Opção | Função |
|---------|---------|
| `-A` | Ativa detecção de SO, versões, scripts NSE e traceroute |
| `-v` | Exibe informações detalhadas durante a execução |

---

#### Detecção de SO
```bash
nmap -O scanme.nmap.org
```

| Opção | Função |
|---------|---------|
| `-O` | Identificação do sistema operacional |

> O domínio `scanme.nmap.org` é disponibilizado oficialmente pela equipe do Nmap para fins educacionais e testes autorizados.

---

#### Scan avançado

```bash
nmap -A <IP_ALVO>
```

| Opção | Função |
|---------|---------|
| `-A` | Ativa recursos avançados de detecção |

---

#### SYN scan

```bash
nmap -sS -T4 -v <IP_ALVO>
```

| Opção | Função |
|---------|---------|
| `-sS` | SYN stealth scan |
| `-v` | Exibe informações detalhadas |





## 2. Gerenciamento de Ameaças Cibernéticas

Anotações e atividades relacionadas à identificação, análise e mitigação de ameaças digitais.

### Tópicos estudados

- Malware
- Engenharia Social
- Vetores de Ataque
- Gestão de Riscos
- Ameaças Internas e Externas

## 3. Segurança de Endpoints

Conteúdos sobre proteção de dispositivos, estações de trabalho e controle de acesso.

### Tópicos estudados

- Antivírus
- EDR
- Hardening
- Controle de Acesso
- Atualizações de Segurança

## 4. Conceitos de Redes

Fundamentos de redes de computadores, protocolos e comunicação entre dispositivos.

### Tópicos estudados

- Modelo OSI
- Modelo TCP/IP
- Endereçamento IPv4
- Endereçamento IPv6
- DNS
- DHCP
- Sub-redes

## 5. Defesa de Redes

Estudos sobre monitoramento, segmentação e mecanismos de proteção de redes.

### Tópicos estudados

- Firewalls
- IDS/IPS
- Defesa em Profundidade
- Monitoramento de Rede
- Segmentação de Rede

## 6. Dispositivos de Rede

Conhecimentos relacionados aos principais dispositivos de infraestrutura de redes.

### Tópicos estudados

- Switches
- Roteadores
- Access Points
- Firewalls
- Dispositivos de Segurança

## Estrutura do Repositório

```text
Mulher-Digital-Ciberseguranca/
│
├── README.md
│
├── Introducao-Ciberseguranca/
│   └── Lab-01-Nmap/
│       ├── README.md
│       └── screenshots/
│
├── Gerenciamento-Ameacas-Ciberneticas/
├── Seguranca-Endpoints/
├── Conceitos-Redes/
├── Defesa-Redes/
└── Dispositivos-Rede/
```

## Objetivo

Este repositório serve como documentação da minha jornada de aprendizado em Cibersegurança, reunindo anotações, laboratórios e práticas realizadas ao longo da formação.

---

## 🔐Aviso

Todos os laboratórios documentados neste repositório foram realizados em ambientes controlados e autorizados, exclusivamente para fins educacionais.
