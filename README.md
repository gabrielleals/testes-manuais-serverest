# 🧪 Casos de Teste - Cadastro de Usuário

Este repositório documenta os **testes manuais funcionais** para a funcionalidade de **cadastro de usuário** em um sistema web.  
O objetivo é validar regras de negócio, entradas obrigatórias e mensagens de retorno da aplicação.

---

## 📂 Estrutura
- `evidencias/` → GIFs com a execução dos casos de teste
- [📊 Planilha de Casos de Teste (Google Sheets)](https://docs.google.com/spreadsheets/d/1LiWYOAUG8l3TvhSj1Z5xJC30mfLV1nw56_CWgRjQRC0/edit?hl=pt-br&gid=0#gid=0) → documentação detalhada (pré-condições, passos, resultados esperados)

---

## 🎯 Cenário de Teste
- **Criar cadastro de usuário**

---

## ✅ Casos de Teste
1. Cadastro com todos os campos obrigatórios preenchidos corretamente  
2. Cadastro sem nome  
3. Cadastro sem e-mail  
4. Cadastro com e-mail inválido  
5. Cadastro sem senha  
6. Cadastro com usuário já existente  

---

## 🌐 Ambiente de Teste
- **Sistema:** Aplicação Web de Cadastro de Usuários  
- **URL:** https://front.serverest.dev/cadastrarusuarios
- **Navegador utilizado:** Google Chrome Versão 137.0.7151.104 (Versão oficial) 64 bits
- **Sistema Operacional:** Windows 11  

---

## 🎥 Evidências (GIFs)

[CT01 - Cadastro válido](evidencias/CT01.gif)<br>
[CT02 - Cadastro sem nome](evidencias/CT02.gif)<br>
[CT03 - Cadastro sem e-mail](evidencias/CT03.gif)<br>
[CT04 - Cadastro com e-mail inválido](evidencias/CT04.gif)<br>
[CT05 - Cadastro sem senha](evidencias/CT05.gif)<br>
[CT06 - Cadastro com usuário já existente](evidencias/CT06.gif)<br>

---

## 🚀 Como Executar os Testes
1. Acesse o ambiente de teste informado acima  
2. Reproduza os passos descritos na [planilha de casos de teste](https://docs.google.com/spreadsheets/d/1LiWYOAUG8l3TvhSj1Z5xJC30mfLV1nw56_CWgRjQRC0/edit?hl=pt-br&gid=0#gid=0)  
3. Compare os **resultados obtidos** com os **resultados esperados**  
4. Registre status (Passou/Falhou) na planilha  

---

## 📌 Observações
- Os testes foram documentados com foco em **funcionalidade** e **validação de regras de negócio**.  
- Futuramente, podem servir como base para **automação de testes** (ex: Cypress, Selenium, Playwright).  
- Evidências foram gravadas em formato **GIF** para fácil visualização.  
