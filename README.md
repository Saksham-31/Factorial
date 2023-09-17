# Factorial
Code to show factorials of numbers using the concept of loops.
WHILE LOOP
int n,factorial=1,i=2;
    cout << "Enter value: " << endl;
    cin >> n ;
    while( i<=n )
    {
        factorial*=i;
        i++;
    }
    cout << "Factorial of " << n << " is :"<< factorial << endl;

FOR LOOP
int n,factorial=1,i=2;
    cout << "Enter value: " << endl;
    cin >> n ;
    for(i ; i<=n ; i++ )
    {
        factorial*=i;
    }
    cout << "Factorial of " << n << " is :"<< factorial << endl;

    DO-WHILE LOOP
    int n,factorial=1,i=2;
    cout << "Enter value: " << endl;
    cin >> n ;
    do {
        factorial*=i;
        i++;
    } while (i <= n);
    cout << "Factorial of " << n << " is :" << factorial << endl;
