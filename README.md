# Laravel E-commerce Website for Computer Shop

## Database Schema
![DatabaseSchema](https://github.com/Dapravith/E-Commerce/assets/90898700/fbe02546-9292-47db-8120-579e3c771ed7)


## Installation 
Make sure you have environment setup properly. You will need MySQL, PHP8.1, Node.js and composer.

### Install Laravel Website + API
1. Download the project (or clone using GIT)
2. Copy `.env.example` into `.env` and configure database credentials
3. Navigate to the project's root directory using terminal
4. Run `composer install`
5. Set the encryption key by executing `php artisan key:generate --ansi`
6. Run migrations `php artisan migrate --seed`
7. Start local server by executing `php artisan serve`
8. Open new terminal and navigate to the project root directory
9. Run `npm install`
10. Run `npm run dev` to start vite server for Laravel frontend

### Install Vue.js Admin Panel
1. Navigate to `frontend-vuejs` folder
2. Run `npm install`
3. Copy `frontend-vuejs/.env.example` into `frontend-vuejs/.env`
4. Make sure `VITE_API_BASE_URL` key in `frontend-vuejs/.env` is set to your Laravel API host (Default: http://localhost:8000)
5. Run `npm run dev`
6. Open Vue.js Admin Panel in browser and login with
    ```
    admin@example.com
    admin123
    ```
## Website URL: 
1. Admin Dashboard (Frontend part Build With VueJS,Tailwind CSS):
https://admin.vithe-commerce.com 
2. Client Homepage (Backend part Build With PHP, Laravel framework): 
https://vithe-commerce.com
