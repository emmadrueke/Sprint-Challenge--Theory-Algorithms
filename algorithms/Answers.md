### Exercise 1
a) ```a=0;
   while (a < n * n * n) {
     a =a + n * n;
   }```

   `a` will get very large very fast. This looks to be Big O^nth power. 

b) ```//input array is of length n
  i = array.length -1;
  while (array[i] > x && i >= 0) {
    i = i/2;
  }```


