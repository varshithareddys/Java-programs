class BankAccount {
    // Declaring fields
    String account_holder_name;
    double balance;

    // Method to deposit money
    void deposit(double amount) {
        balance = balance + amount;
        System.out.println("Deposited Amount: " + amount);
    }

    // Method to withdraw money
    void withdraw(double amount) {
        if (amount <= balance) {
            balance = balance - amount;
            System.out.println("Withdrawn Amount: " + amount);
        } else {
            System.out.println("Insufficient Balance");
        }
    }

    // Method to check balance
    void checkBalance() {
        System.out.println("Account Holder Name: " + account_holder_name);
        System.out.println("Current Balance: " + balance);
    }

    public static void main(String[] args) {
        // Creating object
        BankAccount account = new BankAccount();

        // Assigning account holder name and initial balance
        account.account_holder_name = "Rahul";
        account.balance = 5000;

        // Performing operations
        account.checkBalance();

        account.deposit(2000);
        account.checkBalance();

        account.withdraw(1500);
        account.checkBalance();
    }
}
