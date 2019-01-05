//Input price of laptop,mobile and book and find out total price and average price.

int main()
{
    float t,l,m,b,avr;
    printf("\nenter the price of laptop,mobile and books:");
    scanf("%f%f%f",&l,&m,&b);
    t=l+m+b;
    avr=t/3;
    printf("\nTotal price:%f",t);
    printf("\nAverage price:%f",avr);
}


Output:-
Enter the price of laptop,mobile and books:40000
20000
4000

Total price:64000.000000
Average price:21333.333984
