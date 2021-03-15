# CHAPTER5

Exercise 5-1: Write a program that converts Centigrade to Fahrenheit.

#include <stdio.h>

//programm to convet C a F.

int main(void) {

float C, F;

  printf("INSERT CENTIGRADES\n");
  scanf("%f", &C);
F = ((9./5)*C)+32;
  printf("FARENHEIT: %f", F);
  return 0;
}

Exercise 5-2: Write a program to calculate the volume of a sphere.

#include <stdio.h>
//PROGRAMM TO CACLCULATE THE VOLUME OF A SPHERE.
int main(void) {

float R, R3, VOLUME; 
const float PI = 3.1416;

  printf("INSERT THE RADIUS OF THE SPHERE\n");
  scanf("%f", &R);
  R3 = R*R*R;
  VOLUME = (4./3)*PI*R3;

  printf("\nTHE VOLUME OF THE SPHERE IS %f", VOLUME);
  return 0;
}

Exercise 5-3: Write a program that prints the perimeter of a rectangle given its
height and width. perimeter = 2 · (width + height)

#include <stdio.h>
//CALCULATE PERIMETER OF A RECTANGLE
int main(void) {

float W, H, PERIMETER;

  printf("INSERT THE WIDTH AND HEIGHT OF THE RECTANGLE \n");
  scanf("%f %f", &W, &H);
  PERIMETER = 2 * (W+H); 
  printf("THE PERIMETERES IS: %f", PERIMETER);

  return 0;
}

Exercise 5 -4: Write a program that converts kilometers per hour to miles per h our.
miles = (kilometer ·0.6213712

#include <stdio.h>
//PROGRAM TO CONVERT KM/H TO MI/H;
int main(void) {
float KM, MI;
const float CONVERSION = .6213712; 

  printf("INSERT KM/H TO CHANGE\n");
  scanf("%f", &KM);
  MI = KM * CONVERSION;
  printf("%f EQUALS %f", KM, MI);
  return 0;
}


Exercise 5-5: Write a program that takes hours and minutes as input, and then
outputs the total number of minutes. (1 hour 30 minutes = 90 minutes).

#include <stdio.h>

int main(void) {
//EVERYTHING TO MINUTES
  int H, M, TM;
  printf("INSERT HOURS AND MINUTES\n");
  scanf("%d %d", &H, &M);
  TM = M + (H*60);
  printf("TOTAL OF MINUTES: %d", TM);
  return 0;
}


Exercise 5 -6: Write a program that takes an integer as the number of minutes, and
outputs the total hours and minutes (90 minutes = 1 hour 30 minutes).
#include <stdio.h>
//MINUTS TO HOURS AND MINUTES
int main(void) {
  int TM, H, M;
  printf("INSERT TOTAL OF MINUTES\n");
  scanf("%d", &TM);
  H = TM/60;
  M = TM%60;
  printf("\nHOURS:   %d \nMINUTES: %d", H, M); 

  return 0;
}


5-7
foreach (char ch in laugh)
{
    if (ch == 'h')
        Console.Write("H");
    else
        Console.Write(ch);
}
Console.WriteLine();
}
