### [1D Arrays in C](https://www.hackerrank.com/challenges/1d-arrays-in-c/problem?isFullScreen=true "1D Arrays in C")

```c
int n, i, sum = 0;
scanf("%d",&n);
int *arr = (int*)malloc(n * sizeof(int));

for(i=0; i<n; i++){
    scanf("%d",&arr[i]);
    sum += arr[i];
}
printf("%d",sum);
    
```c