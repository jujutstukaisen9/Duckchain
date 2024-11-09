# DuckChain Telegram Bot


[TELEGRAM CHANNEL](https://t.me/InstantEarning169)

## Updates
- **09.10.24** Tasks are performed for all categories, not just for Partner
- **02.11.24** - add connect TON wallets

# REGISTRATIONS (BIG AIRDROP POTENTIAL)
***What is duckchain?*** Duckchain is the TON L2 powered by Arbitrum. Bringing Liquidity and users from EVM and Bitcoin ecosystem into TON : [announcements](https://x.com/arbitrum/status/1820820056965812287)

1. Visit : [https://t.me/DuckChain_bot/](https://t.me/DuckChain_bot/quack?startapp=zMootUyQ)
2. Claim card id (enter)
3. Click ***"Enter duck planet"***
4. Click to Quack ***(Desible)***
5. Refer friend to get BOX 

## Features
- Daily check-in feature to sign in.
- Opens all available boxes.
- Quacks multiple times with delay support.
- Completes available tasks.
- Proxy support for multiple accounts.
- Configurable through `config.json`.

### Example Log Output
   ```yaml
Processing account 1 / 3
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
[2024-09-15 13:22:57] Duck name: Quacky123
[2024-09-15 13:22:57] Decibels: 45 | Box Amount: 1
[2024-09-15 13:22:57] Daily Check-in successfully
[2024-09-15 13:22:57] Box opened successfully!
[2024-09-15 13:22:57] Quantity: 1 | Points: 100 | Boxes left: 2
[2024-09-15 13:22:57] All boxes opened! No more boxes left.
[2024-09-15 13:22:57] Quack 1: SUCCESS | Result: Some random result
[2024-09-15 13:22:57] Decibel Change: 10 | Quack Times: 1
[2024-09-15 13:22:57] Task successfully completed! Reward 5 Points
   ```


## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/rahatmals1/Duck-Chain.git
   cd Duck-Chain
   ```

2. **Create a virtual environment (optional but recommended)**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

   
3. **Install Dependencies:**

The bot uses Python 3 and requires some external libraries. You can install them using:

  ```bash
    pip install -r requirements.txt
  ```

### Dependencies include:

   ```requests
colorama
random
urllib
   ```

## Configuration Setup:

Create a config.json file in the project root directory:

   ```json

{
   "use_proxy": false,
   "quack_delay": 2,
   "quack_amount": 5,
   "complete_task": false,
   "account_delay": 5,
   "countdown_loop": 3600,
   "connect_wallets": false
}
   ```
- `use_proxy`: Enable/disable proxy usage (true/false).
- `quack_delay`: Time (in seconds) between quacks.
- `quack_amount`: Number of quacks to perform per account.
- `complete_task`: Enable/disable automatic task completion (true/false).
- `account_delay`: Delay (in seconds) between processing each account.
- `countdown_loop`: Time (in seconds) before restarting the bot cycle.
- `connect_wallets` - Enable/disable automatic connect TON wallets (true/false). if you want to connect wallets, add the addresses of TON wallets to wallets.txt . 
The number of wallets must match the number of accounts. 

Example of an address - `UQDi6yrASrkp3nWO0x6YCrG7xNIxgaekE_r4CEBENZ9Teqw4`

## Query Setup:

Add your DuckChain account tokens to a file named `data.txt` in the root directory. Each token should be on a new line.

Example:
   ```txt
Query_id1
Query_id2
Query_id3
   ```
### Proxy Setup (Optional):

If you enable proxy support in `config.json`, create a `proxies.txt` file in the root directory, containing a list of proxies, one per line.

Example (proxy format: username:password@host:port):

   ```graphql
user1:pass1@123.123.123.123:8080
user2:pass2@456.456.456.456:8080
   ```

## Usage
Run the script with:

   ```bash
python main.py
   ```

***The bot will:***

Load the accounts from `data.txt`.
Process each account by fetching user info, performing daily sign-in, opening all boxes, executing quacks, and completing tasks (if enabled).

## How to get tgWebAppData (query_id / user_id)

1. Login telegram via portable or web version
2. Launch the bot
3. Press `F12` on the keyboard 
4. Open console
5. Сopy this code in Console for getting tgWebAppData (user= / query=):



6. you will get data that looks like this

```
query_id=AA....
user=%7B%22id%....
```
7. add it to `data.txt` file or create it if you dont have one


## This bot helpfull?  Please support me by buying me a coffee: 

``` 0x7e0f41066ac01e80e0502353dbdfce5ae8435b0d ``` - BSC (BEP 20)

``` UQDi6yrASrkp3nWO0x6YCrG7xNIxgaekE_r4CEBENZ9Teqw4 ``` - TON

``` TFwYPZpiJ1iFQBULYCwvwVmUYAPvr1qPcR ``` - TRX (TRC 20)


