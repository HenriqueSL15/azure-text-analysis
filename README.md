# Análise de Texto com Serviços Azure AI

## Objetivo  
Demonstrar como os serviços de IA da Azure (como Análise de Sentimentos, Tradução e Reconhecimento de Entidades) podem processar textos em diferentes cenários.

## Frases Analisadas  
As frases estão no arquivo [sentencas.txt](/inputs/sentencas.txt).

## Resultados Teóricos (Baseados no Conteúdo do Curso)  
- **Frase 1**:  
  - *Serviço da Azure*: Tradução de Texto  
  - *Resultado Esperado*: A frase seria traduzida para o idioma configurado mantendo termos técnicos sem perda de contexto.  

- **Frase 2**:  
  - *Serviço da Azure*: Análise de Sentimentos  
  - *Resultado Esperado*: Sentimento negativo detectado com alta confiança (ex: score 0.8+ para "frustração" e "delay").  

- **Frase 3**:  
  - *Serviço da Azure*: Reconhecimento de Entidades  
  - *Resultado Esperado*: Identificação de entidades como `Localização (Paris)`, `Data (2023)`, `Tecnologia (IA Generativa)`.  

## Insights e Aprendizados  
- A **Análise de Sentimentos** é útil para interpretar feedbacks de usuários automaticamente, mas depende do contexto das palavras (ex: "delay" influencia negativamente).  
- O **Reconhecimento de Entidades** pode extrair metadados de documentos, facilitando a organização de dados.  
- A integração desses serviços com APIs (ex: Python) permite automação de tarefas como análise de reviews ou relatórios.  

## Possibilidades Futuras  
- Criar um sistema de suporte ao cliente que priorize tickets com sentimentos negativos.  
- Desenvolver um tradutor automático para documentos técnicos usando a API de Tradução.  
