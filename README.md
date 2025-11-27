

## Project Description
A simple Solidity smart contract for issuing, verifying and revoking educational credentials on-chain. Authorized institutions (issuers) can issue credentials to recipients; third parties (employers, verifiers) can verify authenticity and issuance timestamp. Admin control allows management of authorized issuers.


## Project Vision
To provide a lightweight, auditable, and tamper-evident system for educational institutions to publish verified credentials on a public or private blockchain, improving trust and reducing fraud in credential verification.


## Key Features
- Issue credential (issuer registers a credential for a recipient)
- Verify credential (anyone can query if a credential is valid and fetch issuer/recipient/course/time)
- Revoke credential (issuer or admin can revoke a previously issued credential)
- Admin-controlled issuer authorization (admin can add/remove authorized issuers)


## Future Scope
- Add off-chain metadata storage (IPFS / Arweave) with credential hash stored on-chain
- Role-based access control (use OpenZeppelin's AccessControl)
- Support for signed credential issuance (EIP-712) so issuers can sign and recipients store credentials off-chain
- Frontend dashboard for issuers and verifiers (React + Web3)
- Batch issuance and gas optimizations (ERC-721 or ERC-1155 style tokenization)
- contract address-0x3FB2bb42852B2C069FF5CABeA43d0cBc6B8Ff388
- ![Screenshot_27-11-2025_15541_scan test2 btcs network](https://github.com/user-attachments/assets/c22d2bee-7fe5-4ca6-9904-739e4e202029)
