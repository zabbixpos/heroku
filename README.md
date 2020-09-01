# heroku

#Install
curl https://cli-assets.heroku.com/install.sh | sh
#nodjs - necessario

# Clone
git clone https://github.com/repo/porjet.git

#Criando App
heroku apps:create appname
#ou via web

#Associando repositorio baixado ao app
heroku git:remote -a appname

#PUSH
git push heroku master
