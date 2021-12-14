# buildspace Solana GIF Portal Project

### **Welcome 👋**

To get started with this course, clone this repo and follow these commands:

1. Run `npm install` at the root of your directory
2. Run `npm run start` to start the project
3. Start coding!

### **What is the .vscode Folder?**

If you use VSCode to build your app, we included a list of suggested extensions that will help you build this project! Once you open this project in VSCode, you will see a popup asking if you want to download the recommended extensions :).

### **Questions?**

Have some questions make sure you head over to your [buildspace Dashboard](https://app.buildspace.so/courses/CObd6d35ce-3394-4bd8-977e-cbee82ae07a3) and link your Discord account so you can get access to helpful channels and your instructor!

### RUN Solana

```
export PATH="/Users/leophamdev/.local/share/solana/install/active_release/bin:$PATH"

solana --version

solana config set --url localhost
solana config get

solana-test-validator


solana-keygen new

solana address


anchor test
```

Set up your environment for devnet.

solana config set --url devnet
solana airdrop 5
solana balance

In Anchor.toml, change [programs.localnet] to [programs.devnet].
Then, change cluster = "localnet" to cluster = "devnet".

anchor build


solana address -k target/deploy/myepicproject-keypair.json


solana config set --url devnet

// Make sure you're on devnet.
solana config get

anchor build

// Get the new program id.
solana address -k target/deploy/myepicproject-keypair.json

// Update Anchor.toml and lib.rs w/ new program id.
// Make sure Anchor.toml is on devnet.

// Build again.
anchor build