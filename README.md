# Projeto-PI-TASKO
Desenvolvido por Luiz Biajante, Donavan Ryu Mishima e Lucas Simão, esse projeto é integrado com uma API, sendo
gerenciado o front com back-end, com sistema de login e cadastro de conta, criação de tarefas, sistema de ranking 
semanal e pontuação.

# O que o projeto faz?
No TASKO, você pode criar sua conta e realizar seu login, dentro da tela inicial voce pode criar seu
dia contendo suas tarefas diárias em forma de checklist, cada tarefa vale uma certa quantia de pontos escolhida por 
você. Acumulando pontos, voce pode subir de ranking, é salvo sua pontuação maxima, e sua pontuação semanal 
é resetada a cada semana.

#O que utilizamos?
Ferramentas: VSCODE, MySQL com XAMPP.
Linguagems: HTML, CSS, JavaScript, Node Express, React

# Como rodar?
1 - Ative o apache e sql do xampp
2 - Baixe o projeto, extraia e abara a pasta "tasko-js-main" no vscode
3 - Caso precise, copie o código sql "CREATE.sql" e cole no phpadmin do xampp, na área de SQL, cole o código sql,
e execute.

4 - Dentro do projeto no vs code, abra 2 prompt de comando, e em um deles digite: cd frontend, para ir na pasta
front end.

5 - Dê um npm install nos 2 prompt, um vai instalar node modules na area principal, e o outro vai instalar node modules
na pasta frontend (caso precise, instale separado além do restante o vite)

6 - No prompt principal, digite o comando: node app.js 

7 - Dê um npm run dev no prompt do frontend, e acesse o localhost gerado.
