# Análise de Parcerias Públicas (MROSC) com NotebookLM: O Caso Pedregulho-SP 🏛️🤖

Este repositório apresenta o projeto final para o desafio da **DIO**, focado na utilização da Inteligência Artificial como ferramenta de aprendizagem ativa. O projeto utiliza o **Google NotebookLM** para realizar uma análise técnica e profunda de uma parceria real entre o poder público e o terceiro setor.

## 🎯 Contexto e Objetivos

Como **Analista de Planejamento** e estudante de **Gestão Pública**, escolhi analisar a parceria firmada entre o **Município de Pedregulho-SP** e o **Lar dos Velhinhos de Pedregulho**. 

**Objetivos de Estudo:**
- Analisar a estrutura do **Termo de Colaboração nº 003/2023** e seus aditamentos.
- Compreender a aplicação prática da **Lei Federal nº 13.019/2014 (MROSC)** na gestão municipal.
- Consolidar as metas, equipe de referência e o plano de aplicação de recursos para o exercício de 2025.

## 📚 Curadoria de Fontes

A base de conhecimento foi construída através do upload dos seguintes documentos oficiais no NotebookLM:

1.  **Termo de Colaboração nº 003/2023:** Estabelece o objeto e obrigações iniciais.
2.  **2º Termo de Rerratificação:** Documento que atualiza a vigência até 31/12/2025 e dotações orçamentárias.
3.  **Plano de Ação 2025 (Projeto Meu Lar):** Detalha a justificativa, objetivos e metas qualitativas.
4.  **Plano de Aplicação de Recursos 2025:** Detalhamento financeiro das fontes de receita e despesas.
5.  **Relatório de Atividades 2025:** Resultados obtidos, indicadores de desempenho e equipe técnica.

## 🧠 Engenharia de Prompts e "Cicatrizes"

### Engenharia de Prompts
Para obter uma análise de nível profissional, utilizei a técnica de **Persona** e **Saída Estruturada**:

> "Aja como um Especialista em Gestão Pública e Auditoria de Parcerias. Analise os documentos do Termo de Colaboração nº 003/2023 e elabore um Relatório Técnico Consolidado para a Comissão de Monitoramento e Avaliação. Organize em: Dados Estruturais, Execução Financeira 2025, Desempenho Operacional (Previsto vs. Realizado) e Impacto Social."

### Cicatrizes (Troubleshooting e Aprendizados)
- **Desafio de Versão:** Inicialmente, a IA misturou os valores de repasse de 2023 com os de 2025. **Correção:** Precisei especificar que o "2º Aditamento" e o "Plano de Aplicação 2025" eram as fontes prioritárias para dados vigentes.
- **Terminologia:** Foi necessário instruir a IA a utilizar os termos técnicos do SUAS (como ILPI e Alta Complexidade) em vez de termos genéricos como "asilo", garantindo rigor técnico ao material.

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados do Assunto
A parceria tem como objeto a manutenção de **Serviços de Acolhimento Institucional de Longa Permanência para Idosos (ILPI)**. 
- **Público Atendido:** Atendimento médio mensal de 24 a 26 idosos.
- **Equipe de Referência:** Profissionais celetistas e cedidos, incluindo Assistente Social, Psicólogo, Fisioterapeuta, Terapeuta Ocupacional, Cuidadores, Médicos e Dentistas.
- **Financiamento:** Estrutura mista composta por repasses Municipais (Pedregulho e Jeriquara), Estaduais, Federais, Recursos Próprios e contribuição de 70% do benefício previdenciário dos idosos.

### 2. Glossário de Conceitos Aprendidos
- **MROSC (Lei 13.019/2014):** Marco Regulatório das Organizações da Sociedade Civil que rege as parcerias públicas.
- **ILPI:** Instituição de Longa Permanência para Idosos; unidade de proteção social especial de alta complexidade.
- **Plano de Trabalho:** Instrumento que contém o diagnóstico, metas quantitativas, cronograma e indicadores de avaliação.
- **Termo de Colaboração:** Instrumento de parceria para projetos propostos pela Administração Pública que envolvam transferência de recursos financeiros.

### 3. Prompts Reutilizáveis para Revisão
- > *"Liste as metas quantitativas de 2025 e compare com os resultados apresentados no Relatório de Atividades de 2025."*
- > *"Sintetize as principais obrigações da OSC e do Município conforme a Cláusula Segunda e Terceira do Termo."*
- > *"Identifique no Plano de Aplicação quais despesas de 2025 são financiadas especificamente com repasse de recursos próprios da prefeitura e qual o valor dos repasses."*


---
**Projeto desenvolvido por:** Bruno
**Contexto:** Desafio de Projeto - Inteligência Artificial Aplicada ao Portfólio (DIO)
