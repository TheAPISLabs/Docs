# Token Utilities

As referenced prior, the API token is designed to be superfluid, utilized for on-chain governance, off-chain governance (namely future product development), and five staking derivatives to ensure incentive alignment among all participants in the API protocol, namely the protocol’s service providers— **API Governors, API Nodes and Gateways, API Rollup Validators, and API Dispute Resolvers**—and its customers.

### **On-Chain Governance Rights**

$API holders hold meta-governance rights over the entirety of the $API protocol. This is provided via the Governance Module, which governs all other API Smart Contracts, including the Governance Module itself (designed modularly), the Gnosis Multi-Signature Wallet that signs transactions on behalf the API Treasury, the $API ERC20 Contract, and API Staking Contracts.

![Figure 3.2.1: On-chain Governance Rights.](../../.gitbook/assets/image\_upimage\_upload\_load\_0.png)

Those that own or earn $API tokens maintain a voice over the entire APIS protocol and are incentivized to continue to govern through additional $API through the ve-API program, wherein a portion of future $API is given to those who stake and utilize $API to govern the protocol.

### **Treasury Governance Rights**

After the initial API distribution is complete, all Treasury Governance Rights will be held by API token holders. The APIS Treasury will accrue numerous assets, such as intellectual property, trademarked brands, partner DAO tokens, tangible assets (such as servers and databases), stores of value (such as Ether and stablecoins, accumulated through the selling of APIS products), and the API token itself.

While there will be a specific Working Group to manage the Treasury, whose job will be to write Proposals for the allocation of the Treasury, all Treasury decisions must be approved by $API holders. Additionally, $API holders can vote to remove members from the Treasury Working Group.



![Figure 3.2.2: API Treasury Holdings.](../../.gitbook/assets/image\_upimage\_upload\_load\_1.png)

### **Product Governance Rights**

API’s Future Product Iterations and Launches. Ideas can be brought forth both the APIS Core Team and the greater APIS Community, which consists of both $API token holders and non-token holders. While non-token holders can participate in the Discord and Governance Forum (operated on Discourse if desired), they cannot vote on Snapshot with holding the $API token. Below is the sequence of events for Product Proposals, from start to finish. Proposers and voters may receive additional $API as rewards from the API Community Treasury.&#x20;

![Figure 3.2.3: API Product Governance.](../../.gitbook/assets/82cca54f-7345-44e7-85a7-be5bf93cdad0.png)

### **The Ability to Act as a Service Provider to the API Network**

There are five primary service provides to the API Network: API Governors, API Nodes and Gateways, API Rollup Validators, and API Dispute Resolvers. It is imperative that all API actors who could harm the network have API at stake, due to the well-researched nothing-at-stake problem set \[27].**Acting as an API Governor**API Governors stake API in order to vote in the Governance Module, receiving additional API through the ve-API program. Governors receive the same amount of API, proportionate to their API stake, regardless of whether their vote was ratified or rejected, in order to incentivize all Governors to adequately express their beliefs on the future of the protocol. There is no threshold of API holdings to act as an API Governor.

### **Acting as an API Node or Gateway**

API Nodes and Gateways must stake a threshold—initially set to 10,000 API but to be ratified by API Governors—of $API tokens to become a service provider on the API Network. The purpose of their stake is to allow for slashing events, should the service provider act maliciously via generating faulty APIs to our end-users. Slashing events are brought forth and settled by API Dispute Resolvers via the Dispute Resolution Factory.

### **Acting as a Dispute Resolver**

When the accuracy of a service providers’ endpoint is disputed via the Dispute Resolution Factory, the party that initiates the dispute must also stake a threshold of API— initially set to 500 API but to be ratified by API Governors—on their claim. All $API slashes from either a faulty endpoint or faulty dispute is re-distributed to the participants who stood on the correct side of the dispute.

### **Acting as an API Rollup Validator**

As the number of API Nodes and the Gateways grows, the API Protocol will launch its own customized rollup, in order to ensure that all API Nodes (Nodes send data to Gateways; Gateways are merely a front-end) maintain the same state of the API Network. Validators of the API Rollup must also stake a threshold of API—initially set to 10,000 API but to be ratified by API Governors—which can be slashed (should the validator produce a faulty block), also through the Dispute Resolution Factory.

### **The Ability to Receive Discounted API Products**

Consumers of goods and services from the API network have the ability to receive discounts on products purchased from the network. Consumers receive X% Discount on all products, where X varies per product but is always equal to the operational profit of the API DAO. Thus, the operational profit is shifted fully back to the token holder—API products are created and distributed at cost to API holders.&#x20;

### **DISCOUNT = OPERATIONAL PROFIT = MARKET PRICE – COST OF GOODS SOLD**

There must be a threshold of tokens held to earn the discount (i.e. $1 USD of $API should not be enough). Additionally, this threshold of tokens must be staked, to prevent certain variants of Sybil attacks (an example of a Sybil attack: if want to buy 5 NFTs, I could make 5 single orders using the same $API each time). While tokens must be staked in advance of purchasing, the threshold is measured in real-time at the time of the purchase (using an on-chain oracle, i.e. Uniswap V3). $API staked to reach the threshold for any purchase can only be used once a month, where the threshold equals the market price of the purchase (i.e. subscription, trading fees, etc.).

### **THRESHOLD = MARKET PRICE OF ORDER**

All Stakers—both service provider and stakers—will also be able to execute all Governance Rights via the superfluid design of our API staking contracts. Thus, we will not only use Snapshot for token voting, but also build voting directly into our native website, alongside staking functionality.

![Figure 3.2.4: Superfluid API Composition.](../../.gitbook/assets/a5c2d29a-f447-41bc-a9ab-ce97f372daa4.png)

Because a majority of tokens today are unmined, additional API tokens will be distributed via a usage mining program derived the usage of the protocol itself, namely through fees paid, as money is the most objective measure of **** usage.
