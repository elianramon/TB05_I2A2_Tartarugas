
# 🐢 Projeto Guardião das Tartaruguinhas

O **Guardião das Tartaruguinhas** é uma ferramenta de suporte à tomada de decisão desenvolvida em Python para grupos de monitoramento ambiental. O sistema permite que voluntários organizem e analisem dados sobre ninhos de tartarugas marinhas, auxiliando na preservação das espécies através de dados precisos e estatísticas semanais.

## 📋 Funcionalidades

O sistema foi projetado para operar de forma interativa e robusta, oferecendo:

1. **Registro de Ninhos:** Cadastro de informações geográficas, quantitativas e de segurança.
2. **Monitoramento de Risco:** Classificação visual por níveis de criticidade (🟢, 🟡, 🔴).
3. **Relatórios Semanais:** Visualização tabular de todos os ninhos ativos.
4. **Análise Estatística:** * Cálculo de média de ovos em áreas críticas.
* Identificação de ninhos próximos à eclosão (janela de 5 dias).
* Mapeamento de regiões com maior incidência de risco.
* Cruzamento de dados entre presença de predadores e danos físicos.



## 🛠️ Tecnologias e Conceitos Aplicados

Este projeto utiliza conceitos fundamentais de programação e ciência de dados:

* **Estruturas de Dados:** Listas compostas e dicionários para armazenamento eficiente.
* **Modularização:** Funções específicas para validação, cálculos e interface.
* **Lógica de Programação:** Estruturas de repetição (`while`), condicionais e tratamento de erros (`try-except`).
* **Validação de Dados:** Garantia de integridade para entradas numéricas e categorias pré-definidas.

## 🚀 Como Executar

O programa foi otimizado para rodar em ambientes **Jupyter Notebook** ou em qualquer terminal Python (versão 3.x).

1. Clone este repositório ou copie o código fonte.
2. Certifique-se de ter o Python instalado.
3. Execute a célula do notebook ou o arquivo `.py`.
4. Utilize o menu interativo para navegar entre as opções:
* **Opção 1:** Adiciona novos dados à base.
* **Opção 2:** Gera a tabela de monitoramento.
* **Opção 3:** Exibe os insights e alertas de risco.
* **Opção 4:** Encerra o programa com segurança.



## 📊 Regras de Negócio e Validação

Para manter a qualidade dos dados coletados pelos voluntários, o sistema impede:

* Entrada de quantidade de ovos ou dias de eclosão negativos.
* Inserção de status fora dos padrões: `intacto`, `ameaçado` ou `danificado`.
* Uso de indicadores de risco diferentes dos emojis padronizados (🟢 Baixo, 🟡 Médio, 🔴 Alto).

---
