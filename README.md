**ATM Simulator - C++ Program**

**Description:**
This C++ program simulates an ATM (Automated Teller Machine) that allows users to perform various banking operations such as checking balance, cash withdrawal, updating mobile numbers, and displaying user details. The program utilizes a text-based interface to interact with the user.

**Technologies Used:**
- C++: The programming language used to build the ATM simulator.
- `<iostream>`: Library for handling input and output streams.
- `<string>`: Library for string handling.
- `<conio.h>`: Library for providing console input/output functions (used for `_getch()`).

**How to Use:**
1. Upon running the program, the user will be prompted to enter their account number and PIN for authentication.

2. If the provided account number and PIN match the predefined user details, the user gains access to the main menu.

3. The main menu presents the following options:
   - **Check Balance:** Displays the user's current bank balance.
   - **Cash Withdraw:** Enables the user to withdraw cash from their account, ensuring sufficient funds are available.
   - **Show User Details:** Displays the account number, name, balance, and mobile number of the user.
   - **Update Mobile Number:** Allows the user to update their mobile number after verifying their old mobile number.
   - **Exit:** Terminates the ATM simulator.

4. After performing an operation, the program returns to the main menu, where the user can select other options or exit.

**Important Notes:**
- The user's account details (account number, name, PIN, balance, and mobile number) are predefined within the program and can be modified in the `main` function's `user1.setData()` call.
- The PIN serves as a simple security measure in this simulation. In real-world applications, more robust security mechanisms should be used.
- This is a text-based simulation for educational purposes and does not interact with any real bank system or perform actual financial transactions.

**How to Compile and Run:**
1. Save the provided C++ code in a file named "atm_simulator.cpp" (or any other preferred filename with a .cpp extension).

2. Ensure you have a C++ compiler installed on your system (e.g., GCC or MinGW for Windows users).

3. Open a terminal or command prompt and navigate to the directory where the "atm_simulator.cpp" file is saved.

4. Compile the C++ code using the following command:
   ```
   g++ -o atm_simulator atm_simulator.cpp
   ```
   This will generate an executable file named "atm_simulator" (or any other specified name after `-o`).

5. Run the program by executing the generated executable:
   ```
   ./atm_simulator
   ```
   For Windows users, the command would be:
   ```
   atm_simulator.exe
   ```

**License:**
This program is provided as-is without any warranty. You are free to use, modify, and distribute it for educational or personal purposes. However, use it at your own risk, and the author shall not be liable for any damages or issues caused by its usage.
