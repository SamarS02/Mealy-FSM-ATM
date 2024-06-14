This is a project done using Verilog in the software Vivado and was programmed onto a Zynq 7000 Blackboard.
The ATM utilizes a Mealy FSM to transition between the 8 states.
When the code is uploaded to the board, it will follow the commands as follows:
  -switches 0-9 will serve as the keypad
  -switch 10 acts as the card going into the machine and then use the keypad to enter in the specified 4-pin code
  -switch 11 finishes and exits out of the program
  -button 0 checks the balance of the account and flashes it on the 7-segment display
  -button 1 does a rapid withdrawal of $100
  -button 2 is a regualr withdrawal specified by the user
  -button 3 deposits the moaunt of money specified by the user into the account
  -LED 0: Card valid
  -LED 1: Card invalid
  -LED 2: Balance Check Request In Progress
  -LED 3: Rapid Withdrawal In Progress
  -LED 4: Withdrawal In Progress
  -LED 5: Deposit In Progress + Speaker Announcement
  -LED 6: Waiting for Cash-In
  -LED 7: Cash dispensed + Speaker Announcement
  -RBG LED 10: 
          Red: Not enough money in the account for the process
          Green: Enough money in account
