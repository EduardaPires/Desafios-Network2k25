# 🔐 Desafio 1 – Perfis e Senhas Fracas (TechWave Solutions)

## 📄 Contexto

Como parte da auditoria de segurança interna, a **TechWave Solutions** decidiu verificar se os colaboradores estão adotando boas práticas na criação de senhas para proteger arquivos confidenciais.

Três funcionários de diferentes setores enviaram arquivos `.zip`, cada um contendo informações sensíveis. Esses arquivos estão protegidos por **senhas criadas por eles mesmos**.

Seu objetivo como **analista de segurança** é tentar descobrir essas senhas com base no **perfil pessoal de cada colaborador**, sem o uso de força bruta ou ferramentas automatizadas. O desafio simula um cenário real de **engenharia social** e análise de comportamento.

---

## 🎯 Objetivo

- Descobrir a senha de cada arquivo `.zip` usando lógica e análise de perfil
- Extrair o conteúdo de cada arquivo
- Identificar a fragilidade da senha escolhida
- Sugerir uma senha mais segura para cada colaborador

> ❌ **Atenção:** uso de ataques de força bruta ou dicionários automáticos não é permitido neste desafio.

---

## 👥 Perfis dos Colaboradores

### 👩 Amanda Souza – Marketing  
📁 Arquivo: `Confidencial_Amanda.zip`  
🎂 Nascimento: 17/03/1998 (27 anos)

**Informações do perfil:**
- Tem um gato branco chamado *Lua*, adotado em 2021
- Publica fotos com legendas em minúsculas e emojis 🐾
- Participou da campanha "TechWave Sustentável 2024"
- É apaixonada por fotografia analógica (câmeras Polaroid)
- Já apareceu com camisetas com frases como *"cat mom"*
- Alergia a frutos do mar
- Compartilha receitas de doces nas redes sociais

---

### 👨‍💼 Carlos Ribeiro – Financeiro  
📁 Arquivo: `Relatorio_Carlos.zip`  
🎂 Nascimento: 25/09/1989 (35 anos)

**Informações do perfil:**
- Fã de Fórmula 1 (torcedor da Ferrari)
- Tem um filho chamado Lucas, nascido em 2015
- Usa planner físico para organizar o dia a dia
- É resistente a mudanças tecnológicas
- Já disse que trocar senha “é burocracia demais”
- Nome de usuário nas redes: `carlos_ribeiro89`
- Colecionador de moedas e selos antigos

---

### 👨‍💻 Eduardo Martins – Tecnologia da Informação  
📁 Arquivo: `Secrets_Eduardo.zip`  
🎂 Nascimento: 14/11/1993 (31 anos)

**Informações do perfil:**
- Usa camisetas de banda e adesivos da Hot Peppers no notebook
- Tem action figures de Star Wars na mesa
- Fã de rock clássico (bandas como *Metallica*, *Iron Maiden*)
- Foi palestrante na *TechCon 2023* sobre DevSecOps
- Automatizou a cafeteira do escritório com scripts em Python
- Diz que lembra todas as senhas “de cabeça”

---

## 📁 O que fazer

1. Analise o perfil de cada colaborador
2. Tente descobrir a senha que eles provavelmente escolheriam
3. Extraia o conteúdo dos arquivos `.zip`
4. Anote:
   - A senha usada
   - FLAG encontrada dentro do arquivo
   - Qual foi a falha de segurança cometida
   - Sua sugestão de senha mais segura





