# Stack using Array
Stack is a linear data structure that follows a particular order in which the operations are performed. LIFO (Last In First Out) implies that the element that is inserted last, comes out first and FILO (First In Last Out) implies that the element that is inserted first, comes out last.
![image](https://user-images.githubusercontent.com/125560933/220721466-e60b6141-fcdc-4376-a194-369d03468cb3.png)

## Operations on Stack:

**push()**: When we insert an element in a stack then the operation is known as a push. If the stack is full then the overflow condition occurs.
![image](https://user-images.githubusercontent.com/125560933/220724016-359c8d57-df85-490a-8e90-49a2b823ffe1.png)

**pop()**: When we delete an element from the stack, the operation is known as a pop. If the stack is empty means that no element exists in the stack, this state is known as an underflow state.

![image](https://user-images.githubusercontent.com/125560933/220724144-3a41ca02-f152-4a16-a0ee-860fbd920ffa.png)

**isEmpty()**: It determines whether the stack is empty or not.

**isFull()**: It determines whether the stack is full or not.

## Algorithm of the program:

1. Declare variable top and assign it to -1.

2. Declare an array of 10 integers.

3. Create main function and give the user the choice to perform operations as Push, Pop, Display and Exit . Call the functions according to the choice given by user.

4. Declare and define the function push.
 _PUSH FUNCTION_:
- Check if top==9, print overflow 
-else accept data from user,increment top, insert data at top position.

5. Declare and define the function pop.
_POP FUNCTION_:
-Check if top==-1, print underflow
-else decrement top.

4. Declare and define the function display.
_DISPLAY FUNCTION_:
-Print the array using for loop.


## Applications of Stack:

**Balancing of symbols:** Stack is used for balancing a symbol.As we know, each program has an opening and closing braces; when the opening braces come, we push the braces in a stack, and when the closing braces appear, we pop the opening braces from the stack. Therefore, the net value comes out to be zero. If any symbol is left in the stack, it means that some syntax occurs in a program.

**Expression conversion:** Stack can also be used for expression conversion. This is one of the most important applications of stack. The list of the expression conversion is given below:
Infix to prefix
Infix to postfix
Prefix to infix
Prefix to postfix
Postfix to infix

**UNDO/REDO:** It can also be used for performing UNDO/REDO operations. For example, we have an editor in which we write 'a', then 'b', and then 'c'; therefore, the text written in an editor is abc. So, there are three states, a, ab, and abc, which are stored in a stack. There would be two stacks in which one stack shows UNDO state, and the other shows REDO state.
If we want to perform UNDO operation, and want to achieve 'ab' state, then we implement pop operation.




