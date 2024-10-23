[README Home](README.md)
## Technical Specifications for the GiG token

### The Stellar Blockchain
The GiG token will be issued on the Stellar blockchain.  [stellar.org](https://stellar.org) The Stellar blockchain was chosen for its regulatory status as a utility blockchain that is purpose-built for financial transactions. Industry giants such as Franklin Templeton, BlackRock, MoneyGram, and more use it.  

### Block Time Financial
Block TIme Financial provides a Digital Core with additional modules for ADM to issue and maintain tokens, onboard and maintain investors, provide a marketplace for trading the tokens, and provide the regulatory and compliance data needed for examinations.   
[Block TIme Financial](https://blocktimefinancial.com)  
BTF Ecosystem Partners
[Stellar.Expert](https://stellar.expert)  [Obsrvr](https://www.withobsrvr.com/)  [FinClusive](https://finclusive.com)  [Circle](https://partners.circle.com/block-time-financial)

### Native vs. Soroban Smart Contract
The Stellar blockchain currently has two options for issuing tokens.  Option one is a native asset issued on the blockchain with limited "smart" capabilities.  Option two is a Soroban Smart Contract following the Soroban Token Specification.  This option allows a token to be issued like an Ethereum ERC-20 token.  The Soroban contract can also add compliance mechanisms such as transfer restrictions, KYC and AML enforcement, and suitability restrictions.

### Issuance
Sections D and S of the United States Securities and Exchange Commission rules regulate the issuance of the GiG token.  Guidance at this point indicates that a token issued under these regulations shall have the following attributes:
1) To satisfy regulatory agency freeze actions, the token shall be revocable or frozen by the issuer.
2) To satisfy lost or stolen tokens, the token can be clawed back from an account by the issuer.
A US-regulated broker/dealer will be required to solicit investors and distribute GiG tokens publicly. An Alternative Trading System (ATS) will be needed to trade GiG tokens publicly to comply with SEC and FINRA rules. Private transactions are subject to lesser requirements.

### Transfer
Sections D and S of the SEC regulate the transfer of the securities.  Depending on which exemptions are used when defining the token, the GiG marketplace may implement certain transfer restrictions.  These may include but are limited to the following:
1) Country of citizenship - Reg D is for US investors, and Reg S is for non-US investors.
2) Know your customer (KYC)/KYB) - As a regulated digital security, all owners of the GiG token will be subject to KYC procedures.
3) Accreditation - Depending on the exemptions used, certain GiG holders will be have to be accredited investors.
4) Bank Secrecy Act, Anti-Money Laundering - GiG token holders must be subject to continued screening for BSA/AML/OFAC in the US and worldwide for Reg S tokens.
5) Age restrictions - All GiG purchases by natural persons must be 18.
6) Transfer of unrestricted tokens - The issuer must maintain a control record of ownership of the security.  This may be delegated to a Transfer Agent.
### Trading
Trading of the GiG token may take place in a number of different ways based on the token type issued.  Trading may be facilitated on the Stellar DEX, Swapping Smart Contracts, and other dedicated platforms and contracts, depending on the transfer restrictions on the GiG token.

## Issuance Workflow
The GIG token on the Stellar blockchain has two options at this point.  The first option is a “classic” Stellar native token that is “wrapped” with the Stellar Asset Contract, which would create a Soroban Smart Contract from the natively issued token.  The second option would be to utilize the Stellar Token Contract interface and issue a Soroban Smart Contract token with other digital security requirements such as KYC, transfer restrictions, etc.  The token may require additional smart contracts to implement KYC, AML, and other compliance checks.  All the needed smart contracts would be written, deployed, and managed with the Block Time Financial “Digital Core Platform.” 

The initial design process would include the legal team employed by ADM, Dorsey Whitney, the BTF legal team, Godfrey Kahn, and, if needed, BTF Transfer Services. BTF Transfer Services (BTFTS), a registered SEC Transfer Agent for digital securities, provides investor management, reporting, and communications. BTFTS utilizes the BTF “Digital Core Platform” to provide these services.

