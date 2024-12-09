
# ATM Banking System in COBOL

A simple and functional **ATM Banking System** developed in **COBOL**. This program simulates basic ATM functionalities such as user login, balance inquiry, deposits, withdrawals, and transaction history.  

## Features  
- **User Authentication**: Secure login using account number and PIN.  
- **Balance Inquiry**: View the current account balance.  
- **Deposit Money**: Add funds to the account.  
- **Withdraw Money**: Withdraw funds while ensuring sufficient balance.  
- **Transaction History**: Maintain a record of up to 10 recent transactions.  

## Prerequisites  
To run this project, you need:  
- A COBOL compiler (e.g., GNU COBOL).  
- Basic understanding of COBOL programming.  

## How to Run  

1. **Install a COBOL Compiler**:  
   - For GNU COBOL, download and install it from [GNU COBOL Official](https://gnucobol.sourceforge.io/).  

2. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-username/ATM-Banking-System.git  
   cd ATM-Banking-System  
   ```  

3. **Compile the Program**:  
   ```bash  
   cobc -x -free atm-system.cobol -o atm-system  
   ```  

4. **Run the Program**:  
   ```bash  
   ./atm-system  
   ```  

5. **Follow the On-Screen Instructions**:  
   - Enter your account number and PIN to log in.  
   - Choose actions from the ATM menu to perform transactions.  

## Sample Account Details  
Use the following credentials to test the system:  
- **Account Number**: `1234567890`  
- **PIN**: `1234`  

## Folder Structure  
```plaintext  
ATM-Banking-System/  
├── atm-system.cobol     # Main COBOL program file  
├── README.md            # Project documentation  
```  

## Future Enhancements  
- Expand transaction history storage beyond 10 entries.  
- Add support for multiple user accounts.  
- Integrate advanced features like fund transfers.  

## Contributing  
Contributions are welcome! Feel free to fork the repository and submit pull requests.  
---

Enjoy coding with COBOL! If you have any issues or questions, feel free to open an issue in the repository. 😊
