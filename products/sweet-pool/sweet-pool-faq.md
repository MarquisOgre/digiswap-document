# Sweet Pool FAQ & Troubleshooting

## Troubleshooting

### **I can't find the Sweet Pool I was staking in!**

You should be able to find the Sweet Pool under the “Finished” tab on the DGSweet Pools page. 

By selecting “Staked Only”, it will make it easier to find your assets.

### **Why can’t I unstake my tokens from a Sweet Pool?**

If you are unable to unstake from the Stake Cake, Earn DIGIS pools, please check to make sure that you haven’t sold the SYRUP tokens in your wallet. This token acts as a \`proof of ownership\` over your DIGIS in the Manual DIGIS pool. 

### **Why did my earned tokens go to zero after staking/unstaking?**

Don’t worry! They’re in your wallet already.

Whenever you stake or unstake from a Sweet Pool or farm, your earned tokens get harvested and sent to your wallet at the same time.

## **General Questions**

### How is APR for DGSweet Pools calculated?

> Sweet Pool APR = Annualized rewards \(USD\) / User funds staked in Sweet Pool \(USD\) \* 100

As a basic example, let's take a 60-day pool with 300,000 USD worth of rewards, and 3,000,000 USD worth of DIGIS staked in it.

The APR fluctuates as more DIGIS is staked by users, and as the price of DIGIS, and the reward token, vary.

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"><b>Calculation</b>
      </th>
      <th style="text-align:left">Amount</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Total rewards to distribute (USD value)</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">300,000 USD</td>
    </tr>
    <tr>
      <td style="text-align:left">Distribution period</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">60 days</td>
    </tr>
    <tr>
      <td style="text-align:left">Daily distribution</td>
      <td style="text-align:left">300,000 / 60 =</td>
      <td style="text-align:left">5,000 USD daily</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Annualised rewards (USD value)</b>
      </td>
      <td style="text-align:left">5,000 * 365 =</td>
      <td style="text-align:left"><b>1,825,000 USD</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Value of DIGIS staked by users in pool (USD value)</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>3,000,000 USD</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>APR</b>
      </td>
      <td style="text-align:left">(1,825,000 / 3,000,000) * 100 =</td>
      <td style="text-align:left">
        <p></p>
        <p><b>60.833% APR</b>
        </p>
      </td>
    </tr>
  </tbody>
</table>

### **What does the “End” number on my Sweet Pool refer to?**

This shows the amount of blocks left until the rewards for that pool stop being distributed. Once the pool has reached that block, you should unstake your tokens, because you won’t be receiving any rewards after that.

### **Where do the rewards from DGSweet Pools come from?**

There are three main types of DGSweet Pools.

1. Stake DIGIS, earn DIGIS
2. Stake DIGIS, earn other tokens. 
3. Stake other tokens, earn DIGIS

The rewards for the "Stake DIGIS, earn DIGIS" DGSweet Pools come from the [DIGIS emissions](https://docs.digiswap.finance/tokenomics/cake/cake-tokenomics). Each block, a number of DIGIS tokens are allocated as rewards for these pools.

The rewards for the "Stake DIGIS, earn other tokens" type are provided by the project teams who sponsor a Sweet Pool.

For the "Stake other tokens, earn DIGIS" type, the Digiswap treasury buys back DIGIS from the market to distribute as rewards. These pools are funded by Digiswap, not by the projects themselves.

### What’s SYRUP Token?

Digiswap’s SYRUP Token is deposited in your wallet when you interact with the **Manual** “Stake DIGIS, Earn DIGIS” Sweet Pool. It's not staked for 

It’s basically an IOU that shows how much DIGIS you’ve staked in the pool.

It’ll be returned automatically when you unstake your DIGIS from that pool.

{% hint style="warning" %}
Don’t sell your SYRUP tokens! You need to return your SYRUP to unstake your DIGIS from the Manual DIGIS pool. The amount of SYRUP you return must be the same as the amount of DIGIS you unstake.
{% endhint %}

