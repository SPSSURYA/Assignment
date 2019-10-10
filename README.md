# <h1> Assignment </h1>
# <h2>1. Micro and Array Update </h2>
Micro purchased an array A having N integer values. After playing it for a while, he got
bored of it and decided to update value of its element. In one second he can increase
value of each array element by 1. He wants each array element's value to become greater
than or equal to K. Please help Micro to find out the minimum amount of time it will take,
for him to do so.

# <h3>Input:</h3>
First line consists of a single integer, T, denoting the number of test cases.
First line of each test case consists of two space separated integers denoting N and K.
Second line of each test case consists of N space separated integers denoting the array
A.


# <h3>Output:</h3>
For each test case, print the minimum time in which all array elements will become
greater than or equal to K. Print a new line after each test case.

# <h4>constraints:</h4> 
1<=T<=5<br>1<=N<=10<sup>5</sup><br>
1<=A[i],K<=10<sup>6</sup><br>
<table style="width:100%">
 <tr>
   <th>SAMPLE INPUT</th>
   <th>SAMPLE OUTPUT</th>
</tr>
<tr>
  <td>2<br>
3 4<br>
1 2 5<br>
3 2<br>
    2 5 5</td>
  <td>3<br>
    0</td>
  </tr>
  </table>


# <h2> 2. Hamiltonian and Lagrangian</h2>
Students have become secret admirers of SEGP. They find the course exciting and the
professors amusing. After a superb Mid Semester examination, it’s now time for the
results. The TAs have released the marks of students in the form of an array, where arr[i]
represents the marks of the ith student.
Since you are a curious kid, you want to find all the marks that are not smaller than those
on its right side in the array.
 #<h3> Input Format</h3>
The first line of input will contain a single integer n denoting the number of students.
The next line will contain n space separated integers representing the marks of students.
# <h3>Output Format</h3>
Output all the integers separated in the array from left to right that are not smaller than
those on its right side.
# <h3>Constraints:</h3>
1 <= n <= 1000000<br>
0 <= arr[i] <= 10000<br>


<table style="width:100%">
 <tr>
   <th>SAMPLE INPUT</th>
   <th>SAMPLE OUTPUT</th>
</tr>
  <tr>
   <tr>
    <td>6<br>
     16 17 4 3 5 2</td>
    <td>17 5 2</td>
 </tr>
 </table>

# <h2>3.Frustrated coders</h2>
There are N frustrated coders standing in a circle with a gun in their hands. Each coder
has a skill value S[ i ] and he can only kill those coders that have strictly less skill than
him. One more thing, all the guns have only 1 bullet. This roulette can take place in
any random order. Fortunately, you have the time stone (haaan wo harre wala) and
you can see all possible outcomes of this scenario. Find the outcome where the total
sum of the remaining coder's skill is minimum. Print this sum.

# <h3>Input Format</h3>
The first line contains N the no. of coders
The next line contains N elements where the ith element is theS[ i ] of ith coder.

# <h3>Output Format</h3>
Print a single line containing the minimum sum.

# <h3>Constraints:</h3>
1<= N <= 1000000<br>
1<=S[ i ]<=1000<br>
<table style="width:100%">
 <tr>
  
  
   <th>SAMPLE INPUT</th>
   <th>SAMPLE OUTPUT</th>
</tr>
  <tr>
    <td>6<br>
      1 7 2 2 4 4</td>
    <td>11</td>
  </tr>
  </table>
  
# <h2> 4. Pink Floyd and Happiness</h2>
Pink is sad because of some reasons, he wants to cheer up by listening to some songs
from his favorite band, Pink Floyd.
There are N records and Pink will be happy if he listens to them in the ascending
order, i.e., first the song No. 1, then No.2 and so on (He has to listen to all the N songs
to become Happy).
Pink is delivered his records in some given order, he can either add the record to the
Playlist in the delivered order or put some on another table. After being put on the
table only the topmost record can be added to the playlist at any time.
Print whether Pink will be sad or happy after the delivery of the records.

# <h3>Input Format</h3>
N - Number of records followed by<br>
N - Numbers- order of records.<br>

# <h3> Output Format</h3>
Print "Happy" if the playlist has songs from 1 to N in order else "Sad".

# <h3>Constraints:</h3>
1<=N<=10^5<br>
The array consists of 1-N distinct numbers.<br>

<table style="width:100%">
 <tr>
   <th>SAMPLE INPUT</th>
   <th>SAMPLE OUTPUT</th>
</tr>
  <tr>
    <td>5<br>
     1 2 4 3 5</td>
   <td>Happy</td>
 </tr>
 </table>

