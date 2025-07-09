# 📊 Desafio 5 – Análise de Logs Suspeitos

## 🧩 Situação

Nosso SIEM (Sistema de Monitoramento de Eventos) detectou um pico anormal de acessos ao painel de administração da TechWave fora do expediente.

Os logs foram extraídos e fornecidos para investigação detalhada, e é seu objetivo identificar possíveis atividades suspeitas.

---

## 🎯 Objetivos

- Analisar os logs fornecidos, que na vida real teriam sido extraídos de ferramentas como Wireshark ou de monitoramento de processos.
- Identificar IPs suspeitos ou maliciosos que podem estar realizando ataques de força bruta ou acessos não autorizados.
- Detectar usuários ou processos que executaram comandos suspeitos.
- Observar horários, PIDs, e eventuais padrões anômalos.
- Informar tudo no relatório com explicações do porquê você acha que determinados processos ou Ips são maliciosos.

---

## 📝 Formato dos Logs

Os logs estão formatados com as seguintes colunas, que podem ser usadas para importar em tabelas ou planilhas quando no formato .csv (Planilhas Google ou Micosoft Excel):

| Data/Hora          | Processo        | Programa      | PID   | Usuário   | IP Origem      | IP Destino       | Comando/Eventos          | Observações                  |


---

## ✅ Entrega esperada

- Escrever no relatório:
  - Análise dos eventos.
  - Indicação do(s) IP(s) malicioso(s).
  - Justificativa do porquê acha que o(s) evento(s) relacionado(s) a esse(s) IP(s) são suspeito(s).
  - Sugestões de mitigação (pode ser criativo!)
