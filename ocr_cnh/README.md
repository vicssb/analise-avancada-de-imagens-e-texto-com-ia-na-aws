<img src="./img/gif v1.gif" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador iuriCode">
<p>
  <div align="right"> 
<a href="./readme.md"> <img src="./img/LogoUK.png" alt="Logo UK" width="30"/></a><a href="./leiame.md"> <img src="./img/logoBrazil.png" alt="Logo Brasil" width="30"/> </a>
</div>
  <H1><b>OCR CNH</b> </H1>
  
</p> 

Project used to exemplify the use of [AWS Textract](https://docs.aws.amazon.com/pt_br/textract/latest/dg/API_AnalyzeDocument.html) in extracting data from the National Driver's License (CNH).

## Prerequisites

- Python
- Uv
- Conta AWS

## Environment configuration

You need to configure a user in IAM with access to the Textract service.

## Installation

To install the project dependencies use the command:

```sh
uv install
```

## Execution

```
uv run main.py
```
