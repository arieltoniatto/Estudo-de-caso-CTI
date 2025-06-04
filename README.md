# Estudo de Caso – Resposta a Incidentes e Análise Forense

**Curso:** Hackers do Bem – Especialização em Resposta a Incidentes e Forense

---

## Descrição do Caso

A empresa **Good Money Financial** reportou um incidente de segurança cibernética. Um de seus servidores foi comprometido, e há **suspeita de vazamento de informações sensíveis de clientes**.

Como Analista de Segurança da Informação, sua missão é realizar uma **análise forense de um arquivo PCAP** extraído de um dos computadores afetados. O objetivo é **identificar os principais Indicadores de Comprometimento (IoCs)** para apoiar a **contenção e remediação da ameaça**.

---

## Objetivos da Análise

Responder às seguintes perguntas com base na análise do tráfego de rede:

1. **Q1:** Qual é o endereço MAC do cliente Windows em `172.17.1.129`?
2. **Q2:** Qual é o nome do host do cliente Windows em `172.17.1.129`?
3. **Q3:** Qual URL no PCAP retornou um documento do Microsoft Word?
4. **Q4:** Que tipo de infecção ocorreu neste PCAP?
5. **Q5:** Desenvolver um **Relatório Operacional de CTI** com:

   * Resumo das descobertas
   * Indicadores de Comprometimento (IoCs)
   * Recomendações para contenção e remediação

---

## 🧪 Ferramentas Utilizadas

* Zeek (comando `zeek-cut`)
* VirusTotal e Hybrid Analysis (consulta de IoCs)
* Relatórios da Kaspersky e CTIR Gov

---

## 🔒 Nota Final

Este estudo de caso reforça a importância de monitoramento proativo da rede e resposta rápida a incidentes. O uso de ferramentas como Zeek, VirusTotal, Hybdri Anaylis e práticas de CTI são fundamentais para detectar, conter e erradicar ameaças modernas.

