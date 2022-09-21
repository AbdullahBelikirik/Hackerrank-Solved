### ["Hello World!" in C](https://www.hackerrank.com/challenges/hello-world-c/problem?isFullScreen=true "'Hello World!' in C")

```c
printf("Hello, World!\n");
printf("%s",s);    
```

### [Playing With Characters](https://www.hackerrank.com/challenges/playing-with-characters/problem?isFullScreen=true "Playing With Characters")

```c
scanf("%c%*c", &ch);
scanf("%s%*c", &s);
scanf("%[^\n]%*c", &sen);
printf("%c\n%s\n%s",ch,s,sen);
```

### [Sum and Difference of Two Numbers](https://www.hackerrank.com/challenges/sum-numbers-c/problem?isFullScreen=true "Sum and Difference of Two Numbers")

```c
int n,m;
float a,b;
scanf("%d %d",&n,&m);
scanf("%f %f",&a,&b);
printf("%d %d\n%.1f %.1f",n+m,n-m,a+b,a-b);
```