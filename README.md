# Prova Prática - Desenvolvimento Web

RECOMENDO LER TUDO

Nesta prova prática, você deverá realizar uma série de tarefas envolvendo os projetos fornecidos (API e Cliente React) para demonstrar seus conhecimentos em desenvolvimento web.

Você poderá consultar qualquer material de apoio à sua disposição: apostilas, slides, pdfs, ChatGPT, Gemini, Copilot, Jesus, caderno, Internet, Intranet, entre outros. **É proibido conversar com outros alunos ou compartilhar códigos de qualquer forma**.

Caso haja suspeita de descumprimento das regras, o professor tem plena autonomia para avaliar e aplicar as devidas sanções. Se o aluno sentir-se prejudicado, poderá acionar a coordenação do curso ou, em última instância, desafiar o professor para uma "trocação franca de porrada livre" fora do ambiente acadêmico, com meia hora de duração. Quem desistir primeiro é considerado "errado". O professor se reserva o direito de negar o desafio caso o aluno apresente uma diferença significativa de tamanho ou peso.

## Tarefas

1. **Fork dos Projetos**:
   - Faça um fork dos repositórios fornecidos:
     - [API de Gerenciamento de Itens](https://github.com/Desenvolvimento-WEB-I-2024-2-Ensi-Medio/gerenciamento-itens-api)
     - [Cliente React para Gerenciamento de Itens](https://github.com/Desenvolvimento-WEB-I-2024-2-Ensi-Medio/react-gerenciamento-itens)

2. **Clonagem e Configuração**:
   - Clone os repositórios para a sua máquina:
     ```bash
     git clone https://github.com/Desenvolvimento-WEB-I-2024-2-Ensi-Medio/gerenciamento-itens-api.git
     git clone https://github.com/Desenvolvimento-WEB-I-2024-2-Ensi-Medio/react-gerenciamento-itens.git
     ```
   - Instale as dependências em ambos os projetos:
     ```bash
     cd gerenciamento-itens-api
     npm install
     cd ../react-gerenciamento-itens
     npm install
     ```

3. **Iniciar os Servidores**:
   - Inicie o servidor da API:
     ```bash
     cd gerenciamento-itens-api
     node app.js
     ```
   - Inicie o cliente React:
     ```bash
     cd ../react-gerenciamento-itens
     npm start
     ```

4. **Conectar os Projetos**:
   - Verifiquei com o inspecionar do browser se teve algum erro.
   - Descrubra onde a API está rodando (IP e Porta), sabendo disso ajuste o react para se conectar a API.

5. **Realizar Cadastro e Login**:
   - Acesse o cliente React.
   - Crie um novo usuário na página de registro.
   - Faça login com o usuário criado.

6. **Adicionar um Novo Item**:
   - Após fazer login, acesse a página principal do cliente React.
   - Adicione o seu nome como um novo item.
   - E mude o texto do título para "Prova de Desenvolvimento Web - Seu Nome".

7. **Finalizar e Subir as Alterações**:
   - Não existem regras de como subir para github, use a forma que achar mais confortável. Mas caso queira via terminal segue como fazer:
   - Faça um commit das alterações realizadas no projeto:
     ```bash
     git add .
     git commit -m "Prova completa: cadastro, login e adição de item"
     ```
   - Suba as alterações para o seu repositório no GitHub:
     ```bash
     git push origin main
     ```
   - Observe que são dois projetos que vc tem de enviar o link, um da API e outro do React (que consome a API)

9. **Entrega da Prova**:
   - Envie o link dos seus repositórios (API e Cliente React) com as alterações realizadas no AVA (Prova 2).
  
   - IMPORTANTE: Qualquer aluno que perguntar se algo da prova está "certo" ou pedir para o professor conferir se está correto, não receberá resposta. Além disso, será aplicada uma segunda prova como penalidade. Não haverá tempo adicional para a realização dessa segunda prova, que consistem am achar os bugs na api (backup). Além disso, terá de explicar quais foram os ajustes realizados no code para fazer funcionar
  
10. **Avaliação**:
    - Será avalidado se o aluno conseguiu realizar as atepas acima citado;
    - As estratégias que o aluno utilizou para realizar as etapas;
    - E o tempo que aluno levou para realizar, de maneira proporcional;
---

**Boa sorte!**
