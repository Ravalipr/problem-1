

# 1 Micro and Array Update
 Micro purchased an array A having N integer values. After playing it for a while, he got bored of it and decided to update value of its element. In one second he can increase value of each array element by 1. He wants each array element's value to become greater than or equal to K. Please help Micro to find out the minimum amount of time it will take, for him to do so.


<h2>Input</h2>
First line consists of a single integer, T, denoting the number of test cases. First line of each test case consists of two space separated integers denoting N and K. Second line of each test case consists of N space separated integers denoting the array A. 


<h2>Output</h2>
For each test case, print the minimum time in which all array elements will become greater than or equal to K. Print a new line after each test case. 


<h2>constraints</h2>
              1<=T<=5
              
              1<=N<=10^5
              
              1<=A[i],K<=10^6
              
 <h2>sample input</h2>
         2
          
         3 4
         
         1 2 5
         
         3 2
         
         2 5 5
         
 <h2>sample output</h2>
 3
 
 0
 
# HAMILTONIAN 

Hamiltonian and Lagrangian Students have become secret admirers of SEGP. They find the course exciting and the professors amusing. After a superb Mid Semester examination, it’s now time for the results. The TAs have released the marks of students in the form of an array, where arr[i] represents the marks of the ith student. 
Since you are a curious kid, you want to find all the marks that are not smaller than those on its right side in the array.

<h2>Input Format</h2>
The first line of input will contain a single integer n denoting the number of students. The next line will contain n space separated integers representing the marks of students. 

<h2>Output Format</h2>
Output all the integers separated in the array from left to right that are not smaller than those on its right side. 

<h2>Constraints</h2>

            1 <= n <= 1000000 
            
            0 <= arr[i] <= 10000 
        
 <h2>sample input</h2>
          6
          
          16 17 4 3 5 2
          
  <h2>sample output</h2> 
  17 5 2
          
     
            
            
#  Frustrated coders

There are N frustrated coders standing in a circle with a gun in their hands. Each coder has a skill value S[ i ] and he can only kill those coders that have strictly less skill than him. One more thing, all the guns have only 1 bullet. This roulette can take place in any random order. Fortunately, you have the time stone (haaan wo harre wala) and you can see all possible outcomes of this scenario. Find the outcome where the total sum of the remaining coder's skill is minimum. Print this sum. 

<h2>Input Format</h2>
The first line contains N the no. of coders The next line contains N elements where the ith element is theS[ i ] of ith coder.
 
<h2>Output Format</h2>
Print a single line containing the minimum sum.
 
<h2>Constraints</h2>

             1<= N <= 1000000 
             
            1<=S[ i ]<=1000 
            
  <h2>sample input</h2>    
  6
  
  1 7 2 2 4 4
  
   <h2>sample output</h2>
   11
   
 #  Pink Floyd and Happiness
Pink is sad because of some reasons, he wants to cheer up by listening to some songs
from his favorite band, Pink Floyd.
There are N records and Pink will be happy if he listens to them in the ascending
order, i.e., first the song No. 1, then No.2 and so on (He has to listen to all the N songs
to become Happy).
Pink is delivered his records in some given order, he can either add the record to the
Playlist in the delivered order or put some on another table. After being put on the
table only the topmost record can be added to the playlist at any time.
Print whether Pink will be sad or happy after the delivery of the records.

<h2>Input Format</h2>
N - Number of records followed by
N numbers- order of records.

<h2>Output Format</h2>
Print "Happy" if the playlist has songs from 1 to N in order else "Sad".

<h2>Constraints</h2>
1<=N<=10^5
The array consists of 1-N distinct numbers.

