# 🐍 Guia de Bibliotecas e Frameworks Python

Este arquivo reúne anotações, descrições e principais casos de uso das bibliotecas mais relevantes do ecossistema Python para análise de dados, IA, automação, desenvolvimento web e processamento de documentos.

---

## 📌 Sumário de Navegação
* [1. Análise e Manipulação de Dados](#1-análise-e-manipulação-de-dados)
* [2. Inteligência Artificial e LLMs](#2-inteligência-artificial-e-llms)
* [3. Automação e RPA (Web Scraping)](#3-automação-e-rpa-web-scraping)
* [4. Desenvolvimento Web](#4-desenvolvimento-web)
* [5. Visualização de Dados](#5-visualização-de-dados)
* [6. Leitura e Processamento de Documentos](#6-leitura-e-processamento-de-documentos)
* [7. OCR (Reconhecimento de Texto)](#7-ocr-reconhecimento-de-texto)
* [8. Processamento Assíncrono](#8-processamento-assíncrono)
* [9. Arquitetura e Padronização](#9-arquitetura-e-padronização)
* [📌 Tech Stack Essencial do Projeto](#-tech-stack-essencial-do-projeto)

---

## 1. Análise e Manipulação de Dados

### 🐼 Pandas
Biblioteca para manipulação e análise de dados estruturados em formato de tabelas (DataFrames).
*   **Principais usos:**
    *   Ler arquivos CSV e Excel.
    *   Filtrar, organizar e limpar dados.
    *   Agrupar informações e gerar relatórios.
    *   Integração e trabalho com bancos de dados.

### 🔢 NumPy
Biblioteca fundamental para computação numérica de alta performance. É a base de diversas ferramentas como Pandas, Scikit-Learn e TensorFlow.
*   **Principais usos:**
    *   Manipulação de matrizes e vetores multidimensionais.
    *   Operações de álgebra linear e estatística computacional.

### 🐻‍❄️ Polars
Biblioteca semelhante ao Pandas, porém construída em Rust e focada em extrema velocidade e eficiência para grandes conjuntos de dados.
*   **Principais usos:**
    *   Processamento ultra-rápido de grandes planilhas.
    *   Manipulação eficiente de milhões de registros.

### ⚡ PySpark
Interface Python para o Apache Spark, voltada para processamento massivo de dados em larga escala.
*   **Principais usos:**
    *   Ecossistemas de Big Data.
    *   Processamento distribuído e computação em cluster.

### 📊 OpenPyXL
Biblioteca focada especificamente na manipulação direta e customização de arquivos Excel (`.xlsx`).
*   **Principais usos:**
    *   Criar, alterar células e inserir fórmulas em planilhas de forma programática.
    *   Aplicar estilos, cores e automatizar relatórios corporativos.

---

## 2. Inteligência Artificial e LLMs

### 🤖 Scikit-Learn
A principal biblioteca para Machine Learning tradicional e análise preditiva.
*   **Principais algoritmos:** Regressão, Classificação, Clusterização, Árvores de Decisão, Random Forest, SVM e KNN.

### 🧠 TensorFlow
Framework robusto desenvolvido pelo Google focado em Deep Learning e redes neurais complexas.
*   **Principais usos:** Visão computacional, processamento de linguagem natural (NLP), reconhecimento de imagens e IA Generativa.

### 🔥 PyTorch
Framework de Deep Learning desenvolvido pela Meta. Altamente dinâmico, intuitivo e o mais utilizado atualmente no ambiente de pesquisa.
*   **Principais usos:** Redes neurais estruturadas, modelos de linguagem avançados (LLMs), Chatbots e visão computacional.

### 🦜🔗 LangChain
Framework voltado para a construção e orquestração de aplicações baseadas em Grandes Modelos de Linguagem (LLMs).
*   **Principais recursos:** Criação de agentes inteligentes, chatbots com memória de contexto, busca semântica em documentos e integração simplificada com APIs de IA (como OpenAI).

### 🤗 Hugging Face
Plataforma central e ecossistema de bibliotecas que funciona como o "GitHub da Inteligência Artificial", disponibilizando milhares de modelos prontos.
*   **Possui modelos para:** Tradução, resumo textual, classificação, geração de código, chatbots e visão computacional.

### 🔌 OpenAI API
Serviço em nuvem que disponibiliza os modelos generativos de ponta da OpenAI (como a linha GPT) via requisições diretas.
*   **Principais usos:** Automação de tarefas intelectuais, extração inteligente de dados em relatórios, resumos e conversações contextuais.

---

## 3. Automação e RPA (Web Scraping)

### 🌐 Requests
Biblioteca padrão de mercado para realizar requisições HTTP de forma simples e intuitiva.
*   **Principais usos:** Consumo de APIs REST, downloads de arquivos e comunicação entre microsserviços.

### 🥣 BeautifulSoup
Biblioteca focada na interpretação e extração de dados estruturados a partir de arquivos HTML e XML.
*   **Principais usos:** Web Scraping tradicional, varredura e raspagem de textos, tabelas, links e imagens de páginas estáticas.

### 🎭 Playwright
Framework moderno e poderoso para automação e testes de navegadores web (Chromium, Firefox, WebKit).
*   **Permite:** Simular interações humanas completas (fazer login, preencher formulários complexos, lidar com SPAs, capturar telas e automatizar fluxos de RPA).

### 🤖 Selenium
O framework mais tradicional do mercado para automação web e testes ponta a ponta (E2E). Muito utilizado na manutenção de sistemas legados e esteiras estáveis de RPA.

### 🖱️ PyAutoGUI
Biblioteca para automação da interface gráfica (GUI) do sistema operacional.
*   **Permite:** Controlar o mouse (movimentos e cliques) e teclado de forma física. Ideal para automatizar programas de desktop que não possuem APIs ou interfaces web.

---

## 4. Desenvolvimento Web

### 💚 Django
Framework Web Full Stack completo ("com baterias inclusas"). Fornece toda a estrutura necessária para construir sistemas robustos e seguros rapidamente.
*   **Possui de forma nativa:** ORM, sistema de autenticação/usuários, painel administrativo pronto, camadas de segurança, controle de migrações e renderização de templates.

### 🌶️ Flask
Microframework minimalista, leve e modular. Entrega apenas o essencial, dando total liberdade para o desenvolvedor escolher suas ferramentas e arquitetura.
*   **Ideal para:** APIs pequenas, microsserviços e protótipos ágeis.

### 🚀 FastAPI
Framework moderno de altíssimo desempenho para a construção de APIs REST, totalmente assíncrono e baseado em tipagem padrão do Python.
*   **Características:** Geração automática de documentação interativa (Swagger/ReDoc), validação de tipos nativa e performance comparável a Go e Node.js.

---

## 5. Visualização de Dados

### 📉 Matplotlib
A biblioteca mais tradicional e personalizável para geração de gráficos estáticos em Python (Linha, barras, pizza, dispersão, histogramas). Serve de alicerce para quase todas as ferramentas de plotagem.

### 🌊 Seaborn
Interface de alto nível construída sobre o Matplotlib, focada em visualizações estatísticas atraentes e elegantes com pouquíssimas linhas de código.

### 📊 Plotly
Biblioteca focada em gráficos altamente interativos e responsivos para o usuário final (suporta zoom, hover detalhado, filtros dinâmicos e renderizações em 3D).

### 🎈 Streamlit
Framework que transforma scripts Python estruturados em aplicações e dashboards web interativos em minutos, sem exigir conhecimentos em HTML, CSS ou JavaScript.

---

## 6. Leitura e Processamento de Documentos

### 📄 PyMuPDF (`fitz`)
Biblioteca extremamente veloz para leitura, extração e modificação estrutural de arquivos PDF.
*   **Principais usos:** Extração limpa de blocos de texto e imagens, localização posicional de termos na página, divisão (`split`) e união (`merge`) de documentos.

### 📊 pdfplumber
Biblioteca especializada na análise de geometria interna de arquivos PDF digitais.
*   **Grande diferencial:** Excelente capacidade para identificar linhas, colunas e converter tabelas complexas diretamente em DataFrames do Pandas.

### 📝 python-docx
Biblioteca voltada para a criação, leitura e manipulação direta de arquivos do Microsoft Word (`.docx`).
*   **Principais usos:** Automatizar a geração de relatórios contratuais, preencher modelos de documentos (`templates`) e ler metadados.

---

## 7. OCR (Reconhecimento de Texto)

> 💡 **Nota:** O OCR (Optical Character Recognition) é a tecnologia usada para transformar imagens ou arquivos escaneados (sem texto selecionável) em strings editáveis pelo sistema.

### 🔍 EasyOCR
Biblioteca de OCR pronta para uso imediato baseada em modelos de Deep Learning. Possui curva de aprendizado baixa e excelente precisão em múltiplos idiomas nativamente.

### 🇨🇳 PaddleOCR
Ferramenta de OCR de última geração desenvolvida pela Baidu. Altamente performática e precisa, sendo uma das melhores opções atuais para ler layouts difíceis, tabelas escaneadas e formulários complexos.

---

## 8. Processamento Assíncrono

### 🥦 Celery
Distribuidor de tarefas assíncronas (`Task Queue`) focado na execução de rotinas pesadas em segundo plano.
*   **Casos de uso:** Rodar scripts de OCR, processar uploads de grandes volumes de documentos, disparar e-mails em massa e gerar planilhas sem travar a requisição principal do usuário.

### 💾 Redis
Armazenamento de estrutura de dados em memória, utilizado principalmente como um intermediador de mensagens ultra-rápido (`Message Broker`).
*   **Casos de uso:** Funciona como a fila/mensageria principal do Celery, além de servir para gerenciamento de cache da aplicação e controle de sessões.

---

## 9. Arquitetura e Padronização

### 🛠️ Pydantic
Biblioteca para validação de dados e gerenciamento de configurações baseada em tipagem estática.
*   **Principais usos:** Garantir a consistência de payloads JSON recebidos por APIs, estruturar e validar as respostas vindas de modelos de IA (forçando formatos rígidos) e converter objetos complexos em tipos primitivos do Python com segurança.

#### 🔀 Exemplo de Payload Estruturado (JSON) para IA:
```json
{
    "empresa": "Nome da Empresa LTDA",
    "cnpj": "00.000.000/0001-00",
    "item": "Notebook Pro",
    "quantidade": 2,
    "valor_unitario": 4500.00,
    "valor_total": 9000.00
}
