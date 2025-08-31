Bitcoin Network Simulator

An interactive, front-end simulation of a Bitcoin-like blockchain network. This project, built with pure HTML, CSS, and JavaScript, visualizes key blockchain concepts like Proof of Work (PoW) mining, transaction propagation, and the network's decentralized topology. It serves as an educational tool for anyone interested in understanding how a distributed ledger operates.
Features

    Interactive Network Visualization: A dynamic view of a multi-node network. Nodes are connected by lines, representing peer-to-peer connections.

    Proof of Work (PoW) Mining: Start the mining process to watch a random node solve a cryptographic puzzle and add a new block to the chain. The mining difficulty can be adjusted to observe its impact on the process.

    Transaction Management: Create and send transactions between simulated user wallets. Transactions enter a Mempool (Memory Pool), waiting to be included in the next mined block.

    Real-time Stats: Monitor live network statistics, including block height, mining difficulty, and total Bitcoin supply.

    Dynamic Controls: Add new nodes to the network, generate new user wallets, and control the simulation speed with sliders.

    Blockchain Explorer: Click on any node to view its copy of the blockchain and inspect individual blocks and their transactions.

    Wallet Simulation: Track balances for both user wallets and mining nodes, with a clear distinction between confirmed and pending amounts.

How to Use

The simulation is a single HTML file and requires no setup. Simply open index.html in any modern web browser.
Key Interactions

    Start Mining ⛏️: Manually triggers one of the nodes to mine pending transactions in the mempool.

    Create Transaction 💸: Use the form to send Bitcoin between wallets. The transaction will be propagated across the network.

    Add New Mining Node ⚡: Adds another peer to the network. New nodes automatically connect to a few existing ones to maintain a healthy network.

    Start Auto System 🎲: This mode automates the process by creating random transactions and mining new blocks at a continuous pace, allowing for a hands-off demonstration.

    Difficulty Sliders: Adjust the difficulty to simulate changes in the network's hash rate. A higher difficulty requires more computational work.

Technical Details

This project is built as a self-contained web page with:

    HTML5: Provides the document structure.

    CSS3: Handles all the styling, including the dark, cyber-themed aesthetic and various animations.

    Vanilla JavaScript: The core logic is implemented in a BitcoinSimulator class, which manages all aspects of the blockchain and network. It uses a simplified hashing function to demonstrate the principles of Proof of Work.

Please note that this is an educational tool and not a functional cryptocurrency. The cryptographic functions and network logic are simplified to make the concepts visually intuitive and easy to understand.

If you have benefit from this simulation, can buy me a coffee here: bitcoin:BC1QEU90WULM098NST43RY88H8FM5ZRTGF7PXSYGV6.