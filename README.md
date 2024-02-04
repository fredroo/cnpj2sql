# cnpj2sql

Scripts PHP para download da base de dados do CNPJ da receita federal e conversão em arquivos SQL para importação em banco de dados MySQL.

Esse projeto visa fazer o download da base da dados de CNPJ da receita federal diretamente através do portal dados abertos, utilizando o wget na função mirror.
Após o download será feita a descompactação dos arquivos zip, seguidos alteração da codificação de caracteres para UTF8.
Um Script PHP (cli) será usado para montar os arquivos SQL a partir dos arquivos CSV.

## Por que PHP?

Optei por usar PHP no modo command line interface (cli) visto que não é uma linguagem fortemente tipada e facilita a conversão de dados necessária para o formato banco de dados proposto aqui.

# Como usar

```bash
./download_cnpj.sh
```

```bash
./converter_cnpj.sh
```

# Requisitos

- wget2
- unzip
- php-cli

## Licença GNU GPL v3

Você pode fazer quase qualquer coisa que você queira com esse projeto, exceto distribuir o código fonte em projetos de código fechado.

## Dúuvidas sobre o projeto

O projeto foi desenvolvido para fins de estudo e prova de conceito. O projeto está disponibilizado como está, sem garantias de funcionamento. Devido ao meu tempo limitado e compromisso com outros projetos somente poderei prestar qualquer tipo de auxilio mediante compensação financeira, caso seja de seu interesse entrar em contato [via telegram](https://t.me/r3n4t0), somente tenho condições de responder texto e não sou capaz ouvir mensagens de áudio.

## Contribuições

### Com o código

Se você quiser contribuir com o código, você pode fazer um fork do projeto e enviar um pull request.

### Financeiras

Se esse projeto te auxiliou de alguma forma, você pode contribuir financeiramente para que eu possa continuar a desenvolver projetos open source. As contribuições podem ser:

# PIX:
    b230c7a8-8743-459f-bae5-541ea46a3533

![302100763-dc530122-d9fb-41e4-9edf-dc9c32e74adc](https://github.com/fredroo/cnpj2sql/assets/6863089/1a6505e5-5039-4609-87af-ba84f03d4b08)

