# Lighthouse and GraphQL Tutorial

This is a simple GraphQL API built with [Lighthouse - GraphQL Server for Laravel](https://github.com/nuwave/lighthouse).

Lighthouse is a PHP package that allows you to serve a GraphQL endpoint from your Laravel application. It greatly 
reduces the boilerplate required to create a schema, it integrates well with any Laravel project, and it's highly 
customizable giving you full control over your data.

# Steps
1. git clone git@github.com:subiniz/graphql-lighthouse.git
2. setup .env
3. composer install
4. php artisan vendor:publish --provider="Nuwave\Lighthouse\LighthouseServiceProvider"
5. php artisan vendor:publish --provider="MLL\GraphQLPlayground\GraphQLPlaygroundServiceProvider" 
6. php artisan migrate
7. php artisan serve
