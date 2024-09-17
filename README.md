# ADM
Arctic Digital Mining

### Technical Description of the GIG token on the Stellar blockchain
[Technical README](technicalspecs.md)

### Token Specifications
[Token Specs](tokenspecs.md)

### Legal Specifications
[Legal Specs](legalspecs.md)

The GIG token on the Stellar blockchain has two options at this point.  The first option is a “classic” Stellar native token that is “wrapped” with the Stellar Asset Contract, which would create a Soroban Smart Contract from the natively issued token.  The second option would be to utilize the Stellar Token Contract interface and issue a Soroban Smart Contract token with other digital security requirements such as KYC, transfer restrictions, etc.  The token may require additional smart contracts to implement KYC, AML, and other compliance checks.  All the needed smart contracts would be written, deployed, and managed with the Block Time Financial “Digital Core Platform.” 

The initial design process would include the legal team employed by ADM, Dorsey Whitney, the BTF legal team, Godfrey Kahn, and, if needed, BTF Transfer Services. BTF Transfer Services (BTFTS), a registered SEC Transfer Agent for digital securities, can provide investor management, reporting, and communications. BTFTS utilizes the BTF “Digital Core Platform” to provide these services.

The workflow for the issuance of the GIG token would be as follows:

1. —------Tranche One  
2. Legal consultation on the GIG security's type, size, and regulatory requirements.  
3. Decide on the token type, native or Soroban Token Contract.  
4. Decide on the Oracles needed for KYC and AML or wrapped native tokens.  
5. Work with ecosystem partners to deploy TESTNET oracles.  
6. —-------Move on to Tranche Two  
7. BTF will write smart contract(s) to encode the legal representation of the GIG token.  
8. BTF will deploy and test the GIG token on the Stellar TESTNET.  
9. Refine smart contract(s) as needed.  
10. Freeze the smart contract code and submit it for an audit by a third party. The audit will reveal any security shortcomings.   
11. Refine the smart contract for any deficiencies in step 5\.  
12. —-------Move on to Tranche Three  
13. BTF/BTFTS deploys the token on the PUBLIC network and any needed support oracles.  
14. Investors are onboarded to the BTF platform and provided with a third-party KYC ID  
15. Investors must either self-attest to be accredited or upload a third-party letter from a known entity to the platform.  
16. Investors execute subscription agreements.  
17. The GIG token is distributed as funds are received from investors.  
18. The BTF platform continuously monitors the smart contracts.  
19. AML checks are run on investors at intervals to be determined.  
20. Depending on the regulatory requirements, the GIG token may trade.  
21. Initial trading will occur between onboarded investors who have passed KYC/KYB/AML checks.  A settlement token will be chosen.  
22. Investors may purchase settlement tokens via the BTF investor portal application.  
23. Investors may also purchase tokens via traditional fiat rails provided on the BTF platform.  
24. The BTF platform will utilize the SEP 1, 6, 10, 24, 38, 40,  41, 42, and 43 protocols to support the investor portal and the GIG token.  
25. The GIG token contract will consult Reflector Oracles to query KYC, AML, and ACRD statutes for investors.  
26. The BTF platform will manage distributions and off-ramping.
