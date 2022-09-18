# [Hackerrank C Solutions - Introduction](https://www.hackerrank.com/domains/cpp?badge_type=cpp&filters%5Bsubdomains%5D%5B%5D=cpp-introduction "C - Introduction")

### [Say "Hello, World!" With C++](https://www.hackerrank.com/challenges/cpp-hello-world/problem?isFullScreen=true "Say 'Hello, World!' With C++")

```cpp
cout<<"Hello, World!";
```
### [Input and Output](https://www.hackerrank.com/challenges/cpp-input-and-output/problem?isFullScreen=true "Input and Output")

```cpp
int a,b,c;
cin>>a>>b>>c;
cout<<a+b+c;
```
### [Basic Data Types](https://www.hackerrank.com/challenges/c-tutorial-basic-data-types/problem?isFullScreen=true "Basic Data Types")

```cpp
int a;
long b;
char c;
float d;
double e;
scanf("%d %ld %c %f %lf",&a,&b,&c,&d,&e);
printf("%d\n%ld\n%c\n%.3f\n%.9lf",a,b,c,d,e);
```

### [Conditional Statements](https://www.hackerrank.com/challenges/c-tutorial-conditional-if-else/problem?isFullScreen=true "Conditional Statements")

```cpp
if (n_temp == "1"){
    cout<<"one";
}
else if (n_temp == "2"){
    cout<<"two";
}
else if (n_temp == "3"){
    cout<<"three";
}
else if (n_temp == "4"){
    cout<<"four";
}
else if (n_temp == "5"){
    cout<<"five";
}
else if (n_temp == "6"){
    cout<<"six";
}
else if (n_temp == "7"){
    cout<<"seven";
}
else if (n_temp == "8"){
    cout<<"eight";
}
else if (n_temp == "9"){
    cout<<"nine";
}
else{
    cout<<"Greater than 9";
}
```

### [For Loop](https://www.hackerrank.com/challenges/c-tutorial-for-loop/problem?isFullScreen=true&h_r=next-challenge&h_v=zen "For Loop")

```cpp
int a,b,n;
cin>>a;
cin>>b;
   
for(n=a; n<=b; n++){ 
    if (n == 1){
        cout<<"one\n";
    }
    else if (n == 2){
        cout<<"two\n";
    }
    else if (n == 3){
        cout<<"three\n";
    }
    else if (n == 4){
        cout<<"four\n";
    }
    else if (n == 5){
        cout<<"five\n";
    }
    else if (n == 6){
        cout<<"six\n";
    }
    else if (n == 7){
        cout<<"seven\n";
    }
    else if (n == 8){
        cout<<"eight\n";
    }
    else if (n == 9){
        cout<<"nine\n";
    }
    else {
        if(((int)n)%2 == 0){
            cout<<"even\n";
        }
        else{
            cout<<"odd\n";
        }
    }    
}
```

### [Functions](https://www.hackerrank.com/challenges/c-tutorial-functions/problem?isFullScreen=true "Functions")

```cpp
int max_of_four(int a, int b, int c, int d){
    if(max(a,b)>max(c,d))
    return max(a,b);
    else return max(c,d);
}
```