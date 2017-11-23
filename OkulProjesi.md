#include <stdio.h> 
#include <conio.h> 

// İki sayidan ekrana hangisinin büyük olduğunu yazdıran program.
main() 
{ 
int sayi1,sayi2; 
printf("Birinci sayiyi giriniz : "); 
scanf("%d",&sayi1); 
printf("İkinci sayiyi giriniz : "); 
scanf("%d",&sayi2); 
if(sayi1>sayi2) 
{ 
printf("Birinci sayi ikinci sayidan büyüktür"); 
} 
else if(sayi2>sayi1) 
{ 
printf("İkinci sayi birinci sayidan büyüktür");
} else 
{ 
printf("Sayilar eşittir"); 
} 
getch();

}
