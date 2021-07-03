# 1st-year-C-programs



#include <stdio.h>

int main() {
    int a[10];
    double total = 0;
    for (int i=1;i<=10;i++) {scanf("%d",&a[i]);}
    for (int j=1;j<=10;j++) {total=total+a[j]*a[j];}
    printf("%lf",total);
    return 0;
}
