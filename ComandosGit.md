Conceitos basicões: 

Fork = puxar código para repositório próprio (roubar heh) 

Branch = ramificação projeto, usando linhas cronologicas diferentes p/ não usar só uma linha cronologica 

Merge = Juntar branch

Remote = referenciar github

Push = P/ colocar commit no remote 

Pull = puxa o que está no repositório p/ máquina 

Comandinhos: 

-> git --version
P/ verificar versão do git 

-> git init 
P/ inicializar um novo repositório do git ou converter um projeto existente

-> git add Comandos GitHub.md
P/ colocar arquivos em estado de staging 

-> git add . 

-> git status 

-> git commit -m "primeiro commit"

-> git branch -M "main" 
Boa prática!! 

-> git remote add origin +link do repositório
Só cria a conexão uma vez

-> git push -u origin main 

-> git checkout -b "novo-botao"
Sai da branch em que estou e cria uma nova branch 

-> git checkout main 
Volta para branch principal 

-> git checkout novo-botao

-> git merge novo-botao
após isso git push origin main 

-> git clone 

-> cd gittutorial
p/ entrar em uma pasta

-> clear 

-> git pull