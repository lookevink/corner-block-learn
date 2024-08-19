Bidding on CornerBlock differs from a traditional cash offer bid by a single party in three key ways:
1. Constituent bids are variable before the finalized binding offer.
2. Bids are fully backed by capital at the time of offering.
3. Bids can carry contingencies related to the management of the target asset. 

Following is a rough breakdown of the bidding process. Document will be updated with the specific contract logic used in selecting constituent bids:

#### **1. Pre-bid**
1. **Property Submission**:
    - **Sources**: Properties are submitted through various channels, including listing agents, direct submissions by homeowners, and API partners.
    - **Initial Screening**: Each property undergoes an automated valuation model (AVM) analysis. This model factors in sales and rental comparables, neighborhood trends, and potential rental yield. Properties that meet the predefined criteria are shortlisted for the bidding process.
    - **Pre-Bidding Disclosure**: A comprehensive package is created for each property, including valuation reports, expected rental yields, market analysis, and any identified risks.

#### **2. Bid Submission**
1. **Bid Declaration**:
    - **Bid Window**: A defined bid window is opened (preliminarily 48 hours), during which investors can submit their bids. Bids are submitted directly to a smart contract, which acts as a virtual escrow.
    - **Capital Commitment**: Investors must stake 100% of their intended investment upfront. These funds are locked within the smart contract, ensuring that all bids are fully backed by capital, and refundable should the offer not be accepted. A fully backed cash offer carries significantly more legitimacy than  
2. **Bidding Structure**:
    - **Bid Amount**: Investors submit the amount they are willing to invest, along with their valuation of the property.
    - **Contingencies**: Investors can specify any contingencies (e.g., inspection outcomes, financing conditions). Bids with fewer contingencies are automatically given higher weight.
    - **Service Providers**: Investors may also suggest or vote on preferred contractors, lawyers, title insurance providers, and property managers. Preferred service providers may be a contingency if desired at a cost of reduced priority.
3. **Divergent and Variable Bids**:
    - **Handling Disparities**: The smart contract calculates a weighted average or median bid price. If bids vary significantly, the contract automatically adjusts to reflect a balanced offer, ensuring outliers do not skew the collective decision.
    - **Capital Pooling**: If the capital pool exceeds the required amount, higher bids are prioritized, and the remaining funds are either refunded proportionally or allocated to future investments as per investor preference.
    - **Variable Bids:** Investors can submit variable bids, where if the initial bid falls below the weighted average bid, investor can automate the upward adjustment. The same is true for investors whose initial bid exceeds the weighted average. Investors can specify a range, outside of witch the bid is automatically withdrawn, and fund returned.

#### **3. Bid Finalization**
1. **Bid Acceptance**:
    - **Automatic Selection**: Once the bid window closes, the smart contract evaluates all bids based on the predefined criteria (valuation, contingencies, capital commitment). The top bids are automatically selected, and a collective offer price is determined.
    - **Contingency Resolution**: If there are conflicting contingencies among top bids, the smart contract will enforce the most common or least restrictive terms to proceed with the transaction.
2. **Offer Submission**:
    - **Cash Offer Execution**: The smart contract, through the selected DAO LLC, submits the cash offer to the property seller. This offer is binding, backed by the staked capital of the investors.
    - **Escrow Initiation**: The funds within the smart contract are now locked as earnest money in a virtual escrow, signaling the seriousness of the offer to the seller. The funds can only be withdrawn if contingencies are not met later on the [[Closing|closing process]].