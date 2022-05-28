Q [16,21,11,8,12,22] -> Merge Sort  
  
1) ***Seperation***  
  
   [16, 21, 11] &emsp; [8, 12, 22]  
  
   [16, 21] &emsp; [11] &emsp; [8, 12] &emsp; [22]  
     
   [16] &emsp; [21] &emsp; [11] &emsp; [8] &emsp; [12] &emsp; [22]  
     
     ***Merging***
        
    [16, 21] &emsp; [11] &emsp; [8, 12] &emsp; [22]  
      
    [11, 16, 21] &emsp; [8, 12, 22]  
     
    [8, 11, 12, 16, 21, 22]    
      
2)  ***Big-O Notation:***  
    O(n $\times$ log(n))
