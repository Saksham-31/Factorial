# Factorial
Code to show factorials of numbers using the concept of loops.
int n,factorial=1,i=2;
    cout << "Enter value: " << endl;
    cin >> n ;
    while( i<=n )
    {
        factorial*=i;
        i++;
    }
    cout << "Factorial of " << n << " is :"<< factorial << endl;
