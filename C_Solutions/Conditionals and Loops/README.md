### [Conditional Statements in C](https://www.hackerrank.com/challenges/conditional-statements-in-c/problem "Conditional Statements in C")

```c
if(n==1){
    printf("one");
}
else if (n==2) {
    printf("two");
}
else if (n==3) {
    printf("three");
}
else if (n==4) {
    printf("four");
}
else if (n==5) {
    printf("five");
}
else if (n==6) {
    printf("six");
}
else if (n==7) {
    printf("seven");
}
else if (n==8) {
    printf("eight");
}
else if (n==9) {
        printf("nine");
}
else {
    printf("Greater than 9");
}
```

### [Printing Pattern Using Loops](https://www.hackerrank.com/challenges/printing-pattern-2/problem "Printing Pattern Using Loops")

```c
int n, i, j;
scanf("%d", &n);
for(i=-n+1;i<n;i++){
    for(j=-n+1;j<n;j++){
        if(abs(i)>abs(j))
        printf("%d ",abs(i)+1);
        else 
        printf("%d ",abs(j)+1);
    }
    printf("\n");
}
```

### [For Loop in C](hackerrank.com/challenges/for-loop-in-c/problem "For Loop in C")
    
```c
int a, b, i;
scanf("%d\n%d", &a, &b);
for(i=a; i<=b; i++){
    if (i<=9) {
        if(i==1){
            printf("one\n");
        }
        else if (i==2) {
            printf("two\n");
        }
        else if (i==3) {
            printf("three\n");
        }
        else if (i==4) {
            printf("four\n");
        }
        else if (i==5) {
            printf("five\n");
        }
        else if (i==6) {
            printf("six\n");
        }
        else if (i==7) {
            printf("seven\n");
        }
        else if (i==8) {
            printf("eight\n");
        }
        else{
            printf("nine\n");
        }
    }
    else {
        if (i%2==0) {
            printf("even\n");
        }
        else {
            printf("odd\n");
        }
    }
}
```

### [Sum of Digits of a Five Digit Number](www.hackerrank.com/challenges/sum-of-digits-of-a-five-digit-number/problem "Sum of Digits of a Five Digit Number")

```c
for(i=0; i<5; i++){
    sum += ((n%(int)pow(10, i+1)))/pow(10, i);
}
printf("%d",sum);
```
### [Bitwise Operators](https://www.hackerrank.com/challenges/bitwise-operators-in-c/problem "Bitwise Operators")

```c
void calculate_the_maximum(int n, int k) {
    int i, j, maxAnd=0, maxOr=0, maxXor=0;
    for(i=1; i<n; i++){
        for(j=i+1; j<n+1; j++){
            if(((i&j)<k) && ((i&j)>maxAnd)){
                maxAnd = i&j;
            }
            if(((i|j)<k) && ((i|j)>maxOr)){
                maxOr = i|j;
            }
            if(((i^j)<k) && ((i^j)>maxXor)){
                maxXor = i^j;
            }
        }
    }
    printf("%d\n%d\n%d",maxAnd,maxOr,maxXor);
}
```