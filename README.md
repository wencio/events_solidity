

This repository contains a Solidity smart contract for event management and a React frontend to interact with the contract.

### Smart Contract (EventContract.sol)

The `EventContract` contract allows the creation, purchase, and transfer of tickets for events. Here's an overview of the main functions and features of the contract:

- **Event Structure**: Defines a data structure to represent an event, including the event admin, name, date, price, total ticket count, and remaining ticket count.
- **Event Creation**: Allows the creation of new events with specified name, date, price, and ticket count.
- **Ticket Purchase**: Allows users to purchase tickets for a given event, verifying ticket availability and correct ether amount sent.
- **Ticket Transfer**: Allows users to transfer tickets for an event to another address.

### React Frontend (App.js)

The frontend provides a user interface to interact with the smart contract. Here's an overview of the main features and functionalities of the frontend:

- **Event Creation**: Allows users to create new events by specifying the name, date, price, and available ticket count.
- **Ticket Transfer**: Allows users to transfer tickets for an event to another address.
- **Ticket Purchase**: Allows users to purchase tickets for a selected event.
- **Event Visualization**: Displays a list of available events with details such as ID, admin, name, date, price, and remaining ticket count.

### Running the Project

To run the project, follow these steps:

1. Clone this repository to your local machine.
2. Install the frontend dependencies using npm or yarn.
3. Start the local server for the frontend.
4. Connect the frontend to an Ethereum network compatible with the deployed smart contract.

