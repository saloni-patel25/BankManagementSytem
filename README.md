# BakManagementSystem_MiniProject
This is a simple console-based bank management system implemented in C. It allows users to register accounts, log in, check balance, deposit and withdraw cash, perform online transfers, and change passwords.

## Usage

1. **Compile the program:**
gcc -o main main.c

2. **Run the program:**
./main


3. **Follow the prompts:**
- Choose option 1 to register a new account or option 2 to log in.
- If registering, provide account details.
- If logging in, enter the phone number and password.

4. **Perform transactions:**
- After logging in, choose from various transaction options.
- Balance inquiry, deposit, withdrawal, online transfer, and password change.

5. **Exit the program:**
- Choose not to continue transactions when prompted.

## File Structure

- `main.c`: Contains the main source code for the bank management system.
- `user.dat`: Data files are created for each registered user, storing account information.

## Notes

- The program uses simple file I/O for user data storage.
- Ensure proper compilation before running the program.
- Make sure to handle errors and edge cases during user input.

## Future Improvements

- Implement error handling for file operations.
- Add more security features.
- Enhance the user interface.

Feel free to modify and improve the program according to your needs. For any issues or suggestions, please contact [your contact information].
