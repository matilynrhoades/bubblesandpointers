## bubblesandpointers

---
#include <stdio.h>
const int MAX=9;

void printValues(int*);
void sort(int*);
void swap(int*, int*);

int main(){
  int values[] = {7, 3, 9, 4, 6, 1, 2, 8, 5};
  printf("Before: \n");
  scanf(int*, int*)
  printValues(values);

  // test swap
  int x = 3;
  int y = 5;
  printf("x: %d, y: %d \n", x, y);
  swap(&x, &y);
  printf("x: %d, y: %d \n", x, y);

  sort(values);
  printf("After: \n");
  printValues(values);

  return(0);
} // end main

---
## main
---
produce an array of integres
print the array
create two temporary ints
test the swap functions
run the sort function on the arrays
print the sorted array

---
## printValues
---
void printValues(int*);
takes an int pointer representing the array
step through the array with a for loop
  print each member of the array
print the new line at the end

---
## swap
---
void swap(int*, int*);
takes two int parameters
make a temporary integer called temp
copy the value of a to temp
copy the value of b to the value of a 
copy temp to the value of b
return void

---
## sort
---
void sort(int*);
use bubble sort on the array

constant MAX is max length of array
function sort (array):
    create integer variables i and j
    for i from zero to MAX - 1:
        for j from zero to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array)

---




