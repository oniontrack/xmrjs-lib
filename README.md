# xmrjs-lib
A javascript Monero library for node.js and browsers.

### Generating a unique XMR Payment Address.
```
xmrjs.getAddress('label');
```
Optional: 'label' - Save a label to the address to pull from later.


### Checking confirmations on a XMR transaction.
```
xmrjs.getConfirmations('txid');
```
Required: 'txid' - The transactions hash.
