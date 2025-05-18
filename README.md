# Teste de Assistente de IA com Gemini

Este projeto é um experimento com o modelo Gemini do Google para criar um assistente de inteligência artificial. Ele demonstra como interagir com o modelo Gemini para obter respostas a perguntas e manter um histórico de conversas.

## Descrição

O código no notebook `testeAssistenteDeIA.ipynb` realiza as seguintes ações:

* **Instalação da Biblioteca:** Utiliza `pip` para instalar a biblioteca `google-genai`.
* **Configuração da Chave da API:** Lê a chave da API do Google GenAI de uma variável de ambiente (usando `google.colab.userdata`). **Nota:** É importante que você configure sua chave de API corretamente no Colab para que o código funcione.
* **Inicialização do Cliente Gemini:** Cria um cliente para interagir com os modelos Gemini.
* **Listagem de Modelos:** Imprime a lista de modelos Gemini disponíveis.
* **Geração de Conteúdo:** Demonstra como usar o modelo para gerar respostas simples a perguntas.
* **Criação de Chat:** Cria sessões de chat para manter o contexto das conversas.
* **Personalização do Comportamento:** Mostra como usar `system_instruction` para influenciar o comportamento do assistente (por exemplo, respostas sucintas ou sarcásticas).
* **Interação em Loop:** Implementa um loop simples para que o usuário possa fazer perguntas repetidamente ao assistente.

## Como Usar

1.  **Pré-requisitos:**
    * Conta Google Cloud com acesso à API Gemini.
    * Chave da API do Google GenAI configurada no Google Colab (ou em seu ambiente local).
    * Python 3.6 ou superior.
2.  **Configuração:**
    * Abra o notebook `testeAssistenteDeIA.ipynb` no Google Colab.
    * Certifique-se de que a variável de ambiente `GOOGLE_API_KEY` esteja configurada com sua chave da API.  No Colab, você pode usar `google.colab.userdata`.
3.  **Execução:**
    * Execute as células do notebook sequencialmente.
    * Na célula de interação em loop, você poderá digitar suas perguntas e ver as respostas do assistente.
    * Digite "sair" para encerrar o loop.

## Estrutura do Código

O código é organizado em células em um notebook Jupyter:

* **Célula 1:** Instalação da biblioteca.
* **Células 2-3:** Configuração da API e inicialização do cliente.
* **Célula 4:** Listagem de modelos.
* **Células 5-7:** Exemplos de geração de conteúdo e criação de chat.
* **Células 8-10:** Demonstração de personalização do comportamento do assistente.
* **Células 11-13:** Loop de interação com o usuário.
* **Células 14-16:** Exemplo de assistente com respostas sarcásticas.

## Contribuição

Contribuições são bem-vindas! Se você tiver ideias para melhorar este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

## Agradecimentos

Agradecimentos à equipe do Google GenAI e à Alura pela inspiração e recursos educacionais.
