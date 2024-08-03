# Simple Blockchain with Flask

## Setup

1. Create a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the application:
    ```sh
    python app.py
    ```

## Endpoints

- `/mine` - Mines a new block.
- `/transactions/new` - Adds a new transaction.
        {
            "sender": "address1",
            "recipient": "address2",
            "amount": 5
        }
- `/chain` - Returns the full blockchain.



