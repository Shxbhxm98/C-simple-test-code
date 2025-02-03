/*  # C-simple-test-code
We are checking whether the student is pass or fail by prompting the marks */

#include <stdio.h>
int main() {
int marks;
printf("Enter the marks obtain(0-100) : ");
scanf("%d", &marks);
if (marks <= 33){
printf("Student is Fail");
}
else{
  printf("Student is Pass");
}
  return 0;
}
