<h1>Blockchain basics</h1>


 <h3><i>Smart Contracts</i></h3> <p>Are a set of instructions executed in a decentralized way without the need for a centralized or third party intermediary, stored inside a blockchain, they are immutable (<i>meaning that once they are created, they cant never be changed again</i>) and distributed (<i>meaning that the output of the contract is validated by everyone on the network, so if someone on the network forces the contract to reach the end, the others people on the network can stop it from happening or approve it and keep  it going</i>) and transparent (<i>everyone can see the terms of the agreement</i>). The whole idea is to create trust minimized agreements via unbreakable promises.</p>


<h3><i>Blockchains</i></h3> <p>Are a chain of blocks that contain information, created by Satoshi Nakamoto in 2009, once a piece of data is recorded inside a blockchain is very difficult to change it, each block contains Data(<i>the type of data depends on the type of blockchain, ex the ones from  bitcoin store the sender, the receiver and the amount</i>), Hash(<i>The fingertip of the block, his identification, when the block is created its hash is calculated, changing something inside it will make the hash change as well</i>), Hash of previous block, the first block of the chain(<i>Genesis block</i>) cant point to any previous by definition.</p>

<h3>Consensus</h3>
<p> Is any method used to achieve reliability, security agreement, Consensus is a fundamental problem in the control of distributed computing,  playing major role in security and authentication.</p>


<h3>Proof of Work</h3>
<p>A blockchain can be viewed as a public block of ledgers(<i>storing transaction amounts, wallet addresses, date, time and nonce, this latter being the solution for the PoW, shorter for Number used Once</i>) with all the information of the ledge being encrypted into a hash(<i>identification</i>) and also pointing to the next ledger hash(<i>the next block in the chain</i>). The challenge is take the Nonce plus the hash of the current block into a hash function(sha-256) and reach a value below the condition of the blockchain, the winner of the challenge(<i> the first to process the value below the condition</i>) gets to put a new block on the blockchain plus the reward(<i>transaction fees and newly minted coins</i>). The others miners can easily verify the solution. Lots of energy and computational power are used in the process of generating the solution.  </p>



<h3>Proof of Stake</h3>

<p>With PoS the computational work and the energy costs are reduced, mainly because there is no competition for the  reward, in this case to become a validator(<i>instead of a miner</i>)  the coin owner must "stake" a specific amount of coins (<i> as collateral </i>) to have more chance of being selected, one of the biggest pros about this method is the minimum energy consumption, Ethereum for example dropped 99.84% after transitioning from Pow to PoS.  </p>







Next note -> [[more]]


References -> [[links]], [[Ethereum_Whitepaper.pdf]], [[bitcoin.pdf]]



