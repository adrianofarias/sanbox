# sanbox
Repositório de testes pra treinar o uso do git


#•	Passo 1: Clone o repositorio na sua máquina into your local machine.

 
 
#•	Passo 2: Copie e cole o link no terminal depois de git clone. Use os commandos abaixo para clonar seu repositório:
•	git clone (REPOSITORIO)
git clone https://USERNAME@bitbucket.org/USERNAME/REPOSITORY_NAME.git
 
 
#•	Passo 3: Verifique seu progresso digitando “git status” no terminal
git status
 
#•	Passo 4: Criando e adicionando um arquivo ao seu repositório 
Suponha que você queira criar e adicionar um arquivo ao seu repositório. Digite os commando abaixo no terminal:
•	echo "Esse é um arquivo de teste" >> arquivo.txt
git add arquivo.txt
 
 
#•	Passo 5: Comitar suas mudanças no repositórioCommiting changes to BitBucket Repository
Seu arquivo agora foi adicionado e está pronto para ser enviado ao repositório central.


git commit -m "Commit inicial"
git push origin master // para enviar as mudanças ao repositório
 
 
Se existirem algumas mudanças no seu repositório, você pode usar o git pull para restaurar essas mudanças na sua máquina.
git pull
git pull origin master 
git pull --all
qualquer desses commandos pode ser executado para puxar as mudanças para a sua máquina.
 
#•	Passo 6: Executando operações em branches 
Para criar um branch, digite no terminal:

git branch teste // para criar um novo chamado teste
 
Para mudar para esse branch, utilize o comando git checkout:
git checkout teste // para mudar para um branch chamado teste
Finalmente, para fazer o merge do seu branch com o master, use o commando git merge para juntar os dois branches.
git merge teste
 
 
#•	Passo 7: Para apagar um branch, use git branch -d para apagar o branch
git branch -d teste
 
