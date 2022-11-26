# [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamaları

root 7. Root rakamımızın soluna kendinden küçük, sağına da kendinden büyük rakamlar gelecek şekilde Binary Search Tree'yi oluştururuz.

1. aşama<br>
   7<br>
  /<br>
 5<br>

2. aşama
    7
   /
  5
 /
1

3. aşama
    7
   / \
  5   8
 /
1

4. aşama
    7
   / \
  5   8
 /
1
 \
  3

5. aşama
    7
   / \
  5   8
 / \
1   6
 \
  3

6. aşama
      7
     / \
    5   8
   / \
  1   6
 / \
0   3

7. aşama
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3

8. aşama
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4

9. aşama
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4

https://patika.dev