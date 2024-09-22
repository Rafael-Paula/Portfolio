# Vedolim Teixeira & Advogados Associados 
Ano: 2024

## Descrição

Este projeto teve como objetivo processar **cerca de 1000 páginas de PDFs** de notificações fiscais relacionadas ao **recolhimento de Fundo de Garantia do Tempo de Serviço (FGTS)**. Os documentos eram judiciais e continham informações críticas que precisavam ser extraídas e organizadas de forma precisa.

O desafio era que muitas páginas dos PDFs estavam escaneadas (não digitais), o que causava erros na extração de dados. Além disso, havia a necessidade de aplicar correção monetária de acordo com os índices legais e garantir que os valores fossem exatos, como especificado nos arquivos judiciais.

## Desafio

Minha tarefa era realizar a **extração de dados** das páginas corretas dos PDFs, corrigir erros gerados pelo reconhecimento de texto de documentos escaneados, aplicar a correção monetária utilizando um índice específico, e garantir que os valores finais extraídos estivessem em conformidade com os valores indicados nos documentos originais.

Além disso, era necessário separar os documentos em **duas categorias** principais: **FGTS Mensal** e **FGTS Rescisório**, mantendo a rastreabilidade completa de cada arquivo.

## Ação

1. **Compreensão dos Arquivos Judiciais**:
   - Comecei o projeto lendo e entendendo os **termos jurídicos** e as **exigências processuais** dos arquivos judiciais. Isso me permitiu identificar quais páginas dos PDFs continham as informações necessárias para extração e aplicação das correções.

2. **Extração de Dados e Tratamento de Erros**:
   - Utilizei o **Adobe Acrobat** para extrair o texto e as tabelas dos PDFs. Como alguns documentos estavam escaneados, a extração inicial continha erros. Assim, foi necessário aplicar um processo de **ETL (Extração, Transformação e Carregamento)** utilizando **Excel** para padronizar os dados, corrigir formatações incorretas e preencher os campos vazios.

3. **Correção Monetária**:
   - Desenvolvi uma planilha para aplicar a **correção monetária** com base nos índices exigidos pelo processo. Automatizei o cálculo dentro do Excel para garantir que todos os documentos estavam atualizados corretamente.

4. **Verificação de Valores**:
   - Em seguida, realizei a **conferência dos valores** extraídos dos PDFs, comparando-os com os totais indicados nos documentos judiciais. Utilizei técnicas de estatística para garantir que não houvesse discrepâncias entre os valores originais e os extraídos.

5. **Classificação e Organização dos Arquivos**:
   - Separei os documentos em duas categorias: **FGTS Mensal** e **FGTS Rescisório**. Isso ajudou a manter a rastreabilidade e a transparência no processo de validação dos dados.

## Resultado

O projeto foi concluído com sucesso, atendendo às expectativas jurídicas e garantindo a **integridade dos dados** extraídos. Todos os documentos foram devidamente organizados e classificados, e não houve diferenças entre os valores esperados e os valores obtidos.

Além disso:
- **Rastreabilidade**: Cada arquivo pode ser rastreado até as páginas específicas do PDF de origem.
- **Correção Monetária**: Todos os valores foram ajustados corretamente de acordo com os índices exigidos.
- **Confiabilidade**: Todos os documentos conferidos apresentaram **zero diferença** entre os valores indicados e os valores finais.

---

## Estrutura do Projeto

### 1. Menu com Todos os Arquivos

Essa seção mostra a organização dos arquivos separados por categoria e número, facilitando a navegação e verificação dos documentos processados.

![Menu com Hiperlinks](https://github.com/Rafael-Paula/Portfolio/blob/main/Projeto%203%20-%20FGTS/1.png)

---

### 2. Planilha de FGTS Rescisório com Correção Monetária

Nesta planilha, foram organizados os arquivos da categoria **FGTS Rescisório**, aplicando a correção monetária de acordo com os índices estabelecidos.

![Planilha de FGTS Rescisório](https://github.com/Rafael-Paula/Portfolio/blob/main/Projeto%203%20-%20FGTS/2.png)

---

### 3. Comparação de Planilha e PDF com Páginas Utilizadas

Este arquivo faz referência às páginas específicas do PDF utilizadas para extração das informações, além de realizar uma comparação dos valores extraídos com os valores da planilha, garantindo a precisão dos dados.

![Comparação de Planilha e PDF](https://github.com/Rafael-Paula/Portfolio/blob/main/Projeto%203%20-%20FGTS/3.png)

---

## Habilidades Utilizadas

- **Adobe Acrobat**: Utilizado para a extração de texto e tabelas dos PDFs.
- **Excel**: Ferramenta principal para o processo de ETL, aplicando filtros, reconhecendo padrões de erro e automatizando a correção monetária.
- **Estatística**: Técnicas de conferência para verificação de valores e autenticidade dos documentos.





