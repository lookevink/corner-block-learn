#### **1. Inspection**
1. **Inspection Trigger**:    
    - **Event Trigger**: Once the cash offer is accepted by the seller, the smart contract automatically triggers the inspection phase.
    - **Appointed Inspector**: The inspector, who may have been pre-selected or voted on by investors, receives a notification to conduct the inspection. The smart contract holds a portion of the pooled capital in escrow to pay for the inspection service.
    - **Inspection Results**: The inspection report is uploaded to the smart contract platform. If significant issues are found, the contract triggers a vote among investors to determine whether to proceed, renegotiate, or withdraw the offer.
    - **Trustless Operation**: The smart contract automates payment to the inspector upon submission of the report, eliminating the need for manual intervention.
2. **Title Search**:
    - **Event Trigger**: After the inspection, the smart contract automatically initiates a title search with the appointed title company or attorney.
    - **Clear Title Verification**: The title search results are uploaded to the platform. If any issues such as liens or encumbrances are found, the smart contract triggers an investor vote on how to proceed.
    - **Automated Resolution**: If the title is clear, the smart contract progresses to the next stage. If issues are unresolved within a specified time frame, the smart contract may automatically cancel the transaction and return funds to investors, ensuring protection against title risks.
3. **Final Walk-Through**:
    - **Event Trigger**: The final walk-through is triggered a few days before closing, ensuring the property is in the agreed-upon condition.
    - **Investor Delegation**: Investors may delegate a representative to conduct the walk-through, or vote to waive this step if deemed unnecessary.
    - **Walk-Through Results**: The representative uploads the findings to the platform. If any discrepancies are found, the smart contract triggers a vote on whether to renegotiate or proceed.
#### **2. Document Preparation and Review**
1. **Closing Document Preparation**:
    - **Event Trigger**: Upon successful completion of due diligence, the smart contract triggers the preparation of closing documents by the title company or attorney.
    - **Document Upload**: Closing documents are uploaded to the platform, where investors can review them.
    - **Automated Review Period**: Investors are given a predefined period (e.g., 48 hours) to review and approve the documents. Approval is automated if a majority vote is achieved, or the smart contract proceeds with default terms if no significant objections are raised.
2. **Final Investor Approval**:
    - **Event Trigger**: Before finalizing the closing, the smart contract triggers a final vote among investors to approve the closing.
    - **Weighted Voting**: Votes are weighted based on each investor’s capital contribution. The smart contract enforces the majority decision to either proceed or halt the closing process.
    - **Preventing Bad Actors**: To protect against bad actors with larger bids overwhelming smaller investors, the smart contract can implement a capping mechanism where no single investor's vote can exceed a certain percentage of the total voting power. This ensures a balanced decision-making process.