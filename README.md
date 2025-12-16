# Teste Automatizado com Maestro Studio e Maestro CLI

Este repositório contém testes automatizados desenvolvidos com **Maestro Studio** e **Maestro CLI**, referentes ao projeto **AGER - STCRIP**.

## 📌 Estrutura do Projeto

- **reports/**  
  Contém os relatórios em formato **HTML** dos testes realizados.

- **screenshots/**  
  Contém as evidências dos testes, incluindo **capturas de tela** e **vídeos** da execução.

- **Arquivos `.yaml`**  
  São os arquivos responsáveis pela definição dos testes automatizados.

## ▶️ Como rodar o teste

No terminal da sua IDE, execute o seguinte comando:

```
maestro test login.yaml fiscalizaInicio.yaml cadastroVeiculos.yaml --format html
```

Observações:
Após definir o formato do relatório (--format html), é possível informar o caminho onde os arquivos serão salvos.

Caso queira salvar os arquivos de evidências em uma pasta específica, utilize o parâmetro --output:

```
maestro test login.yaml fiscalizaInicio.yaml cadastroVeiculos.yaml --format html --output pastaComMeusTestes/
```
