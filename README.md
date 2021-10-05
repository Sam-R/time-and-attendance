# Simple Time & Attendance
Built with Laravel

**Develop**
1. Clone repo and checkout `dev` branch
2. Run `composer intsall`
3. Copy `.env.example` to `.env`
4. Run `php artisan key:generate`
5. Run `vendor/bin/sail up -d` to bring the application up using docker
6. Visit `localhost` in your browser

If you already have Port 80 being used on your machine, go into the `.env` and add `APP_PORT=8080`, then run `vendor/bin/sail up -d` again for it to spin up using `localhost:8080`