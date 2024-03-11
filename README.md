# vanity-eth
Node.js ETH vanity address generator

## Usage

clone from github

```bash
$ git clone https://github.com/songzhihao/create-liang-wallet-addr.git
```
Install dependencies

```bash
$ npm install
```
Run

```bash
$ node eth.js
```

The output will be written to output.txt.

## Using PM2
Install PM2

```bash
$ npm install pm2 -g
```
Starting a Node.js application in cluster mode that will leverage all CPUs available:

```bash
$ pm2 start eth.js -i <processes>
```
`<processes>` can be `'max'`, `-1` (all cpu minus 1) or a specified number of instances to start.

   
