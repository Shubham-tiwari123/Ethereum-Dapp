
# Election - DAPP
It is a decentralized application, or Dapp, on the Ethereum Network.

## Dependencies
Install these prerequisites 
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

### Steps to run the project
1. Clone the project

2. Install dependencies

        $ cd election
        $ npm install

3. Start Ganache

        For Ubuntu:
        - Right click on downloded file
        - Goto permissions tab and click the check box infront of execute
        - Close the dialog box
        - Again right click on file 
        - Click on Run
        
4. Compile & Deploy Election Smart Contract
        
        $ truffle migrate --reset
        
    You must migrate the election smart contract each time your restart ganache.

5. Configure Metamask

    Before making any configuration of metamask make sure ganache is running

    - Install metamask extension for chrome
    - Create a new account
    - Change the network to connect locally with genache
        - Click on down arrow and select Custom RPC 
        - In URL box write: http://loclhost:7545 and save it
    - Import an account from ganache
        - Go to ganache.
        - Click on the key icon infront of any account
        - Copy the private key
        - Come back to metamask
        - Click on the top right corner icon
        - Click on import account
        - Paste the private key and click on import

6. Run the Front End Application
    
        $ npm run dev
    Visit this URL in your browser: http://localhost:3000

    If you get stuck, then click on metamask->setting->connections->click 
    on localhost.
     

