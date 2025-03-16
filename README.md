# Ruby on Rails Getting Started Guide

This project is a Ruby on Rails application created by following the
[Getting Started with Rails](https://guides.rubyonrails.org/getting_started.html) guide. The guide
provides a step-by-step tutorial for building a simple e-commerce application called "store".

## Features

- Create, read, update, and delete (CRUD) products
- Basic authentication for product management
- Inventory tracking
- Email notifications for products back in stock
- Simple user interface for managing products

## Requirements

- Ruby 3.2 or newer
- Rails 8.0 or newer
- SQLite3

## Setup

1. Install dependencies:

   ```sh
   bundle install
   ```

2. Set up the database:

   ```sh
   rails db:migrate
   ```

3. Start the Rails server:

   ```sh
   rails server
   ```

4. Open your browser and navigate to `http://localhost:3000` to see the application running.

## User default credentials

- email: "you@example.org"
- password: "s3cr3t"
