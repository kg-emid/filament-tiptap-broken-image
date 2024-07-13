### Filament Tiptap broken image demo project
1. Create database
2. Do `cp .env.example .env`
3. Fill `.env` with your db credentials
4. Run migrations: `php artisan migrate`
5. Start the server with `php artisan serve`
6. Add the port of your server to APP_URL in env file
7. Link storage: `php artisan storage:link`
8. Create filament user: `php artisan make:filament-user`
9. Login to admin
10. Try to make new post following steps from my video attached to issue
