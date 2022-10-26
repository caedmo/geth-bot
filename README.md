# trendingNFTFreeMint.js
Watches blocks consecutively (every `INTERVAL_CHECK_MILLISECONDS`) for transactions which match various transfer events, and other ERC-721 and ERC-1155 patterns within transaction logs.
Will post to Discord endpoint (every `INTERVAL_PROCESS_MILLISECONDS`) assuming the contract hasn't been previously witnessed.