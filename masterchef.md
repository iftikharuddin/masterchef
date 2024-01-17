## Masterchef

- 🤑 Build Your Own DeFi Staking dApp - P1 - Masterchef Smart Contract Logic
    - ref @ https://youtu.be/ySBiVZaub1Q?list=PLLkrq2VBYc1Y4kL1lr-W_qwgI8De6M2BC
    - Masterchef Smart Contract handles the staking, time of staking and based on the timeframe it rewards
    - Let say you stake X amount so how much rewards you will get? This is handled by Masterchef Smart Contract
    - Block generation time is approx 3 seconds. Binance can process upto 160 trx per second
- 🤑 Build Your Own DeFi Staking dApp - P2 - Masterchef Contract Storage
- 🤑 Build Your Own Defi Staking dApp - P3 - Masterchef Contract Add Staking Pools
    - adding pools to smartcontracts
    - do check for duplicate check in adding pool and updating?
    - multiplier should be mutable
- 🤑 Build Your Own Defi Staking dApp - P4 - Masterchef Mint Reward Tokens
    - lastRewardBlock - the last reward block value is that block number that we are going to store in the msg of smartcontract
    - everytime there is staking, unstake 
    - multiplier = (block.number - lastRewardPerBlock) * bonus_multiplier
    - totalReward = multiplier * tokenPerBlock * poolAllocation / totalAllocation
    - if you want to give some rewards to dev or anyone it will be like this
    - devfee = totalReward / 10 (the percentage of rewards dev will get)
    
- Now let's calculate the rewards per share


    

