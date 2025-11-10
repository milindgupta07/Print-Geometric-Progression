# Print-Geometric-Progression
Using C language program is made which gives the output to Print Geometric Progression
#include <stdio.h>
int main() {
    int n, a, r, i = 1;
    scanf("%d %d %d", &a, &r, &n);
    while(i <= n) {
        printf("%d ", a);
        a *= r;
        i++;
    }
    return 0;
}
