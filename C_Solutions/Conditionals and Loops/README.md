### [Conditional Statements in C](https://www.hackerrank.com/challenges/conditional-statements-in-c/problem?isFullScreen=true "Conditional Statements in C")

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

### [Printing Pattern Using Loops](https://www.hackerrank.com/challenges/printing-pattern-2/problem?isFullScreen=true "Printing Pattern Using Loops")

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