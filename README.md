# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP form.

## PROBLEM STATEMENT:
To develope the game application, the role of the agent is to promote the frog into the next level that level having food.

### State Space
~~~
{L1,L2,L3}-->{0,1,2}
L1->Level1
L2->Level2
L3->Levvel3
~~~
### Sample State
~~~
L2->Level2,1
~~~

### Action Space
~~~
Jump left
Jump right
~~~

### Sample Action
~~~
Jump right ->Frog gets food
~~~

### Reward Function
~~~
Reward= 
         +1, if the frog reaches the leaf with food
          0, Otherwise

~~~

### Graphical Representation
![1](https://github.com/Manoj21500566/mdp-representation/assets/94588708/3aad88f5-fb3a-474f-aec8-d0e3ff89aa2a)


## PYTHON REPRESENTATION:
~~~
Register Number:212221240027
Name:Manoj M
P = {
    0:{
        0: [(0,1,1,True)],
        1: [(1.0,0,1.0,False)]
    },
    1:{
        0: [(0,2,1,True)],
        1: [(1,0,1,False)]
    },
    2:{
        0: [(0,2,1,True)],
        1: [(1,1,1,False)]
    }
}

## OUTPUT:
![2](https://github.com/Manoj21500566/mdp-representation/assets/94588708/5a34355a-9118-4b41-86d7-14a12f3a05f2)


## RESULT:
Thus the given real world problem is successfully represented in a MDP form .

