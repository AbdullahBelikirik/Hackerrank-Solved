### [Calculate the Nth term](https://www.hackerrank.com/challenges/recursion-in-c/problem?isFullScreen=true "Calculate the Nth term")

```c
int find_nth_term(int n, int a, int b, int c) {
    if(n == 1){
        return a;
    }
    else if(n == 2){
        return b;
    }
    else if(n == 3){
        return c;
    }
    else {
        return find_nth_term(n-1,a,b,c)+find_nth_term(n-2,a,b,c)+find_nth_term(n-3,a,b,c);
    }
}
```