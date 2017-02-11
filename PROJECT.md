Teste de Recrutamento Climatempo - Diego Hideky

#Seja Bem Vindo ao Challenge Accepted

Abaixo estão descritos o passo-a-passo para executar este projeto

# [SERVER AUX] matar os processos node
killall -9 node

# Instalar bower
npm install bower -g

# Instalar dependencias de frontend
cd public/
bower update

# Instalar dependencias de backend
npm install

# Instalar node ejs
npm install ejs --save

# [LOCAL] server
npm install node -g
node app.js

# [TEST] instalar mocha
sudo apt install mocha
cd test/
mocha test.js

# GitHub
- https://github.com/diegohideky/challenge-accepted

******************************************************************************
Logo na primeira tela existe um campo de busca onde você pode digitar a cidade
este campo entra na rota '/search/:city'
do qual retorna os valores de clima da cidade caso ela exista
******************************************************************************

Projet desenvolvido em Node EJS, Materialize CSS 