
## C Program to find largest number

```c

// C Program to find largest number

#include <stdio.h>

int main() {

  double number1, number2, number3;

  printf("Enter 1st number: ");
  scanf("%lf", &number1);
  printf("Enter 2nd number: ");
  scanf("%lf", &number2);
  printf("Enter 3rd number: ");
  scanf("%lf", &number3);

  if (number1 >= number2 && number1 >= number3)
    printf("The largest number is %lf", number1);

  if (number2 >= number1 && number2 >= number3)
    printf("The largest number is %lf", number2);

  if (number3 >= number1 && number3 >= number2)
    printf("The largest number is %lf", number3);

  return 0;
}

```