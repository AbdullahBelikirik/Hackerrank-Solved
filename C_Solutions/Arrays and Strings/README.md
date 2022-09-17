### [1D Arrays in C](https://www.hackerrank.com/challenges/1d-arrays-in-c/problem?isFullScreen=true "1D Arrays in C")

```c
int n, i, sum = 0;
scanf("%d",&n);
int *arr = (int*)malloc(n * sizeof(int));

for(i=0; i<n; i++){
    scanf("%d",&arr[i]);
    sum += arr[i];
}
printf("%d",sum);//
```

### [Array Reversal](https://www.hackerrank.com/challenges/reverse-array-c/problem?isFullScreen=true "Array Reversal")

```c
int num, *arr, i, tmp;
scanf("%d", &num);
arr = (int*) malloc(num * sizeof(int));
    
for(i = 0; i < num; i++) {
    scanf("%d", arr + i);
}

for(i=0; i<num/2; i++){
    tmp = arr[i];
    arr[i] = arr[num-i-1];
    arr[num-i-1] = tmp;
}

for(i = 0; i < num; i++){
    printf("%d ", *(arr + i));
}
```