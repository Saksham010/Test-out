
# Wraprotocol

## How to Start the Wraprotocol Dapp:

Prerequisites:

1. Node 
3. Git

Step 1:

```shell
git clone repo
```

Step 2:

```shell
cd repo
npm install
```

Step 3:

Open the project folder in Your favourite Ide.

Step 4:

Make a .env file in your Root folder and run this command

```shell
npm install dotenv --save
```

Step 4:

Sign up for a free [Piñata](https://pinata.cloud/signup) account and verify your email.

Create your Piñata API key:
- Navigate to https://pinata.cloud/keys
- Select the "New Key" button at the top
- Set the Admin widget as enabled
- Name your key

<b> Make sure to save your API key and secret in a safe place</b>

Step 6:

Sign up for your free [Alchemy](https://dashboard.alchemyapi.io/signup/?a=dabb74c129) account.

- Navigate to the "create app" button in the "Apps" tab
- Fill in the details on the popup to get your new key
- Choose "Polygon" as the chain and "Mumbai" as the test network.
- Copy the <b>Api Key</b>, and store it somewhere safe.

Step 7:

Open the .env file and these variable there.

```shell
REACT_APP_ALCHEMY_API_URL="<YOUR_API_URL>"
REACT_APP_PRIVATE_KEY="<YOUR_PRIVATE_KEY>"
REACT_APP_PINATA_KEY="<YOUR_PINATA_KEY>"
REACT_APP_PINATA_SECRET="<YOUR_PINATA_SECRET>"
```

<b> <YOUR_PRIVATE_KEY> can be found by exporting your Private key on Metamask </b>

Step 8: 

Once done, Run the below command to open the dapp on your ocahost:3000
  
```shell
  npm start
```
  
  
  
  
  
