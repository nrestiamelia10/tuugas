#include<stdio.h>
#include<conio.h>
void koor();
int main()
{
    koor();
}
void koor()
{
    int x,y;
    printf ("Masukkan nilai koordinat x:");
    scanf("%d",&x);
    printf ("Masukkan nilai koordinat y:");
    scanf("%d",&y);
    if (x>0&&y>0)
        printf(" Koordinat (%d,%d) berada di kuadran 1",x,y);
    else if (x<0&&y>0)
        printf(" Koordinat (%d,%d) berada di kuadran 2",x,y);
    else if (x<0&&y<0)
        printf(" Koordinat (%d,%d) berada di kuadran 3",x,y);
    else if (x>0&&y<0)
        printf(" Koordinat (%d,%d) berada di kuadran 4",x,y);
}
