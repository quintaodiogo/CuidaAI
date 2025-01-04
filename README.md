# CuidaAI

Para enfrentar a situação de quedas de idosos, desenvolvi o CuidaAI, um sistema de detecção de quedas como parte do projeto final da disciplina de Laboratório de Inteligência Artificial na faculdade, aplicando tudo o que aprendi ao longo do curso.

## Como funciona o CuidaAI?

🔹 Detecção em tempo real de quedas utilizando YOLO11 pose  
🔹 Alertas automáticos via Telegram com imagem da ocorrência  
🔹 Orientações de primeiros socorros por meio de um chatbot integrado  
🔹 Ação emergencial caso o responsável não responda ao alerta  

## 🚀 Próximos passos

- Implementar chamadas automáticas de ambulância
- Expandir as funcionalidades do chatbot

A tecnologia pode salvar vidas, e o CuidaAI é um exemplo de como podemos usar a inteligência artificial para cuidar de quem cuidou de nós. Vamos juntos transformar a segurança dos idosos em prioridade! 👴💡

## Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/quintaodiogo/CuidaAI.git
    cd cuidaai
    ```

2. Crie e ative um ambiente virtual:
    ```sh
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

3. Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Configure as variáveis de ambiente no arquivo .env:
    ```env
    BOT_TOKEN=seu_bot_token
    CHAT_ID=seu_chat_id
    OPENAI_API_KEY=sua_openai_api_key
    ```

2. Execute o script principal:
    ```sh
    python main.py
    ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias e novas funcionalidades.
