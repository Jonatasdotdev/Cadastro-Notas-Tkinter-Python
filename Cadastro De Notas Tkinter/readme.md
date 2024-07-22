# Cadastro de Notas com Tkinter

Este projeto é uma aplicação GUI (Interface Gráfica do Usuário) desenvolvida com Tkinter para o cadastro de notas de alunos.

## Índice

- [Introdução](#introdução)
- [Configuração](#configuração)
- [Uso](#uso)
- [Funcionalidades](#funcionalidades)
- [Contribuindo](#contribuindo)
- [Licença](#licença)

## Introdução

Este projeto permite cadastrar, editar, excluir e salvar informações de alunos e suas notas. Os dados podem ser salvos e carregados de um arquivo de texto.

## Configuração

Para executar este projeto, você precisará ter o Python instalado em sua máquina. Recomendamos o uso de um ambiente virtual para gerenciar as dependências.

### Passos para configuração:

1. **Clone o repositório:**
    ```sh
    git clone https://github.com/seu-usuario/cadastro-notas-tkinter.git
    cd cadastro-notas-tkinter
    ```

2. **Crie um ambiente virtual:**
    ```sh
    python -m venv venv
    ```

3. **Ative o ambiente virtual:**
    - No Windows:
      ```sh
      venv\Scripts\activate
      ```
    - No macOS/Linux:
      ```sh
      source venv/bin/activate
      ```

4. **Instale as dependências:**
    ```sh
    pip install tk
    ```

5. **Certifique-se de que a pasta `ui` esteja presente:**
    Baixe a pasta `ui` junto com o repositório, pois ela é necessária para a execução correta da aplicação.

## Uso

Após a configuração, você pode executar a aplicação com o seguinte comando:

```sh
python main.py
