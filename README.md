# Klone Api Spec / Description

---

An open source client library that integrates the following from the klone service: 

- NFT aggregation and NFT Wearables aggregation
    - List all NFTs available
    - Custom queries on each aggregation map
- NFT details
    - Who owns the NFT
    - NFT status from the discovery oracle (reputation, stars etc..)
    - Wearables currently equipped
        - Each wearable will have its own details
    - The NFT 3D model and its related vectors
    - All NFT events status change
    - NFT Whereabouts in the blockchain
    - All NFT Blockchain functionality
        - Participate in events
        - All available contract functions
    - (Optional): NFT Whereabouts in the metaverse if discovery set to public
        - For example: Currently live on blocktopia universe
    - (Optional): Estimated worth if available
        - Includes the wearables worth and reputation/status rarity
- NFT Wearables details
    - Who owns the NFT
    - How NFT available/minted
    - Wearable NFT 3D model
    - All NFT events
    - List of owners
    - All NFT Blockchain functionality
        - Transfer NFT
        - Equip NFT
        - All available contract functions
- NFT Marketplace
    - List all items available for sale
    - Listing details
        - Price required for the purchase
        - Quantity of the NFTs included in the listing
        - Type of selling:
            - Can be ERC1155 for ERC1155 which can be interpolated as a Trade instead of a Purchase
    - All NFT Blockchain functionality
        - Purchase a listing
        - Submit a listing
        - Query a listing details
