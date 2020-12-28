# ✰ Bank for the user: Advanced Python Peojct!

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/67468718/103182205-89259780-485e-11eb-98ff-84b49a97534d.jpg">
</p>


## ✰ This project will consolidate the following skills:

  * ETL: Extraction, Transform and Load in a very controlled environment
  * list manipulation
  * user input retrieval and management
  * function creation and execution
  * data type management and conversion
  * sorting algorithms
  * searching algorithms.
  * data manipulation, taking user inputs, and writing a sorting algorithm.
  
## ✰ Poject steps:
  1. let's make a table in Python that looks a little like this:
  
  <p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/67468718/103183512-cb070b80-4867-11eb-9072-36e92d63731d.JPG">
</p>

  2. We now want to make a transaction function that, when called, adds a transaction to the table. We want this function to:
     * add a row to the accounts table for each transaction
     * get the current date in the format: DD/MM/YY
     * allow the user to input the credit or debit they want to carry out on the account
     * calculate and print the new balance
     * account for strange user inputs, such as 'blobby' and 'tiger', and to respond accordingly.
     
  3. We want our function to ask our user at least 2 questions:
     * Do you want to credit your account? (Y/N)
     * Do you want to debit your account? (Y/N)

     If they answer 'Y' to (1), we want to ask them by how much they want to credit their account. Otherwise, we want to move onto question 2.

     If they answer 'Y' to question (2), we want to ask them by how much they want to debit their account.

     To limit the number of cases, we'll make valid user inputs to (1) or (2) just the strings: 'Y' and 'N' (we'll also accept lower case versions of these). If the user inputs      a string that isn't one of those letters, or a number, then we want the transaction() function to keep asking the user for an input until their input is valid.
  
  4. We want to make a new row in account with the credit field equal to the value of the variable credit. But there are actually two relevant cases for us here:
     * Case 1: where this is the first transaction on record, and

     * Case 2: where this is not the first transaction.

     Our code will behave differently depending on the answer to this.

     Let's consider Case 1 first.

     If it's not the first transaction, we want to calculate the latest balance by adding the balance of the previous transaction to what we're crediting. To this end:

       * we'll get the previous transaction
       * make our new row representing our current transaction, and put the new balance into this row
       * append our new row to the account
       * print out what we've done, and the new balance.
       
   5. Let's consider Case 2: this is the first transaction on record.

      In this case, we'll simply:

       * make a new row, and make the balance value of this row just the value of credit
       * append this new row to our account
       * print what we've done.
    
   6. Let's finish off the part of the function whose aim is to ask the user whether they want to input credit. The debit part will be much more easy and will just need trivial       alterations to the credit section to make it run.
 
 
 

