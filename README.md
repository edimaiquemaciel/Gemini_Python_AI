README.md
Este repositório demonstra como utilizar o Google Generative AI SDK com o modelo Gemini para tarefas de geração de texto e interação em formato de chat.
Requisitos:
Python 3.8 ou superior
Google Cloud Platform account com acesso ao Google Generative AI API
Bibliotecas: google-generativeai
Instalação:
Clone este repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Use code with caution.
Bash
Instale as bibliotecas necessárias:
pip install -r requirements.txt
Use code with caution.
Bash
Configure a API Key do Google Cloud:
Crie um arquivo chamado secret.py no diretório raiz do projeto.
Adicione a seguinte linha, substituindo YOUR_API_KEY pela sua chave da API:
SECRET_KEY = "YOUR_API_KEY"
Use code with caution.
Python
Uso:
Execute o script principal:
python main.py
Use code with caution.
Bash
O script irá:
Listar os modelos disponíveis no Google Generative AI.
Definir configurações de temperatura e segurança para o modelo.
Inicializar o modelo gemini-1.5-pro-latest.
Gerar conteúdo de texto com base em um prompt inicial.
Iniciar uma sessão de chat, permitindo que você envie prompts e receba respostas do modelo.
Ao digitar "fim", o chat será encerrado e o histórico da conversa será exibido em formato Markdown.
Funcionalidades:
Geração de Conteúdo: O modelo pode gerar diversos tipos de conteúdo textual, como histórias, artigos, poemas, etc.
Chat Interativo: Interaja com o modelo em formato de conversa, fazendo perguntas e obtendo respostas.
Configurações de Segurança: Ajuste as configurações de segurança para bloquear conteúdos indesejados.
Controle de Temperatura: Ajuste a temperatura para controlar a criatividade e imprevisibilidade do modelo.
Observações:
O modelo gemini-1.5-pro-latest é utilizado neste exemplo, mas você pode experimentar outros modelos disponíveis.
As configurações de temperatura e segurança podem ser ajustadas conforme suas necessidades.
O histórico de chat é exibido no final da execução para facilitar a visualização.
Próximos Passos:
Explore diferentes modelos e configurações para descobrir as possibilidades do Google Generative AI.
Integre este código em seus projetos para gerar conteúdo dinâmico e interativo.
Experimente outros métodos de geração de conteúdo, como tradução, resumo, etc.
Recursos:
Google Generative AI Documentation: https://ai.google/discover/generative-ai
Google Generative AI SDK: https://github.com/googleapis/python-generativeai
