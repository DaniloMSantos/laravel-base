Iniciar o git e clonar o projeto base
"git init
git clone https://github.com/DaniloMSantos/laravel-base NomeDoProjeto"

Remover conexão com o projeto base
"git remote remove origin"

Criar um repositório novo no GitHub e conectar
"git remote add origin https://github.com/~~~ (Caminho do novo repositório)"

Instalar composer e npm
"composer install
npm install"

Copiar e ditar o .env
"copy .env.example .env"
(Campos APP_NAME DB_DATABASE DB_USERNAME e DB_PASSWORD)

Criar o Banco
"mysql -u root -p
CREATE DATABASE nome_do_banco;
exit;"

Gerar a Laravel Key
"php artisan key:generate"

Rodar as Migrations
"php artisan migrate"

Iniciar o Backend 
"php artisan serve"

Iniciar o Frontend
"npm run dev"

Comitar alteração
"git add .
git commit -m "Initial project setup""

Subir pro git
"git branch -M main
git push -u origin main"
