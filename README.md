# Detecção Automática de Idioma

Este é um exemplo de código Python para detectar automaticamente o idioma de uma frase fornecida pelo usuário. O código utiliza duas bibliotecas diferentes para essa finalidade: `langdetect` e `fasttext`. As instruções a seguir fornecem detalhes sobre como configurar e executar o código.

## Configuração

Antes de executar o código, certifique-se de ter uma instância do Google Colab configurada e pronta para uso.

### Pré-requisitos

- Instale o `langdetect` e o `fasttext` executando os seguintes comandos:
```bash
!pip install langdetect
!pip install fasttext
## Instruções de Uso

1. Faça o download do notebook do Google Colab contendo o código.
2. Abra o notebook no Google Colab.
3. Execute as células de código conforme necessário.
4. Insira uma frase quando solicitado e aguarde a detecção automática do idioma.

## Descrição do Código

O código está dividido em duas partes principais:

### Detecção de Idioma usando langdetect:

- Utiliza a biblioteca `langdetect` para determinar o idioma da frase inserida pelo usuário.
- Método: `detectar_idioma(frase)`

### Detecção de Idioma usando fasttext:

- Baixa e carrega um modelo pré-treinado para detecção de idioma fornecido pelo FastText.
- Método: `detectar_idioma_fasttext(frase)`

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar uma solicitação de pull request.
