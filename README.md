# Fintech Finder

![wallet](images/blockchain_wallet.jpg)

This is an application that allows customers to find fintech professional from a list of candidates, hire them, and pay them.  You will need to create a `.env` file which holds your `MNEMONIC` phrase.  You will also need to install streamlit to run the application and Ganache.  To deploy the web app, run `streamlit run fintech_finder.py` in your terminal.

---

## Technologies

To install Streamlit library, open your `terminal` window and be sure to be in your `dev` virtual environment.  Run the following command
`pip install streamlit`.

Follow the instructions on the [Ganache webpage](https://www.trufflesuite.com/ganache) to download and install this tool on your local machine.

---

## App Overview
Once you've created your dashboard, it should appear as shown:

![dashboard](images/dashboard.jpg)

After selecting a candidate and number of hours, click `Send Transaction`.  Your transaction will be verified as seen on your streamlit `Dashboard`, Ganache's `Accounts` tab and `Transactions` tab as shown:

![transaction](images/send_transaction.jpg)
![index](images/index.jpg)
![transaction](images/transaction.jpg)

Your streamlit dashboard will also update with your current eth balance as shown.

![balance](images/dashboard_balance.jpg)

---

## Contributors
Christina San Diego