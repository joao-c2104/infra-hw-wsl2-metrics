# Análise de Desempenho de I/O e Virtualização (WSL2 vs Hyper-V)

Repositório público com os artefatos técnicos, dados brutos e scripts utilizados na medição de desempenho da infraestrutura de hardware para a disciplina da CESAR School.

## Estrutura do Repositório
* `/scripts`: Ferramentas em Python e usadas para estressar a CPU e a hierarquia de memória.
* `/dados_brutos`: Logs originais extraídos do terminal (saídas de I/O, contadores de IRQ e vmstat).
* `/imagens`: Gráficos gerados que comprovam o gargalo de largura de banda e limite de I/O no disco.

## Hardware Inspecionado
* **CPU:** Intel Core i5-13420H (12 Threads)
* **RAM (Hospedeiro):** [Inserir total real] / **RAM (WSL2):** Limitada a 3.7 GiB
* **SO:** Ubuntu 24.04 LTS sobre Windows 11 (WSL2)

**Autor:** João Carlos Vasconcelos de Gusmão
