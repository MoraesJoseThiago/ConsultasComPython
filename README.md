# Ferramenta de Verificação de Site

Esta é uma ferramenta simples em Python para verificar informações sobre um site, incluindo o banner, o IP associado a um host e se um site existe.

## Requisitos

- Python 3.x

## Como usar

1. Clone o repositório ou faça o download do arquivo.
2. Abra um terminal ou prompt de comando.
3. Navegue até o diretório onde o script está localizado.
4. Execute o script usando o comando `python script.py`.

## Funcionalidades

### 1. Verificar o BANNER do site

- Solicita ao usuário um IP e uma porta.
- Conecta-se ao IP e porta especificados e exibe o banner recebido.

### 2. Verificar o IP de um site

- Solicita ao usuário um host (sem HTTP).
- Obtém e exibe o endereço IP associado ao host.

### 3. Verificar se o SITE existe

- Solicita ao usuário um site (com HTTP).
- Realiza uma requisição HTTP para verificar a existência do site e exibe informações do servidor, se existir.

## Cores no Terminal

O script utiliza códigos ANSI para cores no terminal, proporcionando uma experiência visual agradável.

- `Colors.HEADER`: Cabeçalho.
- `Colors.OKBLUE`: Informações.
- `Colors.OKGREEN`: Sucesso.
- `Colors.WARNING`: Aviso.
- `Colors.FAIL`: Falha.
- `Colors.ENDC`: Fim de cor.
- `Colors.YELLOW`: Amarelo para destaque.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar solicitações de pull.
