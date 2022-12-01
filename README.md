<p align="center">
  <h1 align="center">:zap: Gerador de CNPJs</h2>
  <p align="center">Projeto gerador CNPJs válidos com Python, gerados em um CSV</p>
</p>

## Como gerar um novo arquivo
No terminal, entre na pasta do projeto e execute o comando 
```bash
python3 gerador.py
```
## Parâmetros
Para maiores informações, execute:
```bash
python3 gerador.py -h
```

Após a execução do comando acima, você observará o seguinte resultado em sua linha de comando:
```
usage: gerador.py [-h] [-i INITIAL_CNPJ] [-q QUANTITY] [-o OUTPUT_PATH] [-s SEP_CSV]

Projeto gerador CNPJs válidos salvos em formato CSV.

options:
  -h, --help            show this help message and exit
  -i INITIAL_CNPJ, --initial_cnpj INITIAL_CNPJ
                        8 primeiros dígitos do CNPJ a ser gerado, esse é o valor que será incrementado, caso precise fazer outra
                        sequência basta trocar esse valor.
  -q QUANTITY, --quantity QUANTITY
                        Quantidade de CNPJs a serem gerado.
  -o OUTPUT_PATH, --output_path OUTPUT_PATH
                        Diretório onde será gerado o arquivo.
  -s SEP_CSV, --sep_csv SEP_CSV
                        Caractere de separação entre as colunas do `.csv`.
```
## :pushpin: Licença
[MIT License](/LICENSE) <br>
