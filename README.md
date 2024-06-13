# Blockchain

Welcome to the Blockchain repository! This repository contains a Python program that demonstrates practical blockchain operations, including creating blocks, verifying blocks, displaying the entire blockchain, and verifying the entire blockchain with tampering detection.




![](https://media.geeksforgeeks.org/wp-content/uploads/20221111160733/Structureofblocksinblockchain.png)



## Features

1. Create a Block
2. Verify a Block
3. Display Whole Chain
4. Verify Entire Blockchain (with tampering)


## Getting Started

### Prerequisites

Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Blockchain.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Blockchain
    ```

### Usage

To run the blockchain program:
```bash
python blockchain_demo.py
```

### Program Options

1. **Create a Block**
   - Prompts for a miner's name and creates a new block.
   - Example:
     ```
     Enter your choice (1-5): 1
     Enter miner name: het
     Block #1 created successfully!
     ```

2. **Verify a Block**
   - Prompts for the block index and verifies the integrity of the specified block.
   - Example:
     ```
     Enter your choice (1-5): 2
     Enter block index to verify: 1
     Block #1 is valid.
     ```

3. **Display Whole Chain**
   - Displays the entire blockchain with details of each block.
   - Example:
     ```
     Enter your choice (1-5): 3

     Current Blockchain:
     Block #0 | Miner: Miner_1 | Timestamp: 1706962537.8012571 | Data: Genesis Block | Hash: 1337e0c64ae5eb433a727d5f6c80277f7d552a2fcf0631c6ec19223180229d38
     Block #1 | Miner: het | Timestamp: 1706962544.4103677 | Data: Block #1 Data | Hash: 26dc203af7e968f8bf2cabae65fc623ce8a3234c638f2e3d0f23552d6d344c75
     Block #2 | Miner: blockchain practical | Timestamp: 1706962562.0441248 | Data: Block #2 Data | Hash: 1282fb44d28872438f8815738c12807dcd19a5d17555c3ff455d8d4206feb92e
     ```

4. **Verify Entire Blockchain (with tampering)**
   - Verifies the integrity of the entire blockchain, detecting any tampering.
   - Example:
     ```
     Enter your choice (1-5): 4

     Blockchain after tampering:
     Block #0 | Miner: Miner_1 | Timestamp: 1706962537.8012571 | Data: Genesis Block | Hash: 1337e0c64ae5eb433a727d5f6c80277f7d552a2fcf0631c6ec19223180229d38
     Block #1 | Miner: het | Timestamp: 1706962544.4103677 | Data: Block #1 Data | Hash: 26dc203af7e968f8bf2cabae65fc623ce8a3234c638f2e3d0f23552d6d344c75
     Block #2 | Miner: blockchain practical | Timestamp: 1706962562.0441248 | Data: Tampered Data | Hash: 1282fb44d28872438f8815738c12807dcd19a5d17555c3ff455d8d4206feb92e

     Verification Result: False
     ```

5. **Exit**
   - Exits the program.
   - Example:
     ```
     Enter your choice (1-5): 5
     Exiting...
     ```

## Repository Structure

```
Blockchain/
│
├── Blochain_p1.ipynb
├── README.md
```


## Tool used 

https://jupyter.org/

    
## Author

- [@het-khatusuriya](https://github.com/het-khatusuriya)

