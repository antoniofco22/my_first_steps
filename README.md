1. Após criado a sua conta no GitHub, crie um repositório remoto público chamado “my_first_steps” e cole o link aqui; 
https://github.com/antoniofco22/my_first_steps
2. Crie um diretório em sua máquina e o vincule ao seu repositório remoto “my_first_steps” utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa. 

$ mkdir “my_first_steps”
$ cd “my_first_steps”	
$ git init
$ git branch -M main
$ git remote add origin git@github.com:antoniofco22/my_first_steps.git


3. Dentro do diretório em sua máquina, crie um arquivo chamado “ola_mundo.txt”, adicione algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa. 

$ touch ola_mundo.txt

$ git add ola_mundo.txt

$ git commit -m "primeiro commit"
$ git branch -M main
$ git remote add origin git@github.com:antoniofco22/my_first_steps.git
$ git push -u origin main
Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
$ ssh-keygen -t ed25519 -C "antoniofco20142014@gmail.com"
--Ir ao github e autentica a chave 
$ git push -u origin main

4. Se não existir em seu diretório, adicione ao seu diretório um arquivo com o nome de “.gitignore”. Em seguida, crie um arquivo chamado “serei_ignorado.txt” e adicione algum texto dentro dele. Adicione a instrução ao arquivo “.gitignore” para que as alterações realizadas no arquivo “serei_ignorado.txt” não seja controlado pelo git. Cole aqui o conteúdo que você utilizou no “.gitignore” para realizar esta tarefa. 

/serei_ignorado.txt
