# Multichain Demo

This demo originally created here: [https://github.com/Kunstmaan/hands-on-with-multichain](https://github.com/Kunstmaan/hands-on-with-multichain)

Belong to this great article about Multichain: [https://labs.kunstmaan.be/blog/hands-on-with-multichain](https://labs.kunstmaan.be/blog/hands-on-with-multichain)

Since it not maintained, I clone it in this new repository and edit docker-compose to make it one single command running


# Usage

- Install Docker on your machine.
- Clone this repo and cd into it
```bash
    git clone https://github.com/sadok-f/multichain-demo.git
    cd multichain-demo
```
- Setup the environment
```bash
   ./setupEnvironment.sh
```
- You can access MultiChain Explorer: [http://localhost:2750/](http://localhost:2750/)
- Run the exchange example
```bash
   ./runExchange.sh
```
- Run the document example
```bash
   ./runDocument.sh
```
