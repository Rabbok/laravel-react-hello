# Laravel + React Hello World

## 1. Create project

```bash
composer create-project laravel/laravel laravel-react-hello
cd laravel-react-hello
npm install
npm install react react-dom @vitejs/plugin-react
```

## 2. Replace files with the files from this archive

Replace these files in your Laravel project:

- `resources/js/app.jsx`
- `resources/views/app.blade.php`
- `routes/web.php`
- `vite.config.js`

## 3. Run project

```bash
npm run dev
php artisan serve
```

Open:

```text
http://127.0.0.1:8000
```

You should see:

```text
Hello world
```

## 4. Upload to GitHub

```bash
git init
git add .
git commit -m "Laravel React hello world"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

## 5. Send to teacher

Send your GitHub repository link by email.
