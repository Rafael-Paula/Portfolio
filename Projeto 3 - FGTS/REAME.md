# Projeto: Reconhecimento de PDF e Processamento de Notificações Fiscais

## Descrição do Projeto

Este projeto envolveu o reconhecimento e processamento de aproximadamente **1000 páginas de PDFs** de notificações fiscais relacionadas ao **recolhimento de Fundo de Garantia do Tempo de Serviço (FGTS)**. O objetivo foi extrair e organizar as informações desses documentos, separando-os em categorias mensais e rescisórias, garantindo a rastreabilidade e a verificação de valores.

## Processo e Soluções Implementadas

### 1. Extração de Texto e Tabelas dos PDFs

A extração dos dados foi realizada com o **Adobe Acrobat**, sendo que alguns dos documentos estavam em formato escaneado e não digital. Isso causou erros em partes específicas dos PDFs, exigindo um processo minucioso de reconhecimento e correção dos dados.

### 2. Processo de ETL (Extração, Transformação e Carga)

Como muitas páginas continham erros devido ao reconhecimento incorreto de texto, foi necessário realizar um **processo de ETL (Extract, Transform, Load)**, que consistiu nos seguintes passos:

- **Extração de texto**: Todos os dados dos PDFs foram extraídos e convertidos para o formato **Excel**, permitindo uma análise mais detalhada.
- **Reconhecimento de padrões de erro**: O conteúdo extraído foi analisado e padronizado, identificando inconsistências e problemas de formatação.
- **Filtragem e correção de dados**: As informações foram filtradas por colunas para identificar e corrigir itens com formatação inconsistente ou dados incorretos, ajustando os erros no processo.

### 3. Correção Monetária e Índices

Foi desenvolvida uma planilha específica para aplicar a **correção monetária** com base em um índice solicitado no processo. Esse cálculo foi feito de forma automatizada, utilizando **Excel** para aplicar os índices aos valores corretos.

### 4. Verificação de Valores

Cada documento continha os **valores totais** que deveriam ser conferidos. Utilizando técnicas de estatística, foi realizada a checagem automática dos valores extraídos contra os totais presentes nos PDFs, garantindo a precisão dos dados.

### 5. Classificação dos Documentos

Os documentos foram divididos em duas categorias principais:
- **FGTS Mensal**
- **FGTS Rescisório**

Essa separação permitiu a rastreabilidade completa dos documentos e a conferência da autenticidade das informações.

### 6. Resultados Finais

Ao final do processo, todos os documentos foram organizados e conferidos, sem qualquer diferença entre os valores extraídos e os valores esperados. Isso garantiu a confiabilidade e a rastreabilidade de todas as informações processadas.

---

## Estrutura do Projeto

### 1. Menu com Todos os Arquivos

Essa seção mostra a organização dos arquivos separados por categoria e número, facilitando a navegação e verificação dos documentos processados.

![Menu com Hiperlinks](./path-to-images/1.png)

---

### 2. Planilha de FGTS Rescisório com Correção Monetária

Nesta planilha, foram organizados os arquivos da categoria **FGTS Rescisório**, aplicando a correção monetária de acordo com os índices estabelecidos.

![Planilha de FGTS Rescisório](./path-to-images/2.png)

---

### 3. Comparação de Planilha e PDF com Páginas Utilizadas

Este arquivo faz referência às páginas específicas do PDF utilizadas para extração das informações, além de realizar uma comparação dos valores extraídos com os valores da planilha, garantindo a precisão dos dados.

![Comparação de Planilha e PDF](./path-to-images/3.png)

---

## Tecnologias Utilizadas

- **Adobe Acrobat**: Utilizado para a extração de texto e tabelas dos PDFs.
- **Excel**: Ferramenta principal para o processo de ETL, aplicando filtros, reconhecendo padrões de erro e automatizando a correção monetária.
- **Estatística**: Técnicas de conferência para verificação de valores e autenticidade dos documentos.

---

## Conclusão

Este projeto automatizou a extração e o processamento de um grande volume de documentos fiscais, garantindo a integridade dos dados e a rastreabilidade completa de todas as informações. O uso de técnicas avançadas de reconhecimento de padrões e conferência de valores assegurou a precisão dos resultados, permitindo que o projeto fosse concluído sem discrepâncias.


