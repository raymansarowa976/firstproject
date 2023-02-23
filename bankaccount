# firstproject
public class BankAccount {
//attributes
	 int id;
	 double balance;
	 double annualInterestRate;
     static int count;
	
//constructors
	public BankAccount(double x, double y) {
		SetBalance(x); SetannualInterestRate(y); count ++;
		id +=count;
	}
	public BankAccount() {
		balance = 0;
		annualInterestRate = 0;
	}
//methods
	//setters and getters
	
	public void SetBalance(double x){
		balance =x;
	}
	public void SetannualInterestRate(double y){
		annualInterestRate = y;
	}

	public int GetID() {
		return id;
	}
	public double GetBalance() {
		return balance;
	}
	public double AnnualInterestRate() {
		return annualInterestRate;
	}
	
	public double getMonthlyInterest() {
		double MonthlyInterest =balance * (annualInterestRate/100)/12;
		double MonthlyInterestRate = annualInterestRate/12;
		System.out.println(MonthlyInterestRate + "%");
		return MonthlyInterest;
	}
	public double withdraw(double g){
		double withdraw = balance - g;
		double temp = balance;
		balance = withdraw;
		 return withdraw;
		
	}
	public double deposit(double k) {
		double deposit = balance + k;
		double temp = balance;
		balance = deposit;
		return deposit;
		
	}
	public void displayInfo() {
		System.out.println("Account ID: " + GetID());
		System.out.println("Current balance: " + GetBalance());
		System.out.println("Annual interest rate: " + AnnualInterestRate() + "%");
		System.out.print("Monthly interest: " );
		System.out.println("Monthly interest: " + getMonthlyInterest());
		
	}




}
