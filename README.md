# Drupal template

A simple composer file to get you started with the Headless Ninja Starterkit

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- PHP 7.x

### Installing

Before you start, you need to make sure Composer is installed on your computer. If you run `composer -V` in your terminal and see something like `Composer version 1.x.x` popping up, you're ready to go.

You install our distribution the following ways:

#### Composer

Create a directory for your project and run the following command in your terminal:

```bash
composer create-project headless-ninja/drupal-template -s dev --remove-vcs
```

This will download a basic Drupal project with HN and other nice-to-have modules installed.

#### Git

Clone this repository
```bash
git clone https://github.com/headless-ninja/drupal-template.git hn-drupal-template
```

Go to the directory of the project. Start with `composer install`, this will download a basic Drupal project with HN and other nice-to-have modules installed.

### Start server

To start the php server, run `composer run start-server --timeout 0` in your terminal. You will need to keep this command running while you're developing.

In your terminal, the URL of your Drupal installation will show up. Open that URL in your browser and follow the on-screen instructions to install the HN Starterskit.

## Running the tests

Yet to come

## Built With

* [Composer](https://getcomposer.org/) - Dependency Manager for PHP

