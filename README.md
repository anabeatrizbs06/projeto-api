# API de Upload e Download de Arquivos

## Sobre o projeto

Esta API foi desenvolvida em Python utilizando Flask e SQLite. Seu objetivo é permitir o envio e o download de arquivos por meio de requisições HTTP.

## Tecnologias utilizadas

- Python
- Flask
- SQLite
- Werkzeug

## Funcionalidades

- Upload de arquivos.
- Download de arquivos.
- Validação dos tipos de arquivos permitidos.
- Limitação do tamanho dos arquivos.
- Registro de informações em logs.
- Armazenamento dos dados no banco SQLite.

## Tipos de arquivos permitidos

- PNG
- JPG
- JPEG
- GIF
- PDF
- TXT

## Como executar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/anabeatrizbs06/projeto-ad.git
```

2. Entre na pasta do projeto:

```bash
cd projeto-ad
```

3. Instale o Flask:

```bash
pip install flask
```

4. Execute a aplicação:

```bash
python app.py
```

A API estará disponível localmente em:

`http://127.0.0.1:5000`

## Rotas

| Método | Rota | Função |
|---|---|---|
| POST | /uploads/upload | Enviar arquivos |
| GET | /downloads/... | Download de arquivos |

## Banco de dados

O projeto utiliza SQLite para armazenar informações sobre os arquivos enviados.

## Autoria

Projeto desenvolvido como atividade acadêmica.
