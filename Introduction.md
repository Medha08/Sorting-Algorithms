# Inroduction to Sorting Algorithms 
## Key Points to be noted here are 
### Usage 
- These algorithms are mainly considered for usage  when we need to arrange things in a certain order to increase readability 
- When we need to search or extract something quickly out of a collection of data , remember how you sort all the copies in your bag :smile:
- Data can be sorted in a particular order based on a specific and desirable property :sunglasses:

### Examples 
- Remember when we played cards and sorted our cards based on rank "Ace" being the head (Thus sorting was done based on property of rank ) or we can sort by suite.
- Remember surfing through a Hotel or Flipkart where it gives us various properties to sort the products  in some order like from  low price to high price or rating based etc.
- Dictionary :cold_sweat: (Life Saviour) Sorting is called as lexicographical order or dictionary order.

### Definition 
        Sorting is arranging the elements in a collection or list in increasing or decreasing order of some property , 
        the data items being sorted should be homogeneous or of same type (all integes or characters).
  Sorting can be done based on any property ,if we have 5 numbers 2,3,5,6,9 sorting can be done in the following ways ->
  - 2,3,5,6,9 (Increasing order of value )
  - 9,6,5,3,2 (Decreasing order of value )
  - 2,3,5,9,6 (Increasing order of number of factors) 2->1,2  ||   3->1,3  ||   5->1,5   ||   9->1,3,9   ||    6->1,2,3,6
  A sorted list is a permutation of original list , we only rearrange based on a property .
  
### Magic
  If a list is unsorted we will have to do **Linear Search** 
    size of list -> n 
   - if we take n-> 2^64 then as Linear Search Time Complexity (Worst Case) is O(n) ie n comparisons, so it will take 2^64 ms to complete :cold_sweat:
  If a list is sorted we can do **Binary Search**
  size of list -> n 
   - if we take n-> 2^64 then as Binary Search Time Complexity (Worst Case) is O(log n) ie log n comparisons, so it will take 64 ms to complete :relaxed:
   
### Classification 
   
    **Time Complexity** ie rate of growth of time taken by an algorithm with respect to input size.
    
    **Space Complexity** or Memory usage,  Inplace Sort -> constant memory to rearrange elements while other algorithms like Merge Sort use extra memory to temporarily store data which increase with input size . 
    
    **Stability** if we have set of cards 6 of heart , 9 of club , 6 of diamond and we want to sort by rank -> 6 of heart , 6 of diamond , 9 of club or we can do  6 of diamond ,6 of heart , 9 of club , The difference is that first is stable sort as arrangement of 6 in first algorithms has sorted cards according to the property but has also preserved the relative order of cards as in original list, while second has not so unstable.
    
    **Internal or External Sort**
    When all records which are sorted are present in main memory ->Internal Sort 
    when records are presnt in auxillary storage like disk ->External Sort 
    
    **Recursive or Not Recursive **
    Recursive-> Quick Sort and Merge Sort 
    Non Recursive -> Insertion Sort and Selection Sort
    
  
    
    
    
      
   
   
  
   
   
   
        
