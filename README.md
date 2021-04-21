PSEUDO CODE OF BUBBLE SORT USING OUR OWN PROGRAMMING LANGUAGE:
Now we are going to see how we can design a pseudo code of bubble sort by using the concepts of our own programming language which we have discussed before.

procedure bubbleSort: list : array of items {

 variable loop = list.length;
 for loop: variable i = 0, i<loop-1, i++{
 variable swapped = false;
 for loop: variable j = 0, j<loop-1, j++{
 if: list[j] > list[j+1]{


           
            swap( list[j], list[j+1] );		 
            swapped = true;


}


}


if:not swapped{ 
         break;
}

}

}




PSEUDO CODE OF INSERTION SORT:
procedure insertionSort:A : array of items {
   variable  holePosition;
   variable valueToInsert;
   for loop: variable i = 1, i<=A.length, i++ {
      valueToInsert = A[i]
      holePosition = i

while loop: holePosition > 0 AND A[holePosition-1] > valueToInsert{
         A[holePosition] = A[holePosition-1]
         holePosition = holePosition -1
      }

     A[holePosition] = valueToInsert

}

}

PSEUDO CODE OF SELECTION SORT:
procedure selection sort: list,n {    

   for loop: variable i = 1, i<n - 1, i++{
   varaible  min = i

for loop: variable  j = i+1, i<  n, i++{ 
         if: list[j] < list[min] {
            min = j;

}
}
  if: indexMin NOT = i{
         swap list[min] and list[i]
}


}


}
