# 🔍 Desafio 2 – Análise de Comunicação Ofuscada

## 🧩 Situação

Durante a triagem de eventos de segurança da rede, foi identificado um e-mail suspeito enviado para o setor jurídico. O conteúdo parecia legítimo à primeira vista, mas ao final da mensagem havia um **bloco de texto incomum**, com caracteres aparentemente sem sentido.

Esse trecho foi extraído e armazenado em um arquivo chamado `Email_Ofuscado.txt`. A equipe de Threat Intelligence acredita que ele pode conter uma **mensagem escondida ou instruções para ação maliciosa**, ofuscadas com alguma técnica simples.

> 🕵️ Sua missão é descobrir **se há conteúdo sigiloso ou comprometedor escondido nesse trecho**, e qual foi o método usado para ocultá-lo.

---

## 🛠️ Passos

1. Acesse o arquivo `Email_Ofuscado.txt`.
2. Analise o conteúdo suspeito e identifique se há padrões que indicam algum tipo de ofuscação.
3. Tente reverter o processo (ex: decodificação, conversão, ou outra forma de interpretação).
4. Se encontrar alguma **mensagem legível, instrução ou flag**, registre no relatório.
5. Indique o **tipo de técnica** que acredita ter sido utilizada para esconder a mensagem.

---

## 🧠 Dicas

- Ferramentas comuns de ataque usam codificações simples para burlar filtros de e-mail ou sistemas de detecção.
- Preste atenção em:
  - Padrões de repetição ou blocos com comprimento fixo
  - Caracteres comuns em codificações (`=`, `/`, `+`)
  - Se o texto parecer embaralhado mas estruturado, isso pode ser proposital
- Teste diferentes tipos de conversão (ex: texto → hexadecimal → binário) até obter uma mensagem inteligível

---

## ✅ Objetivo

- Identificar se há informação oculta
- Decodificar a mensagem e registrar a descoberta
- Apontar a técnica utilizada (ou sua hipótese)
- Analisar o risco da comunicação passar despercebida


