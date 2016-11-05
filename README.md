# If-Statements

public class BankAccount: MonoBehaviour

private float moneyTotal = 25;

public void myBalance(){
    print(moneyTotal);
    //return moneyTotal;
}

public void Deposit(float amount){
    moneyTotal += amount;
}

public void Withdrawl(float amount){
    if (moneyTotal > amount) {
    moneyTotal -= amount;
    //return amount;
    }
} else {
    print("Sorry, not enough money.");
    //return 0;
}
