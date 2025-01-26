<img src="./img/gif v1.gif" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador iuriCode">
<p>
  <div align="right"> 
<a href="./readme.md"> <img src="./img/LogoUK.png" alt="Logo UK" width="30"/></a><a href="./leiame.md"> <img src="./img/logoBrazil.png" alt="Logo Brasil" width="30"/> </a>
</div>
  <H1><b>OCR CNH</b> </H1>
  
</p> 

Projeto usado para exemplificar o uso do [AWS Textract](https://docs.aws.amazon.com/pt_br/textract/latest/dg/API_AnalyzeDocument.html) na extração de dados da Carteira Nacional de Trânsito (CNH).

## Pré requisitos

- Python
- Uv
- Conta AWS

## Configuração do ambiente

É necessário configurar um usuário no IAM com acesso ao serviço Textract.

## Instalação

Para instalar as dependências do projeto utilize o comando:

```sh
uv install
```

## Execução

```
uv run main.py
```
