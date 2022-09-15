### [Boxes Through a Tunnel] (https://www.hackerrank.com/challenges/too-high-boxes/problem?isFullScreen=true "Boxes Through a Tunnel")

```c
struct box{
    int length;
    int width;
    int height;
};

typedef struct box box;

int get_volume(box b) {
	return b.width*b.height*b.length;
}

int is_lower_than_max_height(box b) {
	if(b.height<MAX_HEIGHT){
        return 1;
    }
    else {
        return 0;
    }
}
```