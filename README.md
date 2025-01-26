# Layer Edge Auto Ping Node

![banner](./img/image.png)
- website : https://dashboard.layeredge.io/

## Features

- **Auto Run Node**
- **Auto Create Accounts**
- **Auto Referrall**
- **Support Proxy usage**

## Prerequisites

- Node.js installed on your machine


## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Zlkcyber/LedgeBot.git
    cd LedgeBot
    ```

2. Install the required dependencies:
    ```sh
    npm install
    ```
3. paste proxy in `proxy.txt`:
-  format `http://username:password@ip:port` or `socks5://username:password@ip:port`
    ```sh
    nano proxy.txt
    ```
4. Run the script:
    ```sh
    npm run start
    ```

## Additional feature 
- ### Auto Referral 
    ```sh
    npm run autoref
    ```

## All wallets information saved at `wallets.json`


## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the [MIT License](LICENSE).