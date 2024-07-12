# Editor de Metadados de Arquivos MP3

Este projeto permite a leitura e edição de metadados em arquivos .mp3. Utilizando a biblioteca `eyed3`, o script permite modificar informações como autor, intérprete, título, gênero e comentários dos arquivos de música.

## Funcionalidades

- **Carregar Trilhas**: Carrega todos os arquivos .mp3 de um diretório especificado.
- **Exibir DataFrame**: Exibe os metadados dos arquivos .mp3 em um formato de tabela.
- **Alterar Metadados**: Permite alterar metadados individuais ou em lote.
- **Interface Interativa**: GUI básica para interação com o usuário.

## Pré-requisitos

Certifique-se de ter Python instalado em sua máquina. Além disso, as seguintes bibliotecas são necessárias:

- `eyed3`
- `pandas`
- `tabulate`

Para instalar as dependências, execute:

```sh
pip install eyed3 pandas tabulate
