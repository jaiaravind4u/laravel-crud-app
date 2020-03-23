<h1>Simple Laravel app with CRUD operations, authentication & access control, and file uploading</h1>

<p>This is a simple CRUD app I use as a starter for my other projects. It has a blog-like interface with authentication, access control, image uploads.</p>

<p>It has barebones but highly extensible functionality.</p>

<h2>Setup:</h2>
<ol>
    <li><h3>Clone (or fork) repo</h3>
        <code>git clone https://github.com/jaiaravind4u/laravel-crud-app.git</code>
    </li>
    <li><h3>Install Composer dependencies</h3>
        <code>composer install</code>
    </li>
    <li><h3>Install NPM dependencies</h3>
        <code>npm install</code></li>
    <li><h3>Create .env file by copying .env.example</h3>
        <code>cp .env.example .env</code></li>
    <li><h3>Generate an app encryption key. It will appear in .env as APP_KEY</h3>
        <code>php artisan key:generate</code>
    </li>
    <li><h3>Create an empty SQL database</h3>
    </li>
    <li><h3>Add database information in the application .env file</h3>
    <p>(make sure db name, credentials, and port are correct- check your server configuration docs if any issues)</p>
    </li>
    <li><h3>Migrate the databse</h3>
        <code>php artisan migrate</code>
    </li>
    <li><h3>Create a symlink to make assets in /storage accessible in /public</h3>
        <code>php artisan storage:link</code>
    </li>
</ol>



## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
