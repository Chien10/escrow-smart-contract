### Environment Setup
1. Install Rust from https://rustup.rs/
2. Install Solana v1.6.2 or later from https://docs.solana.com/cli/install-solana-cli-tools#use-solanas-install-tool

### Build and test for program compiled natively
```
$ cargo build
$ cargo test
```

### Build and test the program compiled for BPF
```
$ cargo build-bpf
$ cargo test-bpf
```

# What is an escrow?
- Simply putting, escrow is the use of a third party which holds assets or funds before they're transferred from one party to another.
- An escrow will hold the assets or funds until both parties have fulfilled their contractual requirements.
- Types of escrow: real estate escrow, stock market escrow, online sale escrow, etc.

# What is smart contract?
- Smart contract is a set of promises written in digital form, including protocols (math or standard operating procedures (if, else)) within which the parties perform on these promises. (Nick Szabo, 1996)
- Smart contract may not be **smart**: just algorithms that perform a function, not artificial intelligence.
- Smart contract may not be **contract**.
- Use cases of smart contracts for business: digital identity, records, securities, trade finance, derivatives, financial data recording, mortages, land title recording, supply chain, auto insurance, clinical trials, cancer research, etc.

# What is dApp?
- dApp stands for decentralized applications which use blockchain as data storage and most of them have their own native token. dApps run as a smart contract on top of a platform.
- You can visit [State of dApps](https://wwww.stateofthedapps.com/) or [Dappradar](https://dappradar.com/) for more information about dApps and according to the former site, more than half of all the dApps listed fail!
- Usage of dApps: exchange, gambling, gaming, finance, etc.
- By the time I write this README, the most active dApp has 2,050 active users per day compared to Facebook with half a billion active users a day.
- Why haven't dApps yet received wide consumer adoption?

# What is Solana?
- [Solana](https://solana.com/) is high performance, single-layer, permissionless open-source blockchain. In other words, Solana is a data storage for dApps.
- Solana's native token is SOL and it can be divisible by up to one billion. 1e-9 SOL = 1 lamport.
- The Solana ecosystem is still young and the platform just went to mainnet in March 2020
