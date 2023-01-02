
## Instalação


1. Download o projeto
2. Copie `.env.example` para `.env` e configure as credenciais
3. Vá para a pasta raiz do projeto
4. Rode `composer install`
5. Set a encryption key executando `php artisan key:generate --ansi`
6. Rode as migrations `php artisan migrate --seed`
7. Starte o local server executando `php artisan serve`
8. Abra um terminal e entre na pasta react
9. Copie `react/.env.example` dentro `.env` e ajuste`VITE_API_BASE_URL` parametro
9. Rode `npm install`
10. Rode `npm run dev` para iniciar o servidor
