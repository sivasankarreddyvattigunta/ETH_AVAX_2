Hardhat Project

This repository contains a starter project for integrating smart contract using solidity and Hardhat.

Getting Started

To get the code running on your computer, follow the steps below:


1. **Clone the GitHub Repository:**
   You need to clone the project repository from GitHub. Replace `<repository_url>` with the actual URL of the repository.
   ```
   git clone <repository_url>
   ```

2. **Install Dependencies:**
   Once you have cloned the repository, navigate to the project directory in your terminal and install the necessary dependencies using npm.
   ```
   cd <project_directory>
   npm install
   ```

3. **Open Additional Terminals:**
   Open two additional terminals (or command prompt windows) within your code editor. This is to run different commands simultaneously.

4. **Start Local Hardhat Node:**
   In the second terminal, start the local Hardhat node using the following command:
   ```
   npx hardhat node
   ```

5. **Deploy Smart Contracts:**
   In the third terminal, deploy the smart contracts to the local network using the following command:
   ```
   npx hardhat run --network localhost scripts/deploy.js
   ```

6. **Launch the Frontend:**
   Go back to the first terminal and run the following command to launch the frontend application:
   ```
   npm run dev
   ```

7. **Access the Application:**
   After running the frontend application, you should be able to access it on your local machine at:
   http://localhost:3000/

**Author:**
The author of this project is Vattigunta Siva Sankar Reddy.

**Prerequisites:**
Before proceeding with the installation, make sure you have Node.js and npm (Node Package Manager) installed on your computer.

**Contributing:**
The instructions encourage you to explore and modify the code to build your decentralized applications. If you encounter any issues or have improvements to suggest, you can submit a pull request.

**License:**
This project is licensed under the MIT License, which means it is open-source and allows you to use, modify, and distribute the code as long as you include the original copyright and license notice.
