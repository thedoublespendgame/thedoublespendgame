# The Double Spend Game

## Background
A card game and teaching resources to educate students on the concepts of blockchains to increase financial and technical literacy

The Double Spend Game is flexible educational toolkit to be used to increase financial and technical literacy across the globe, especially in developing countries. It can be tailored to be used in school students (11-18),  university students (18-22), and adult education (18+). 

It is a set of interactive low-tech games playable with just pen and paper. It includes a complete lesson plan and set of educational resources to be used by educators to teach groups of students or adults the concepts behind centralised banking, decentralised finance, and how different types of blockchains (Bitcoin, XRP Ledger, Ethereum) work.

Financial and technical literacy is a significant factor in people's ability to create wealth and to avoid being exploited.

There is a [significant gap in financial literacy between black and white communities](https://www.annuity.org/financial-literacy/black-community/).

This idea was inspired by the work of the [Krypto for Kids project in Barbados](https://blockchainonthebeach.com/) to educate students on aspects of financial and technical literacy. It aims to create scalable education that can be translated and used throughout the world in schools, colleges, and adult education establishments. Everything will be released under a Creative Commons license and is intended to be a complete standalone lesson plan on its own, or adapted to be a part of a wider curriculum.

The games use an intentionally low-tech approach of pen and paper in order to maximise the potential audience globally. They can also be translated to other languages and/or adapted to different cultural specifics. 

The games involve explaining and simulating simplified versions of common blockchains, involving students interacting with each other and playing roles (e.g. miner, banker, validator). e.g. for PoW, each student is given a sudoku puzzle to solve, the first to solve it becomes the "miner" for that block. The other students then write transactions on cards and give them to the miner. For XRP LCP, a group of students are nominated to be a UNL and get to vote on transaction ordering.

The deliverable of the project will be a website with all the downloadable resources that can be printed or drawn by hand:

- A lesson plan for various length lessons (30, 45, 60 minutes)
- Background information on blockchains, payment systems, cryptocurrencies
- Cards and worksheets used in the play of the games
- Rules for each game
- Teaching points and discussion items for each game

The XRP Ledger will be used as one of the examples, and comparison of its advantages over proof of work and proof of stake blockchains.

The toolkit will be able to be used with groups of various ages and experiences, from school kids to university blockchain clubs, to adult education courses. 

## Example Games
The deliverables of this project will be a number of games and worksheets, along with accompanying lesson plan and educational resources.

An initial sketch out of some of the games is below. 

### Game 1: Centralized Banking

A single student is nominated as "the bank". The have a ledger sheet containing the names of each student in the class and an initial balance of $100:

| Name      | Balance |
| --------- | ------- |
| Alica     | 100     |
| Bob       | 100     |
| Chantelle | 100     |

Each student writes down a transaction amount and takes that paper to the the "bank", the bank in turn adjusts each balance based on the transaction amount. e.g. if Alica has \$20 written on her transaction, and has a previous balance of \$100, then the banker crosses off \$100 and writes \$120. Debit (deposits) amounts are positive, credits (spending) are negative.

Teaching scenarios:
1. The teacher manually adjusts a balance, setting it to zero. They then ask that student to make a withdrawal. There is no money left, the withdrawal thus fails. Where is the students money? What recourse do they now have? Was that a bank clerical error? Did the government seize the funds? Why were they seized?
2. The teacher takes the banks ledger sheet and destroys it. Now what? How do we know who owns what? What scenarios might lead to this in real life?

### Game 2: Decentralised ledger, but no consensus protocol
Explain that maybe a central ledger is bad, and maybe a better approach is that every participant has a copy of the ledger, so that the is no single point of failure.

Each student now has a ledger sheet. They all write down every name of each student in the class and an initial balance of \$100. 

Each student writes down a transaction amount on a transaction slip. The teacher then calls students in turn to take their transaction sheet to another student they randomly select. That student adjusts the account in their ledger sheet just like the banker did in game 1. They then shout out the transaction for everyone else to hear "Alicia: \$20". All the other students have to listen and adjust their ledgers at the same time.

The teacher speeds up inviting multiple students at a time to make transactions. Faster so that soon chaos ensues and students get out of sync keeping their ledgers up to date. Especially as multiple students call out transactions simultaneously.

Learning points:
1. It is difficult to keep transactions in sync.
2. A student could make multiple transactions to two different nodes at the same time, resulting in spending their money twice.
3. This is known as a "double spend" and the main thing that consensus algorithms are designed to solve.

### Game 3: Proof of Work (Bitcoin)
This was the first way in which the double spend problem was solved, and was the genesis of cryptocurrencies

Each student has a ledger sheet, with each student's name and initial balance of \$100. They also have a Sudoku sheet. Each student writes down a transaction, and the transaction slips are all collected by the teacher and kept in a random pile (the mempool). The teacher shouts "go!" and all students start to solve their Sudoku sheet. The first to finish puts up their hand. 

The first student to put up their hand is the "Block producer". They then are given the transaction slips by the teacher, and choose the order in which to record them on their ledger sheet, they call out each ones as they do, and all others copy their transactions.

Another two rounds of the same are performed.

Teaching points:
1. How much effort is involved in doing this? What happens to the results of the Sudokus that didn't win? Are they waste?
2. What happens if someone falsely claims to have completed their Sudoko? Is it easy to tell?
3. What happens if you give one student a calculator?

### Game 4: Federated Byzantine Agreement (XRP Ledger)

Each student has a ledger sheet with the name of each student in the class and a balance of \$100

Between them they agree on a subset of the students to be "Validators". In a class of 30, 5 validators would be a good number. 

Each student writes down a transaction on their transaction slip and the teacher collects them. The validators go into a huddle and agree on an order to apply the transactions, e.g. alphabetically or by amount or by age. Once they agree, they announce to the class and everyone applies the transactions in that order.

This is repeated for another 2 rounds.

Learning points:
1. Does the order matter? If so, to whom does it matter?
2. What happens if the validators don't agree on an order?
3. What can the rest of the students do, if one validator in particular is constantly disagreeing?

### Game 5: Proof of Stake (Ethereal)

Tbc.
