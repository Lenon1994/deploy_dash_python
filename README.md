**deploy Render**
Passo a passo:
- Acessar: https://dashboard.render.com/ 
- Após acessar seguir processos abaixo
- New+
- Webservice
- Conectar no repositorio GIT
- Copiar o link com as informações do repositorio GIT e colar no RENDER
- Realizar as configurações do render
- Configurações
- Precisa ter o requirements.txt nos arquivos GIT (arquivos com as bibliotecas utilizadas no python)
- Precisa ter em star comand "$ gunicorn app:app"
- Depois selecionar Create WebService
- Acompanhar deploy e caso falhe realizar a correção e depois (manual deploy > cache deploy) para executar novamente.



**Comandos GIT para carregar os arquivos**
- Abrir CMD ir até a pasta dos arquivos e realizar o seguinte comando (git init)
- Comando para adicionar todos os arquivos da pasta (git add .)
- Comando para avaliar o status (git status )
- Toda alterção precisa realizar o commit (git commit -m “colocar o texto aqui”)
- Associar o local dos arquivos (git remote add origin "link com o repositorio GIT")
- Acessar ao branch principal (git branch -M main)
- Comando para subir os arquivos (git push -u origin main)
- Comando para avalair logs (git log --oneline --graph -all)
- Comando para pegar arquivos do Git (git pull)


**Observação**
O arquivo com o dataset precisa estar dentro da pasta assets