<p align="center">
  <img src="https://shopxoserver.oss-cn-beijing.aliyuncs.com/demo/system/logo.jpg" width="360" />
</p>

# ShopXO Rental Platform

ShopXO is now an **online rental platform** built around a WeChat Mini Program. The backend API is powered by ThinkPHP and exposes rental features such as item listings, rental periods, deposits and order processing. The WeChat Mini Program provides users with a quick way to browse, book and return rental items.

## Features

- Inventory and rental period management
- Deposit handling and order tracking
- WeChat login and payment integration
- Admin panel for managing rentals

## Getting Started

### API Backend Setup

1. Clone this repository.
2. Copy `example.env` to `.env` and update the database configuration.
3. Install PHP dependencies via Composer.
4. Initialize the database with `php think migrate:run`.
5. Start the API with `php think run`.

### Building the Mini Program

1. Install the WeChat Developer Tools.
2. Import the `sourcecode/miniprogram` directory.
3. Set the request domain to your backend API URL.
4. Build and upload the mini program from the developer tools.

## License

ShopXO is released under the MIT License.
