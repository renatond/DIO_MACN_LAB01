# DIO_MACN_LAB01

Este projeto é um exemplo de aplicação de cadastro e listagem de produtos em um e-commerce na nuvem, utilizando:

- Streamlit para a interface web
- Azure Blob Storage para armazenamento de imagens
- Azure SQL Server para persistência dos dados dos produtos

## Como rodar o projeto

1. Clone este repositório.
2. Crie um arquivo `.env` na raiz do projeto com as variáveis de ambiente necessárias (veja o arquivo `env.txt` para o modelo).
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Execute a aplicação:
   ```bash
   streamlit run main.py
   ```

## Variáveis de Ambiente
Veja o arquivo `env.txt` para os nomes das variáveis que devem ser definidas no seu `.env`.

## Observações
- Não compartilhe seu arquivo `.env` nem dados sensíveis.
- O arquivo `produtos.json` é usado apenas como exemplo local e não é necessário para produção.

---

Projeto para o bootcamp Microsoft Azure Cloud Native da DIO.
