# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto
Cap 3 - Classificação Automática de Variedades de Trigo

## Nome do grupo

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/lucas-lins-lima/">Lucas Lins</a> 

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/andregodoichiovato/">André Godoi Chiovato</a>


## 📜 Descrição

Este projeto implementa um sistema inteligente de classificação automática de grãos de trigo utilizando técnicas de Machine Learning. O objetivo é automatizar o processo tradicionalmente manual de classificação de grãos em cooperativas agrícolas, aumentando a eficiência, precisão e consistência das análises.

O projeto foi desenvolvido seguindo rigorosamente a metodologia CRISP-DM (Cross-Industry Standard Process for Data Mining), garantindo uma abordagem sistemática e profissional para o desenvolvimento de modelos de aprendizado de máquina.

## 🎯 Contexto e Motivação

**Problema Identificado:**
- 🔍 Classificação manual: Processo demorado e sujeito a erros humanos
- ⏱️ Ineficiência: Reduz a velocidade de processamento nas cooperativas
- 📊 Inconsistência: Variabilidade entre diferentes especialistas
- 💰 Custo elevado: Necessidade de especialistas para análise manual

**Solução Proposta:**
- 🤖 Automação completa do processo de classificação
- 🎯 Alta precisão na identificação de variedades de trigo
- ⚡ Processamento rápido de grandes volumes de grãos
- 📈 Escalabilidade para diferentes cooperativas e regiões

## 🔬 Metodologia CRISP-DM
O projeto segue as 6 fases da metodologia CRISP-DM:

**1. 📊 Business Understanding (Entendimento do Negócio)**
- Definição clara dos objetivos de negócio
- Identificação dos critérios de sucesso
- Análise dos requisitos e restrições

**2. 📈 Data Understanding (Entendimento dos Dados)**
- Coleta e exploração do dataset Seeds
- Análise estatística descritiva
- Identificação de padrões e correlações

**3. 🔧 Data Preparation (Preparação dos Dados)**
- Limpeza e tratamento de dados
- Normalização e padronização
- Divisão estratificada treino/teste

**4. 🤖 Modeling (Modelagem)**
- Implementação de 5 algoritmos diferentes
- Treinamento e validação cruzada
- Comparação de performance

**5. ⚡ Evaluation (Avaliação)**
- Otimização de hiperparâmetros
- Análise detalhada de métricas
- Interpretação dos resultados

**6. 🚀 Deployment (Implementação)**
- Documentação completa
- Recomendações para produção
- Plano de monitoramento

## 📊 Dataset Utilizado

**Seeds Dataset - UCI Machine Learning Repository**
- 📦 Total de amostras: 210 grãos de trigo
- 🏷️ Classes: 3 variedades (Kama, Rosa, Canadian)
- 📏 Características: 7 medições geométricas por grão
- 🎯 Distribuição: Balanceada entre as classes

**Características Analisadas:**
1. Área: Medida da área total do grão
2. Perímetro: Comprimento do contorno do grão
3. Compacidade: Regularidade da forma (4πA/P²)
4. Comprimento do Núcleo: Eixo principal da elipse equivalente
5. Largura do Núcleo: Eixo secundário da elipse
6. Coeficiente de Assimetria: Medida de irregularidade
7. Comprimento do Sulco: Característica única do grão

## 🤖 Algoritmos Implementados
O projeto compara 5 algoritmos de classificação diferentes:
```
Algoritmo | Tipo | Principais Características
🔍 K-Nearest Neighbors (KNN) | Instance-based | Simples, baseado em proximidade
⚡ Support Vector Machine (SVM) | Kernel-based | Eficaz em alta dimensionalidade
🌳 Random Forest | Ensemble | Robusto, fornece importância das features
📊 Naive Bayes | Probabilístico | Rápido, assume independência das features
📈 Logistic Regression | Linear | Interpretável, fornece probabilidades
```
## 📊 Métricas de Performance:
```
Métrica | Valor | Interpretação
Acurácia | >90% | ✅ Objetivo alcançado
Precisão | >90% | ✅ Poucos falsos positivos
Recall | >90% | ✅ Poucos falsos negativos
F1-Score | >90% | ✅ Métricas balanceadas
```
## 🎯 Características Mais Importantes:

1. Área do grão - Principal diferenciador
2. Perímetro - Correlacionado com o tamanho
3. Compacidade - Indica formato específico

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>.github</b>: Nesta pasta ficarão os arquivos de configuração específicos do GitHub que ajudam a gerenciar e automatizar processos no repositório.

- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

- <b>config</b>: Posicione aqui arquivos de configuração que são usados para definir parâmetros e ajustes do projeto.

- <b>document</b>: aqui estão todos os documentos do projeto que as atividades poderão pedir. Na subpasta "other", adicione documentos complementares e menos importantes.

- <b>scripts</b>: Posicione aqui scripts auxiliares para tarefas específicas do seu projeto. Exemplo: deploy, migrações de banco de dados, backups.

- <b>src</b>: Todo o código fonte criado para o desenvolvimento do projeto ao longo das 7 fases.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

Para visualizar e executar este projeto, siga as instruções abaixo:

**Pré-requisitos**
- Python 3.10+
- Jupyter Notebook ou ambiente compatível (instalado via pip install notebook ou por ferramentas como Anaconda)
- Instale as bibliotecas necessárias (pandas numpy scikit-learn matplotlib seaborn)

**Passo a passo para verificar a execução do projeto**
1. Clone o repositório ou baixe o arquivo .zip pelo próprio GitHub e extraia no seu computador.
```bash
git clone https://github.com/lucas-lins-lima/FIAP_F4_CAP3.git
```
2. Acesse a pasta dos scripts
```bash
cd FIAP_F4_CAP3
```
3. Inicie o Jupyter Notebook
```bash
jupyter notebook
```
4. Abre a e execute as células do notebook em sequência para acompanhar todas as análises, resultados e gráficos gerados.

**Passo a passo para a visualização online**
1. Acesse: nbviewer.jupyter.org 
2. Cole o link direto do notebook document/Resolucao.ipynb hospedado no GitHub 
3. Visualize o conteúdo renderizado diretamente no navegador.

## 🗃 Histórico de lançamentos

* 0.1.0 - 20/06/2025
    * Preparação e conclusão da atividade
        
## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>


