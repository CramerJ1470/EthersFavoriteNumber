# EthersFavoriteNumber
Setting favorite number Ganache 
Usage

1. Run your ganache local chain, by hitting `quickstart` on your ganache application

> Save the workspace. This way, next time you open ganache you can start the workspace you've created, otherwise you'll have to redo all the steps below.

2. Copy the `RPC SERVER` sting in your ganache CLI, and place it into your `.env` file similar to what's in `.env.example`.

<img src="./img/ganache-http.png" alt="ganache" width="500"/>

`.env` Example:

```
RPC_URL=http://0.0.0.0:8545
```

3. Hit the key on one of the accounts, and copy the key you see and place it into your `.env` file, similar to what you see in `.env.example`.

<img src="./img/ganache-key.png" alt="ganache" width="500"/>

<img src="./img/ganache-private-key.png" alt="ganache" width="500"/>

`.env` Example:

PRIVATE_KEY=11ee3108a03081fe260ecdc106554d09d9d1209bcafd46942b10e02943effc4a

4. Compile your code

Run

```
yarn compile
```

You'll see files `SimpleStorage_sol_SimpleStorage.abi` and `SimpleStorage_sol_SimpleStorage.bin` be created.

5. Run your application

```
node deploy.js
```
