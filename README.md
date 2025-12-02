![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF7C00?style=for-the-badge&logo=streamlitlogoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

# MAS (Sistema Multiagente) para Processo de Adoção no Brasil

O sistema MAS é estruturado para suportar consultas e resolução de demandas complexas no contexto da adoção, reunindo agentes especializados, supervisão inteligente e integração de fontes diversas para garantir robustez, transparência e adaptabilidade.


## Agente Jurídico:
- Especialista no ECA (Estatuto da Criança e Adolescente), leis de adoção e regulamentações correlatas
- Explica procedimentos legais, prazos, direitos e deveres
- Fornece informações sobre habilitação, destituição do poder familiar e aspectos processuais
- Sempre indica que a resposta não substitui consulta jurídica profissional

## Agente Psicossocial:
- Foco no perfil da criança/adolescente e preparação psicológica
- Trabalha questões de tempo de espera vs. perfil desejado
- Orienta sobre estágio de convivência e adaptação familiar
- Aborda aspectos emocionais e de vínculo

## Agente de Processos (Burocrático):
- Consulta status simulado no SNA (Sistema Nacional de Adoção)
- Lista documentos necessários e etapas do processo
- Explica fluxos administrativos e prazos processuais
- Orienta sobre cadastro e movimentação no sistema

## Agente Conversacional:
- Especialista em engajamento sobre o processo de adoção brasileiro
- Lida com conversas introdutórias, acolhimento e orientação geral
- Encaminha para agentes especializados quando necessário
- Fornece suporte emocional inicial

## Agente Supervisor XAI (Explicável):
- Monitora todos os outros agentes, coletando logs, resultados e consultas
- Analisa padrões de delegação e desempenho do sistema
- Gera explicações transparentes sobre decisões do sistema
- Fornece relatórios sobre o funcionamento holístico do MAS


## Architecture

![agent_architecture]([MAS ADOCAO.drawio.png](https://github.com/fariaswladimir/adoption_MAS/blob/f35bb91a56ecf0a34b1b0843d9e5df6bcf0b028f/MAS%20ADOCAO.drawio.png))

UI -> prompt -> API -> Supervisor -> [Legal, XAI,Process Psycossocial Conversational] -> API -> UI

## Stack used

TODO: Explain the stack used

Pydantic_ai, Logfire, Streamlit, Chromadb, Fastapi, HuggingFace[Transformers]
