# Chat Interativo com o Modelo de IA Gemini (Google)

## Este script Python permite interagir com o modelo de linguagem de IA Gemini da Google através de um chat.
### Funcionalidades:

* Instalação automática do SDK: O código instala automaticamente o SDK do Google para acesso à API.
* Listagem de modelos disponíveis: Apresenta os modelos compatíveis com geração de conteúdo.
* Configuração flexível: Permite personalizar as configurações de geração e segurança do modelo.
* Interface amigável: Oferece uma interface de chat intuitiva com prompts para o usuário.
* Formatação Markdown: Formata a saída do chat com Markdown para melhor legibilidade.
* Visualização do histórico: Permite visualizar o histórico completo da conversa a qualquer momento.
### Requisitos:
* Python 3.x
* Chave de API da Google (GOOGLE_API_KEY)
### Como Usar:
* Insira sua chave de API da Google no campo GOOGLE_API_KEY.
* Execute o script.
* Digite seus prompts no chat.
* Digite "histórico" para visualizar o histórico da conversa.
* Digite "fim" para encerrar o chat.
### Observações:
Explore as opções de configuração do modelo para ajustar o comportamento da IA.
Consulte a documentação do Google AI Platform para mais informações sobre o modelo Gemini.
### Exemplo de Uso:
**Sessão de Chat iniciada!**
Digite seu prompt (ou "fim" para encerrar, ou "histórico" para visualizar o histórico): Olá!
> **Você:** Olá!
> **Gemini:** Olá! Como posso te ajudar hoje?
-------------------------------------------
Digite seu prompt (ou "fim" para encerrar, ou "histórico" para visualizar o histórico): Qual a sua função?
> **Você:** Qual a sua função?
> **Gemini:** Sou um modelo de linguagem grande, treinado pelo Google.
-------------------------------------------
Digite seu prompt (ou "fim" para encerrar, ou "histórico" para visualizar o histórico): histórico

**Histórico da Conversa:**
> **Usuário (1):** Olá!
> **Gemini (2):** Olá! Como posso te ajudar hoje?
> **Usuário (3):** Qual a sua função?
-------------------------------------------

Digite seu prompt (ou "fim" para encerrar, ou "histórico" para visualizar o histórico): fim

**Sessão de Chat encerrada!** 

## Contribuições:
Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests com melhorias e correções.
