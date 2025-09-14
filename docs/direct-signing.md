## Direct Signing

<br>
<img style="max-width:800px" src="./web3-auth-vs-sign.jpeg" alt="Web3 auth vs sign">
<br>

#### Wallet Auth vs Direct Signing

Many web3 platforms allow users to created profiles, upload images, and interact with each other through submiting comments and reactions. Most platforms already moved away from the old email and password-based system, opting for wallet authentication, also know as 'Sign-in with Ethereum' (EIP-4361), which requires a user to sign a special login message with a private key. But here's the catch: this is still based on the same old slave tech-style account-based architecture, similar to traditional banking, where all records are unsigned and stored in a centralized database that can be altered.

Spasm provides a better alternative, where all messages are directly signed, similar to how cryptocurrencies and DeFi operate. This web3-style method offers serious advantages:
- Enhanced security because signed messages can't be tampered with since they're verified on both the server and client sides against the provided signatures.
- Users can sign messages offline and then broadcast them, additionally boosting security.
- It's more interoperable with other platforms and offers options for federation, making it more resistant to censorship.
- Signed messages can be distributed across different networks, increasing their visibility.
- There's no need to sign any login message or rely on a third party service to handle authentication.
- Better privacy as users can broadcast messages through relays.
- Users remain full custody of their own identities.
