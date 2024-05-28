# Programa servidor API-REST de mensagens utilizando Node.js no Render.

- O projeto foi desenvolvido no VSCode deve ser chamado "mensagem_nodejs_render".
- Programa cliente está no projeto "mensagem_reactjs_render".
- Programa servidor cria o webservice na posta 8000.
- Implementação do serviço utilizando REST e os métodos GET e POST.
- Classe Mensagem possui duas operações: setMensagem e getMensagem.

- Dependências:    
    - express,
    - cors.

- Execução:    
   <pre><code>npm start</code></pre>

- Arquivos em src:
    - index.js - Programa principal com o servidor Express.
    - mensagem.js - Contêm a classe da Mensagem.
    - mensagemrecurso.js - Contêm os métodos de acesso aos recursos da mensagem.
    - servicos.js - Contêm as rotas aos métodos de acesso a mensagem.

- Render   
   https://mensagem-nodejs-render.onrender.com