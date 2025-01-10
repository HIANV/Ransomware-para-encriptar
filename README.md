# Ransomware-para-encriptar
# Sistema de Criptografia e Descriptografia de Arquivos com PyAES

Este projeto implementa a criptografia e descriptografia de arquivos utilizando o módulo `pyaes`. Ele permite proteger arquivos com uma chave AES e posteriormente restaurá-los ao estado original.

## Funcionalidades

- **Criptografia de arquivos:**
  - Lê os dados de um arquivo.
  - Criptografa os dados utilizando AES.
  - Salva o arquivo criptografado com uma nova extensão.
  - Remove o arquivo original para garantir a segurança dos dados.

- **Descriptografia de arquivos:**
  - Lê os dados de um arquivo criptografado.
  - Reverte os dados para o estado original utilizando a mesma chave de criptografia.
  - Salva o arquivo restaurado com o nome original.
  - Remove o arquivo criptografado após a descriptografia.

## Como funciona

1. **Criptografia:**
   - Defina o nome do arquivo original na variável `file_name`.
   - Os dados serão criptografados e salvos em um arquivo com a extensão `.ransomwaretroll`.
   - O arquivo original será excluído.

2. **Descriptografia:**
   - Defina o nome do arquivo criptografado na variável `file_name`.
   - Os dados serão descriptografados usando a mesma chave e salvos com o nome original.
   - O arquivo criptografado será excluído.

## Requisitos

Antes de executar os scripts, instale os seguintes pré-requisitos:

- Python 3.6 ou superior
- Biblioteca `pyaes`

Para instalar o `pyaes`, use:

```bash
pip install pyaes