The workflow for the issuance of the GIG token would be as follows:
### Tranche One  
#### Description
ADM and BTF will finish the legal consultation on the GIG security's type, size, and regulatory requirements.  We will then decide on the token type, native or Soroban Token Contract.  Based on legal advice, decide on either oracles for KYC and AML or wrapped native tokens. If a native token is chosen, create issuing and distribution accounts with the correct authorization flags set.  Define the needed KYC, AML, and ACRD tokens, Stellar native or Soroban wrapper.  Issue the assets using the BTF Digital Core Platform.
#### Steps
1. Legal consultation on the GIG security's type, size, and regulatory requirements.  
2. Decide on the token type, native or Soroban Token Contract.  
3. Decide on the Oracles needed for KYC and AML or wrapped native tokens.  
4. Work with ecosystem partners to deploy TESTNET oracles.
#### Measure of Completion
Code and descriptions on the GitHub repo.  MVP contracts and assets issued on TESTNET.
#### Estimate date of completion
10/31/2024
#### Budget
Legal Fees -  $10,000  
ADM Administration -  $15,000  
BTF Administration -  $15,000  (4 Admin@$100/hr/16.5=$6,600, 1 PM@$70/hr/120hrs=$8,400 )   
##### Total Tranche 1 - $40,000 USD  

### Tranche Two
#### Description
ADM and BTF will iterate over the MVP implementation and refine the interaction between the security tokens and any KYC, AML, and ACRD tokens.  Purchasing the GiG token with USDC, EURC, and fiat will be tested with BTF’s banking partners.  When code is finished, the code base will be frozen and audited by Stellar ecosystem partners.  Approve the regulatory and compliance reports.
#### Steps
1. BTF will write smart contract(s) to encode the legal representation of the GIG token.  
2. BTF will deploy and test the GIG token on the Stellar TESTNET.  
3. Refine smart contract(s) as needed.  
4. Freeze the smart contract code and submit it for an audit by a third party. The audit will reveal any security shortcomings.   
5. Refine the smart contract for any deficiencies in step 5.
#### Measure of Completion
Code and descriptions on the GitHub repo. Completed contracts and assets issued on TESTNET. Completed Audit Report by ecosystem partner.
#### Estimate date of completion
11/30/2024
#### Budget
Legal Fees -  $10,000  
ADM Administration -  $15,000  
BTF Administration -   $15,000 (4 Admin@$100/hr/15=$6,000, 1 PM@$70/hr/110hrs=$5,600, 2 Devs@$65/hr/10hrs=$1,300)   
Audit - $10,000 (Possible Stellar Credits)  
Banking Partner -  $2,500 onboarding fee  
KYC/AML/ACRD Partner - $3,000 onboarding fee  
##### Total Tranche 2 - $55,500  

### Tranche Three
#### Description
Completely audited assets and contracts are deployed on the MAINNET. Validating nodes for ADM/BTF have been spun up. Investors have been onboarded to the platform. GiG tokens are issued as royalty streams are purchased by investors.
#### Steps
1. BTF/BTFTS deploys the token on the PUBLIC network and any needed support oracles.  
2. Investors are onboarded to the BTF platform and provided with a third-party KYC ID  
3. Investors must either self-attest to be accredited or upload a third-party letter from a known entity to the platform.  
4. Investors execute subscription agreements.  
5. The GIG token is distributed as funds are received from investors.  
6. The BTF platform continuously monitors the smart contracts.  
7. AML checks are run on investors at intervals to be determined.  
8. Depending on the regulatory requirements, the GIG token may trade.  
9. Initial trading will occur between onboarded investors who have passed KYC/KYB/AML checks.  A settlement token will be chosen.  
10. Investors may purchase settlement tokens via the BTF investor portal application.  
11. Investors may also purchase tokens via traditional fiat rails on the BTF platform.  
12. The BTF platform will utilize the SEP 1, 6, 8, 10, 24, 38, 40,  41, 42, and 43 protocols to support the investor portal and the GIG token.  
13. The GIG token contract will consult Reflector Oracles to query KYC, AML, and ACRD statutes for investors.  
14. The BTF platform will manage distributions and off-ramping.
#### Measure of Completion  
Code and descriptions on the GitHub repo. Completed contracts and assets issued on MAINNET.

#### Estimate date of completion  
12/31/2024
#### Budget  
Legal Fees -   $15,000  
ADM Administration -   $15,000   
BTF Administration -   $15,000 (4 Admin@$100/hr/17=$6,800, 1 PM@$70/hr/80hrs=$5,600, 2 Devs@$65/hr/20hrs=$2,600)   
Banking Partner -   $1,000 (Ongoing Fees)  
KYC/AML/ACRD Partner - $8,500 (Usage Fees) (KYC Fees for Investors, KYB Fees for Businesses, Accredited Audit Fees per Investor)  
##### Total Tranche 3 - $59,500  

## Total Budget - $150,000  

##### Disclaimer(s)
[ADM Disclaimer(s)](admdisclaimer.md)  
[BTF Disclaimer(s)](btfdisclaimer.md)
