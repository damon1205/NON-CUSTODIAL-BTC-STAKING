## Non-Custodial BTC Staking Platform ( CoreDao )

# Overview
This project implements a non-custodial BTC staking platform that allows users to stake their assets while maintaining control over their private keys. The platform is built using a multisig wallet solution powered by Asigna and leverages cross-chain communication for optimal security and efficiency. The project ensures transparency by keeping both on-chain and off-chain records of user holdings and staking status, allowing users to verify their data anytime.

# Features

- Admin Wallet: The admin configures a multisig wallet using Asigna to manage user funds securely.
- Staking Workflow: The staking process involves a multi-step workflow that uses existing Layer-1 blockchain features for staking, unstaking, and earning yields.
- User Data: Asset peg values are stored both on-chain and in an off-chain database. Users can log in to verify their holdings and staking status.
- Cross-chain Communication: Uses relayers for fast, gas-optimized cross-chain communication between CoreDao and the multisig wallet.
- User State: User state is maintained on both the Core chain and the database, including important data such as Initial Value (IV), wallet addresses, staked amounts, and Total Value Locked (TVL).
- Immutable IV: Once an IV is created for an asset, it cannot be manipulated or reversed by the user or the protocol.
- Cross-chain Asset Identification: The platform uniquely identifies staked assets across Core and Stacks chains, along with their historical peg values.
- Future Updates: Users must unstake and withdraw funds from version 1 before staking again in version 2 upon release.

# Use-Case Description
- Staking
Users holding a supported asset can initiate staking by depositing capital.
The asset will remain in the user's wallet, but the base capital will be staked on the platform.
Admin configures the staking period (e.g., 2 weeks, 1 month, etc.).
- Earning Yields
Users earn daily yields while the staking cycle is active.
When a staking cycle ends, there may be a gap of 1-2 days before the next yield cycle starts.
Users can choose to continue staking and earning yields in future cycles.
- Recharge
Users can increase their staked capital or TVL at any time.
New yields will start in the next staking cycle after the capital increase.
- Unstaking
Users can opt to end their staking before the current cycle ends and withdraw their staked capital.
Upon unstaking, users will retain their base asset, but the TVL will be reset to 0.

# Diagram
![image](https://github.com/user-attachments/assets/2242d4e0-f60a-47d8-b580-146d903470f9)
![image](https://github.com/user-attachments/assets/7d44dee4-f35e-410b-b4f3-2a25edef2d48)
![image](https://github.com/user-attachments/assets/90ff3c4a-3ead-4021-870b-df561de5359e)

If you are interested in building this project, please contact to me.


Telegram Immutal0 (https://t.me/Immutal0)


