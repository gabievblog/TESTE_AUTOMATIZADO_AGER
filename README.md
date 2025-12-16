# Teste Automatizado com Maestro Studio e Maestro CLI

Este repositório contém testes automatizados desenvolvidos com **Maestro Studio** e **Maestro CLI**, referentes ao projeto **AGER - STCRIP**.

## 📌 Estrutura do Projeto

- **teste_fiscalizcoes.yaml**
  Contém as variáveis de ambiente globais e o fluxo de teste. Esse arquivo que será testado via linha de comando.

- **flows/**  
  - **fiscalizacoes/**
    Contém os testes em `.yaml`.

- **reports/fiscalizacoes**
  - **.maestro/tests**
    Contém um arquivo `maestro.log` com o debug do teste e arquivos **json** e **html** como relatório dos testes.
  - **screenshots/**  
    Contém as evidências dos testes, incluindo **capturas de tela** e **vídeos** da execução.
  - **report.html**
    Arquivo em formato html com o relatório geral do teste.

## ▶️ Como rodar o teste

Abra o git na sua máquina e execute:

```
git clone https://github.com/gabievblog/TESTE_AUTOMATIZADO_AGER.git
```

No terminal da sua IDE, execute o seguinte comando:

```
maestro test teste_fiscalizacoes.yaml --format html ----debug-output TESTE_AUTOMATIZADO_AGER\reports\fiscalizacoes
```

**Observações**:

Caso queira salvar os arquivos de evidências em uma pasta específica, utilize o parâmetro **--output**:

```
maestro test teste_fiscalizacoes.yaml --format html ----debug-output TESTE_AUTOMATIZADO_AGER\reports\fiscalizacoes --output TESTE_AUTOMATIZADO_AGER\reports\fiscalizacoes\screenshots
```

Caso o arquivo não salve no caminho desejado copie e cole o arquivo dentro da pasta desejada na sua IDE.

## Feature Fiscaliza Stcrip

Contém as US para fazer os testes app no Maestro para fim de estudo:

https://dev.azure.com/Loglab/FABRICA%20-%20SQUAD%20-%20QA/_queries/edit/287367/?newQuery=true&parentId=94125b3c-aaf6-4dd8-8572-d14fb444a6c7
