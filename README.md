<h1 align='center'>FastSoftForge Laravel</h1>

<h2>Installing :</h2>

<h3>1) Cloning a repository :</h3>

<br>

```
git clone https://github.com/WhoStoleMySleep/fastsoftforge_laravel.git
```

<br>


<h3>2) Installing the necessary modules :</h3>

<br>

```
composer install && npm install && php artisan sail:install
```

<br>

<h3>3) Launch :</h3>

<br>

<h4>Starting docker and running laravel</h4>

```
./vendor/bin/sail up
npm run dev
```

<br>


<h3>4) Migrations :</h3>

<br>
<h4>Running sail migrations</h4>

```
./vendor/bin/sail artisan migrate
```

<br>
