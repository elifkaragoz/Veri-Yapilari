

Qustion; [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Answer;

root 5'tir.
       
       5
Dizideki diğer elemanlar sırayla kök düğümden başlayarak eklenir:
3, 5'ten küçük olduğu için sol tarafına eklenir.
     
       5
      /
     3
     
7, 5'ten büyük olduğu için sağ tarafına eklenir ve bu şekilde eklenmeye devam eder.
     
       5
      / \
     3   7
     
  ------------   
     
        5
       / \
      3   7
     /
    2
 
  ------------   
      
        5
       / \
      3   7
     / \
    2   4
   
  ------------   
    
        5
       / \
      3   7
     / \ /
    2   4
      /
     6
     
  ------------   
     
        5
       / \
      3   7
     / \ / \
    2   4   8
      /
     6
     
  ------------   
 
         5
        / \
       3   7
      / \ / \
     2   4   8
     / \
    1   6
