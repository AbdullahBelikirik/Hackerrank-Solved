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

### [Students Marks Sum](https://www.hackerrank.com/challenges/students-marks-sum/problem?isFullScreen=true "Students Marks Sum")

```c
int marks_summation(int* marks, int number_of_students, char gender) {
    int i,ans = 0;
    if(gender == 'b'){
        for(i=0; i<number_of_students; i+=2){
            ans += *(marks+i);
        }
    }
    else if(gender == 'g'){
        for(i=1; i<number_of_students; i+=2){
            ans += *(marks+i);
        }
    }
    return ans;
}
```

### [Variadic functions in C](https://www.hackerrank.com/challenges/variadic-functions-in-c/problem?isFullScreen=true "Variadic functions in C")

```c
int sum (int count,...) {
    va_list args;
    int i, summary;
    
    va_start(args, count);
    for(i=0; i<count; i++){
        summary += va_arg(args, int);
    }
    va_end(args);
    return summary;
}

int min(int count,...) {
    va_list args;
    int i, minima = 999999, current;
    
    va_start(args, count);
    for(i=0; i<count; i++){
        current = va_arg(args, int);
        if(minima>current){
            minima = current;
        }
    }
    va_end(args);
    return minima;
}

int max(int count,...) {
    va_list args;
    int i, maxima = 0, current;
    
    va_start(args, count);
    for(i=0; i<count; i++){
        current = va_arg(args, int);
        if(maxima<current){
            maxima = current;
        }
    }
    va_end(args);
    return maxima;
}
```