<p align="center">
    <a href="https://github.com/wissalcharraki/ECommerceCosmeticsApp" target="_blank">
        <img src="https://your-image-link.com/logo.png" width="400" alt="E-Commerce Cosmetics App Logo">
    </a>
</p>

<p align="center">
    <a href="https://github.com/wissalcharraki/ECommerceCosmeticsApp/actions"><img src="https://github.com/wissalcharraki/ECommerceCosmeticsApp/workflows/tests/badge.svg" alt="Build Status"></a>
    <a href="https://packagist.org/packages/yourusername/ecommerce-cosmetics-app"><img src="https://img.shields.io/packagist/dt/yourusername/ecommerce-cosmetics-app" alt="Total Downloads"></a>
    <a href="https://packagist.org/packages/yourusername/ecommerce-cosmetics-app"><img src="https://img.shields.io/packagist/v/yourusername/ecommerce-cosmetics-app" alt="Latest Stable Version"></a>
    <a href="https://github.com/wissalcharraki/ECommerceCosmeticsApp/blob/main/LICENSE"><img src="https://img.shields.io/github/license/wissalcharraki/ECommerceCosmeticsApp" alt="License"></a>
</p>

## About E-Commerce Cosmetics App

This E-Commerce Cosmetics App is a web application developed for the sale and management of cosmetic products. Built using an agile approach, it offers a range of features for product management, category browsing, secure checkouts, and more.

- [User Authentication and Profile Management](https://github.com/wissalcharraki/ECommerceCosmeticsApp/docs/authentication)
- [Product and Category Management](https://github.com/wissalcharraki/ECommerceCosmeticsApp/docs/product-management)
- [Advanced Filtering and Search](https://github.com/wissalcharraki/ECommerceCosmeticsApp/docs/advanced-search)
- [Shopping Cart and Checkout](https://github.com/wissalcharraki/ECommerceCosmeticsApp/docs/checkout)

The application is designed to provide users with a smooth and secure shopping experience, backed by PHP and Laravel.

## Getting Started

To get started with this project, please visit the [documentation](https://github.com/wissalcharraki/ECommerceCosmeticsApp/docs) for setup instructions.

<h2>Technologies Used</h2>

<p>The E-Commerce Cosmetics Application is built using a range of modern web development tools and frameworks to ensure a secure, scalable, and user-friendly experience.</p>

<ul>
    <li><strong>Frontend</strong>:
        <ul>
            <li><strong>HTML, CSS, JavaScript</strong>: Core technologies for structuring, styling, and scripting the web pages.</li>
            <li><strong>Bootstrap</strong>: A popular CSS framework for responsive and mobile-first front-end development.</li>
            <li><strong>jQuery</strong>: A JavaScript library that simplifies DOM manipulation and enhances interactivity.</li>
        </ul>
    </li>
    <li><strong>Backend</strong>:
        <ul>
            <li><strong>PHP</strong>: Server-side scripting language to handle dynamic content and server logic.</li>
            <li><strong>Laravel</strong>: A powerful PHP framework for secure and efficient application development with built-in authentication, routing, and database management.</li>
        </ul>
    </li>
    <li><strong>Database</strong>:
        <ul>
            <li><strong>MySQL</strong>: A reliable and scalable relational database management system used to store product data, user information, and order details.</li>
            <li><strong>PhpMyAdmin</strong>: A web-based tool for managing MySQL databases, providing an intuitive interface for database interactions.</li>
        </ul>
    </li>
    <li><strong>Development Tools</strong>:
        <ul>
            <li><strong>Composer</strong>: Dependency manager for PHP, used to install and manage libraries for Laravel and other PHP packages.</li>
            <li><strong>XAMPP</strong>: A local development environment for testing and deploying the application on a local server.</li>
            <li><strong>Adobe Illustrator</strong>: Used for creating and editing visual assets and graphics for the application's design.</li>
        </ul>
    </li>
</ul>

<h2>How to Run the Project</h2>

<p>Follow these steps to set up and run the E-Commerce Cosmetics Application locally:</p>

<ol>
    <li><strong>Clone the repository:</strong>
        <pre><code>git clone https://github.com/wissalcharraki/ECommerceCosmeticsApp.git</code></pre>
    </li>
    <li><strong>Navigate to the project directory:</strong>
        <pre><code>cd ECommerceCosmeticsApp</code></pre>
    </li>
    <li><strong>Install dependencies:</strong>
        <p>Make sure you have <a href="https://getcomposer.org/" target="_blank">Composer</a> installed, then run:</p>
        <pre><code>composer install</code></pre>
    </li>
    <li><strong>Configure the environment:</strong>
        <ul>
            <li>Rename the <code>.env.example</code> file to <code>.env</code>.</li>
            <li>Update the database credentials in the <code>.env</code> file:</li>
            <pre><code>
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
            </code></pre>
        </ul>
    </li>
    <li><strong>Generate the application key:</strong>
        <pre><code>php artisan key:generate</code></pre>
    </li>
    <li><strong>Run database migrations:</strong>
        <p>This will create the necessary tables in your database:</p>
        <pre><code>php artisan migrate</code></pre>
    </li>
    <li><strong>Start the development server:</strong>
        <p>You can start the server with the following command:</p>
        <pre><code>php artisan serve</code></pre>
        <p>The application will now be accessible at <a href="http://localhost:8000" target="_blank">http://localhost:8000</a>.</p>
    </li>
</ol>

<p>You're all set! Visit <a href="http://localhost:8000" target="_blank">http://localhost:8000</a> in your browser to view and use the E-Commerce Cosmetics Application.</p>


<p>These technologies were selected to optimize the application's performance, security, and ease of use, making it suitable for both administrators and customers looking for an enhanced online shopping experience.</p>

### Demonstration
Watch a demonstration of the application in action: [E-Commerce Cosmetics App Demo](https://youtu.be/fC0K3S2wQLg?si=xxEiMuoolT-jtXry)

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
