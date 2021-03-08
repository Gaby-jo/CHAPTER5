# CHAPTER5
5-1
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


5-2
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


5-3
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


5-4
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


5-5
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


5-6
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
#include <stdio.h>
//PROGRAM TO KNOW YOUR AGE IN CHINA 
int main(void) {
  int B, Y, CHINAGE;
  printf("INSERT BIRTH YEAR AND ACTUAL YEAR\n");
  scanf("%d %d", &B, &Y);
  CHINAGE = (Y - B) + 1;
  printf("YOUR AGE IN CHINA IS: %d", CHINAGE);
  return 0;
}
