# Sort & Search Algorithms:
  ### Sorting and searching are two fundamental types of algorithms that every programmer should know.
  
# Brute Force Search:

### When to use Brute Force Search function:
  * When the problem is simple
  * When simplicity is more important than speed.
  * To benchmark other search engines (will be like a baseline!!!)

***The main Idea behind Brute_Force_Search*** is:

   Basically we're comparing the query_item against all items one by one in a list till we find the query_item.
   The result will be True or False

# Binary Search:

### When to use Binary Search function:
  * When're looking for both smarter and faster option

***The main Idea behind Binary search*** is :

  *  Find the median of the list and compare against the query_item:
     query_item ==  Median 
     True
        Break
     False 
        Continue 
  *  Check if query_item > Median :
     True
        Elimninate the lower half of the given list 
     False
        Elimninate the upper half of the given list 
  *  repeate step no.1 on the reminaing half.
     The result will be True or False
     
# Bubble Sort:

### When to use Bubble Sort function:
  * When're looking for both simple and slow option

***The main Idea behind Bubble Sort*** is : Swap pairs if First > Second


# Insertion Search:

### When to use Insertion Sort function:
  * When're looking for both smarter and faster option

***The main Idea Insertion Sort*** is :

  *  Always start from Index[1] (because there's nothing to the left to compare it with).
  *  Always compare current element to all left elements.

