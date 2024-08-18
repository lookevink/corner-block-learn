## Problem

[[Single family rental]] (SFR), despite its risk-adjusted & stable return profile, is often inaccessible to majority of middle income earners for the following reasons:

1. **High Initial Capital Requirement:** Purchasing, renovating, and placing tenant in an SFR property requires high upfront investment, preventing incremental portfolio accumulation.
2. **Lack of Liquidity:** Investing in SFR properties ties up a substantial amount of capital, making it difficult for middle-class investors to access funds quickly if needed for other financial obligations.
3. **Competition from Institutions** Middle-class investors may face stiff competition from institutional buyers in hot markets, which see strong cash offers made possible through economies of scale.
4. **Demanding Property Management:** For working professionals, managing a rental property alongside a full-time job can be overwhelming, leading to potential mistakes or neglect that can hurt rental income and property value.
5. **Lack of Diversification:** Investing in a single SFR property concentrates risk in one asset, making it difficult for middle-class investors to spread risk across multiple properties or markets without significant additional capital.
6. **Low Yields:** Achieving profitable returns requires constant market monitoring, deep market knowledge, and the ability to make responsive and tactical bids, which is prohibitively time-consuming.

## Solution

CornerBlock plans to democratize SFR investment to middle income earners with:

1. **Property Tokenization:** Tokenization enables fractional ownership, reducing upfront capital requirements to generating SFR income.
2. **Secondary Market:** On-chain secondary market for tokenized assets enables fractional SFR investors to access liquidity through peer-to-peer transactions, allowing for cheaper and greater flexibility.
3. **Fractional Cash Offers:** Pooling funds enables multiple investors to make competitive & all cash bids on properties, as investors can unlock greater capital efficiency by adjusting the risks and amount of upfront investment.
4. **Decentralized Autonomous Organizations:** Fractional owners can vote to choose property management professionals, or rely on the management of other fractional owners, at agreed upon fees. Investors can choose to be as involved or passive in the process.
5. **Automated Portfolio Diversification:** Investors can diversify by purchasing fractional ownership in multiple properties across various locations and types, reducing concentration risk. Smart contracts enable automatic distribution of investments based on individual risk preferences, ensuring a balanced portfolio with minimal effort.
6. **Vetted Off-market Properties:** Community or agent sourced [[Off-Market Properties|off-market properties]], completed with AI-powered rental & valuation financial analysis, guarantees high yielding properties with transparent financial assumptions.

## Implementation
CornerBlock ("CB") is building [[Fractional Cash Offer|fractional cash offer]] marketplace for [[Single Family Rental|single family rental]] operated on [Solana](https://solana.com). Participants pool capital to bid on properties using [PYUSD](https://www.paypal.com/us/digital-wallet/manage-money/crypto/pyusd) or [USDC](https://www.circle.com/en/usdc), held by [[Smart Contract|smart contracts]] that make cash offers on off-market properties. After acquisition and tokenization, holders assign, vote, and manage property and receive pro rata rental payment.

#### Typical Lifecycle:
1. CB sources off-market deals through the following channels:
	1. [[Listing Agent]] submission
	2. Direct submissions by homeowners
	3. API partner submission
2. Properties go through a [[Automated Valuation Model|automated valuation model]] that factors in sales and rental comparable market analysis. Properties that do not meet yield or other requirements are filtered; rest are listed on the market place.
3. CB investors review and bid on the property at offer prices, investment amounts, & terms:
	1. Investors bid by sending tokens to a wallet held by smart contract, which serves as a virtual escrow.
	2. Once sufficient fund is pooled, smart contract send a signed cash offer through one of the available [[DAO LLC|DAO LLCs]].
	3. Investors who have staked their tokens may vote to appoint attorneys, inspectors, contractors, property manager, and title companies, if desired.
	4. Take a closer look at the bidding process [[Bidding|here]].
4. When an offer is accepted, the property enters closing, with the following general steps
	1. **Inspection:** Assesses property condition and identifies potential issues.
	2. **Title Search:** Confirms clear ownership and checks for liens or encumbrances.
	3. **Final Walk-Through:** Ensures the property is in agreed-upon condition.
	4. **Document Preparation:** Title company or attorney prepares closing documents.
	5. **Funds Transfer:** Smart contract deploys the remainder of the offer amount
	6. **Deed Recording:** Officially transfers ownership by recording the deed with local authorities.
5. After closing & renovation if applicable, the delegated managers run day-to-day operations on the properties, including tenant placement, rent collection, maintenance, and financial reporting.
6. Token holders vote on larger issues, including property sales, major renovations, change in management, etc.
7. If desired, individual investors can sell their tokens to other investors. Theoretically, a tokenized asset never needs to be listed on market again, drastically reducing the costs of ownership transfer.