#include <stdio.h>

int main()
{
    int po;
    int isprime = 1;
    scanf("%d", &po);
    if (po <= 1) {
        isprime = 0;
    } else {
        for (int i = 2; i < po; i++) {
            if (po % i == 0) {
                isprime = 0;
                break;
            }
        }
    }
    if (isprime) {
        printf("%d is a prime number \n", po);
    } else {
        printf("%d is not a prime number \n", po);
    }

    return 0;
}
