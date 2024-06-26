
# ali_coin Cryptocurrency


ali_coin Cryptocurrency is a blockchain-based project that includes the implementation of a basic cryptocurrency. This project consists of multiple nodes, each running on different ports, and a Postman collection for testing purposes.

# Directory Structure
The project contains the following files:

- `alicoin.py`: The main implementation of the Ali Coin cryptocurrency.
- `alicoin_node_5001.py`: Node implementation running on port 5001.
- `alicoin_node_5002.py`: Node implementation running on port 5002.
- `alicoin_node_5003.py`: Node implementation running on port 5003.
- `ali_coin.postman_collection.json`: A Postman collection for testing the API endpoints.
- `nodes.json`: JSON file containing the list of nodes in the network.
- `transaction.json`: JSON file containing transaction data.


## Installation

### Prerequisites
- Python 3.x
- Postman (for testing API endpoints)

### Steps
- Clone the repository or download the ZIP file and extract it.
- Navigate to the project directory.  

### Usage
## Running the Nodes
- Open a terminal and navigate to the project directory.
- Run the nodes using the following commands

```bash
python alicoin_node_5001.py
python alicoin_node_5002.py
python alicoin_node_5003.py

```
Each command will start a node on the respective port.

##Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.