# Introduction

- QNT (Quanta Network Token) is a breakthrough cryptocurrency token. By design, the total quantity of QNT currently and permanently amounts to 120 billion tokens.  During last year's token sale, purchasers bought 9.53% of the total QNT, while the remaining QNT is held by Quanta PLC, a privately held blockchain company headquartered in Douglas, Isle of Man. QNT is governed by the globally respected and stringent Isle of Man Financial Services Authority (IOMFSA).

- QNT will be transferable among QNT-eligible registered token holders only as governed by the built-in transfer function of QNT’s smart contract. Eligible registered token holders will be able to exchange QNT for major cryptocurrencies thanks to Quanta’s integration with one of the blockchain industry's most well-known and trusted Europe-based exchange services.

- QNT holders have the following rights:

    * Can apply with Quanta Technology Limited (QTL) to become a QTL Affiliate. QTL Affiliates can market the sell Quanta lottery tickets to earn QNT. A bonus for QTL Affiliates is paid out in QNT and subject to the Affiliate’s performance and other relevant requirements and at the discretion of QTL

    * Receive rewards (compensation) in the form of QNT as well as Ethereum (ETH)

# Balance function

Quanta PLC added the famously-used balance function source code into our QNT smart contract source code to provide a convenient way to check token balance to our QNT holders. You can check your token balance by using either Quanta Wallet or any Ethereum blockchain Wallet. 

```js
// This variable keeps balance of account
mapping(address => uint) public balances;

// This function displays the balance of a particular account
function balanceOf(address _owner)
    public
    constant
    returns (uint balance)
{
    return balances[_owner];    
}
```
