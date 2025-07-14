# abc-octra
abc octra
🔹 Step 1:
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
🔹 Step 2:
bun install
🔹 Step 3:
bun run build
🔹 Step 4:
bun start
click the “PORTS” tab open link under forwarded address in browser

Wallet Generated, Back up private key

Go to https://faucet.octra.network/

Paste Wallet address & claim faucet



Quest1 - Send Tokens
Video Guide - https://x.com/CryptoTeluguO/status/1940750439034802461

Step 1
pip install -r requirements.txt
Step 2
cp wallet.json.example wallet.json
Step 3
Then open the file: wallet.json

Paste your test wallet details

{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
🔹 Step 4 : Send a test transaction
Replace address with any address from explorer - https://octrascan.io/

python cli.py send --to octECeUEKyTeFMYBumubqnskCYo292LJaDi8pR7ETJB4NYz --amount 0.01

Quest2 - encrypt & decrypt Tokens
Step 1
pip install -r requirements.txt

Step 2
cp wallet.json.example wallet.json

Step 3
Then open the file: wallet.json

✅Replace with your Pvt key & octra address u generated in previous guide

{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