# <h2>5.Remove Friends</h2>
After getting her PhD, Christie has become a celebrity at her university, and her
Facebook profile is full of friend requests. Being the nice girl, she is, Christie has
accepted all the requests.
Now Kuldeep is jealous of all the attention she is getting from other guys, so he asks
her to delete some of the guys from her friend list.
To avoid a 'scene', Christie decides to remove some friends from her friend list, since
she knows the popularity of each of the friend she has, she uses the following
algorithm to delete a friend.
# <h3>Algorithm Delete(Friend):</h3>
DeleteFriend=false
for i = 1 to Friend.length-1
if (Friend[i].popularity < Friend[i+1].popularity)
delete i th friend
DeleteFriend=true
break
if(DeleteFriend == false)
delete the last friend.

# <h3>Input Format</h3>
First line contains T number of test cases. First line of each test case contains N, the
number of friends Christie currently has and K ,the number of friends Christie decides
to delete. Next lines contains popularity of her friends separated by space.

# <h3>Output Format</h3>
For each test case print N-K numbers which represent popularity of Christie friend's
after deleting K friends.


# <h3>Constraints:</h3>
1<=T<=1000<br>
1<=N<=100000<br>
0<=K< N<br>
0<=popularity_of_friend<=100<br>

# <h3>NOTE:</h3>
Order of friends after deleting exactly K friends should be maintained as given in
input.
<table style="width:100%">
 <tr>
   <th>SAMPLE INPUT</th>
   <th>SAMPLE OUTPUT</th>
</tr>
  <tr>
    <td>3<br>
3 1<br>
3 100 1<br>
5 2<br>
19 12 3 4 17<br>
5 3<br>
     23 45 11 77 18</td>
   <td>100 1 <br>
19 12 17 <br>
    77 18 </td>
 </tr>
 </table>
 
# <h2>6.Monk watching fight</h2>
Once Monk was watching a fight between an array and a tree, of being better. Tree
got frustrated and converted that array into a Binary Search Tree by inserting the
elements as nodes in BST, processing elements in the given order in the array. Now
Monk wants to know the height of the created Binary Search Tree.
Help Monk for the same.
#  <h3>Note:</h3>
1) In Binary Search Tree, the left sub-tree contains only nodes with values less than
or equal to the parent node; the right sub-tree contains only nodes with values
greater than the parent node.
2) Binary Search Tree with one node, has height equal to 1.

# <h3>Input Format</h3>
The first line will consist of 1 integer N, denoting the number of elements in the array.
In next line, there will be N space separated integers, A[i], where 1 ≤ I ≤ N, denoting
the elements of array.

# <h3>Output Format</h3>
Print the height of the created Binary Search Tree.

# <h3>Constraints:</h3>
1<=N<=10^3<br>
1<=A[i]<=10^6<br>
<table style="width:100%">
 <tr>
   <th>SAMPLE INPUT</th>
   <th>SAMPLE OUTPUT</th>
</tr>
<tr>
  <td>4<br>
    2 1 3 4</td>
  <td>3
    </td>
  </tr>
  </table>
  
# <h3>Explanation:</h3>
N=4.

Insert 2. It becomes root of the tree.
Insert 1. It becomes left child of 2.
Insert 3. It becomes right child of 2.
Insert 4. It becomes right child of 3.
Final height of tree = 3.

# <h2>7.Yatin plays PUBG</h2>
Yatin is playing PUBG and he has reached a place with a large staircase in front of him.
And there is an enemy at each landing of the staircase.
The staircase is analogous to a binary tree with each of its nodes as a landing of the
staircase and each of its edges as stairs from one landing to another.

<img src="https://he-s3.s3.amazonaws.com/media/uploads/9817cde1-d9a3-4551-9ecd-8ac1e50acd2a.png" >

Yatin wants to kill the maximum possible number of enemies. He can kill every person
he can see from his position with his suppressed sniper gun. But he can see only the
persons at the leftmost standing at each level and cannot see the rest.
Before starting shooting them, he wants to know how many persons he can kill. He is
busy keeping an eye on the enemies. So he wants you to find out the maximum
number of people he can kill from that location by providing you with the analogous
a binary search tree.

 # <h3>Note:</h3>
 Players do not change their position after one player has died, i.e. the leftmost
node remains the same even after player on that node has died. Or we can say that
the nodes are not removed after the player on that node has died.

# <h3>Input Format</h3>
The first line of input contains a number t denoting the number of test cases.
The first line of each test case contains n, the number of nodes in the tree.
The second line of each test case contains n space separated integers (unique) ai
denoting the value at each node of the BST.

# <h3>Output Format</h3>
Print the answer for each test case on a new line.

# <h3>Constraints:</h3>
1 <= t <= 20<br>
1 <= n <= 1000<br>
1 <= ai <= 1000000000<br>
<table style="width:100%">
 <tr>
   <th>SAMPLE INPUT</th>
   <th>SAMPLE OUTPUT</th>
</tr>
  <tr>
    <td>1<br>
 9<br>
    8 3 10 1 6 14 4 7 13</td>
   <td> 4 </td>
 </tr>
 </table>
