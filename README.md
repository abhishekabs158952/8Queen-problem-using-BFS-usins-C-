# 8Queen-problem-using-BFS-usins-Cpp
# Abhishek kumar(Abs)
# 1801005


variables :
a : type struct node{
		int arr[8][8];
   		int row;
    		int column;
    		struct node *next;
		}

main : 
1.)Queen8
	1.i)valid

discription :
1.)Queen8 :
	as the cost for each path is same so i am appling BFS here
	1.i)valid : 
		in this function i am checking where the matrix formed is valid(no queen cut any other)
