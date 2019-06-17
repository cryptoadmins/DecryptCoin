# DecryptCoin
This repo holds PrivateKey decryption Sequence code for BTC and ETH
## Building and installing
1. cd to `~/go/src/github.com/cryptoadmins/DecryptCoin
2. install required packages with `go get`
3. build the executable with `go build`
4. include the executable in `$PATH`: `sudo cp decryptcoin /usr/local/bin`

## Usage
For generating keys, run:

```bash
decryptcoin btc <page number>
decryptcoin eth <page number>
```

For searching by private key, run:
```bash
decryptcoin btc-search <btc private key>
decryptcoin eth-search <eth private key>
```
