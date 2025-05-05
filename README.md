# 💼 Microsoft Fabric Challenge: Monitoramento de Vagas de Emprego

Bem-vindo ao **Microsoft Fabric Challenge**!  <br>
Nesta jornada, com a inspiração e o suporte da comunidade liderada por especialistas como:

- [Dirceu Resende](https://www.linkedin.com/in/dirceuresende)
- [Juliana Rodrigues](https://www.linkedin.com/in/julianamarialopes/)
- [Luiz Santana](https://www.linkedin.com/in/luizfsantana/),

E um "Data Evangelist":
- [Shalom André](https://www.linkedin.com/in/shalommandre)

Você será guiado passo a passo na construção de uma solução moderna de dados com o **Microsoft Fabric**.  
Ao concluir este desafio, você terá desenvolvido um pipeline completo e automatizado, que coleta dados de vagas de emprego em tempo real (streaming) ou em lote (batch), processa essas informações, consultas SQL e as apresenta de forma visual no Power BI — tudo isso com atualizações contínuas e integração via GitHub ou Azure DevOps.

---
#### O vídeo da nossa reunião: https://www.youtube.com/watch?v=1OtVi40qxK8&sub_confirmation=1
#### Data de Entrega - Sábado 17 de Maio de 2025 às 15 Brasil | 19H Angola/Portugal: https://events.teams.microsoft.com/event/d1d8a1fd-ad6c-4f38-925a-fddca9b04d1f@84c31ca0-ac3b-4eae-ad11-519d80233e6f
---

## 🧠 Objetivo do Desafio

Criar uma solução de ingestão, processamento e visualização de dados de **vagas de emprego em tempo real** ou **em lote**, com foco em:

- Localidade  
- Cargo  
- Empresa  
- Salário médio

A solução será mantida com **CI/CD utilizando GitHub ou Azure DevOps**, garantindo uma entrega contínua e confiável.

---
## 🏗️ Arquitetura do Projeto

![challenge](https://github.com/user-attachments/assets/bf3661ad-2307-441d-8a09-6a54349bb2aa)

---

## 🧱 Etapas do Projeto

### 1. Ingestão de Dados  
- **Fonte**: API do Indeed via RapidAPI  
- **Método**: `GET`  
- **Endpoint exemplo**: https://rapidapi.com/mantiks-mantiks-default/api/indeed12

### 2. Tratamento, Transformações e Armazenamento  
- **Ferramenta**: A critério de cada participante  
- **Exemplos de transformações**:
- Normalização de colunas: `título`, `empresa`, `localização`, `salário`, `descrição`
- Tratamento de valores nulos
- Conversão de datas
- Criação de colunas derivadas (ex: tipo de vaga, nível de senioridade)

### 3. Consultas SQL  
- Quais são os cargos mais ofertados no mercado?
- Quais empresas estão com mais vagas abertas?
- Qual é o salário médio por cargo?
- Em quais cidades ou estados há mais vagas disponíveis?
- Como está a tendência de publicação de vagas ao longo do tempo?
- Quais cargos oferecem salários acima da média geral?
- Quais vagas exigem experiência prévia e em qual nível?
- Quantas vagas são para trabalho remoto, híbrido ou presencial?
- Quais empresas oferecem os maiores salários?
- Quantas vagas foram publicadas na última semana?
- Qual a distribuição de vagas por setor ou área de atuação?
- Existem padrões de vagas por dia da semana?
- Qual a faixa salarial mais comum nas vagas?
- Há mais vagas para júnior, pleno ou sênior?
- Quais as tecnologias ou habilidades mais pedidas nas vagas?

### 4. Visualização no Power BI  

#### 📊 Dashboards:
- Total de vagas por localidade  
- Salário médio por função  
- Empresas que mais contratam  
- Tendência de vagas ao longo do tempo  

---

## 📈 Benefícios

- Experiência prática com Microsoft Fabric e Power BI
- Conhecimento aplicado em engenharia de dados e integração contínua
- Portfólio real para apresentar em entrevistas e redes profissionais
- Oferta simbólica para os 3 vencedores.

---

## 🤝 Contribuições

Sinta-se à vontade para abrir issues, enviar sugestões ou contribuir com este repositório!  
Vamos juntos elevar o nível da engenharia de dados com Microsoft Fabric.

---

