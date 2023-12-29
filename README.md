
# Example Starter Application Tall Stack

## Requirements

- PHP `>= v8.1` and Composer `>= v2.0`
- Node.js `>= v20.0`

## Setup

1. Clone the repository & `cd` into it
   ```shell
   $ git clone git@github.com:sakukode/example-starter-tall-stack.git <dir-name>
   $ cd <dir-name>
   ```
2. Install dependencies
   ```shell
   $ composer install
   $ npm install
   ```
3. Copy `.env.example` file to `.env` file & generate new app key
   ```shell
   $ php artisan key:generate
   ```

## Development

### Front-end

Run this command to build asset for local development

```sh
$ npm run dev
```

or build the asset for production
```sh
npm run build
```
