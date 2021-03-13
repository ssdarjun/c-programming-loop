# c-programming- for loop

#include<stdio.h>
int main(){
    int i, n, d;
    n = 100;
    printf("******************************************************************************\nArjun Sutradhar\nCSE2101022038\nSonargaon University\n******************************************************************************\n \n \n");

    for(i = 1; i <= n; i++){
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 1,2,3,4,5,......,100

    for(i = 1; i <= 100; i++){
        if(i % 2 == 0)
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 2,4,6,8,10,......,100

    for(i = 1; i <= 100; i++){
        if(i % 2 != 0)
            printf("%d,", i);
    }

    printf("\n\n");
    //c program to display following series: 1,3,5,7,10, ......,99

    printf("n=");
    scanf("%d", &n);
    for(i = 1; i <= n; i++){
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 1,2,3,4,5,......,n

    printf("n=");
    scanf("%d", &n);
    for(i = 1; i <= n; i++){
        if(i % 2 == 0)
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 2,4,6,8,10,......,n

    printf("n=");
    scanf("%d", &n);
    for(i = 1; i <= n; i++){
        if(i % 2 != 0)
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 1,3,5,7,10, ......,n


    for(i = 1; i <= 100; i++){
        if(i%3==1)
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 1,4,7,10,13, ......,100

    for(i = 0; i <= 100; i=i+5){
        if(i > 0)
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 5,10,15,15,20, ......,100

    for(i = 1; i <= 100; i++){
            if(i*i <= 100)
            printf("%d,", i*i);

    }
    printf("\n\n");
    //c program to display following series: 1,4,9,16, ......,100


    for(i = 1; i <= 100; i++){
        if(i*i <= 100)
            printf("%d,", i*i*i);

    }
    printf("\n \n");
    //c program to display following series: 1,8,27,64, ......,1000

    for(i = 1; i <= 100; i++){
        printf("%d+", i);
    }
    printf("\n\n");
    //c program to display following series: 1+2+3+4+......+100

    printf("n=");
    scanf("%d", &n);
    for(i = 1; i <= n; i++){
        printf("%d+", i);
    }
    printf("\n\n");
    //c program to display following series: 1+2+3+4+......+n

    char c;
    for (c = 'A'; c <= 'Z'; ++c){
        printf("%c ", c);
    }
     printf("\n\n");
    //c program to display following series: A,B,C,D,E,F, ..... ,Z

    for (c = 'A'; c <= 'Z'; ++c){
        if(c % 2 != 0)
            printf("%c ", c);
    }
     printf("\n\n");
    //c program to display following series: A,C,E,G, ..... ,Y

    for (c = 'A'; c <= 'Z'; ++c){
        if(c % 2 == 0)
            printf("%c ", c);
    }
     printf("\n\n");
    //c program to display following series: B,E,F,H, ..... ,Z

    for (c = 'a'; c <= 'z'; ++c){
        printf("%c ", c);
    }
     printf("\n\n");
    //c program to display following series: a,b,b,d,e,f, ..... ,z

    for (c = 'a'; c <= 'z'; ++c){
        if(c % 2 != 0)
            printf("%c ", c);
    }
     printf("\n\n");
    //c program to display following series: a,c,e,g ..... ,y

    for (c = 'b'; c <= 'z'; ++c){
        if(c % 2 == 0)
            printf("%c ", c);
    }
     printf("\n\n");
    //c program to display following series: b,e,f,h ..... ,z


    for(i = 100; i >= 1; i--){
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 100,99,98,97,96,.....3,2,1

    for(i = 100; i >= 1; i--){
        if(i % 2 != 0)
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 99,97,95,93,.....5,3,1

    for(i = 100; i >= 1; i--){
        if(i % 2 == 0)
            printf("%d,", i);
    }
    printf("\n\n");
    //c program to display following series: 100,98,96,94,.....6,4,2

}
