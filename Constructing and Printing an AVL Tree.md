# Ex. No: 16A - Constructing and Printing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a function `getDictTree(tree)` to return the **dict_tree** of an AVL tree.

**Step 3**: Define a function `Construct_AVL(L)` to:
- Create an **AVL tree** from the list `L`.
- Get and print the **dict_tree** using `getDictTree(tree)`.

**Step 4**: Define a list `L` with integer values.

**Step 5**: Call `Construct_AVL(L)` to build the tree and print the result.

**Step 6**: End the program.

---

## PYTHON PROGRAM
```
from  TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L,N):
    tree=AVL(L)
    for i in N:
        tree.insertNode(i)
    print("AVL Tree Before Balancing\n",getDictTree(tree))
    tree.BalanceTree()
    print("AVL Tree After Balancing\n",getDictTree(tree))
```

## OUTPUT
```
AVL Tree Before Balancing
 {10: [5, 15], 5: [4, 7], 15: [12, 18], 7: [9], 18: [], 9: [], 12: [], 4: [3], 3: []}
AVL Tree After Balancing
 {7: [4, 15], 4: [3, 5], 15: [10, 18], 10: [9, 12], 18: [], 9: [], 12: [], 3: [], 5: []}
```

## RESULT

<img width="1140" height="384" alt="image" src="https://github.com/user-attachments/assets/6983cfcb-fb3b-4374-80ef-c7796d6b97a6" />

