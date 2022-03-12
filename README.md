# Android-Interview-Questions

Putting all questions, i ever faced in android app domain.

**** Kotlin :
1. When to use and not to use inline functions?
Ans : 
You can inline when all functional type parameters are called directly or passed to other inline function
You should inline when ^ is the case.
You cannot inline when function parameter is being assigned to a variable inside the function
You should consider inlining if at least one of your functional type parameters can be inlined, use noinline for the others.
You should not inline huge functions, think about generated byte code. It will be copied to all places the function is called from.
Another use case is reified type parameters, which require you to use inline


**** Android :
1. Life cycle of activity with example.
2. Launch modes in android with practical examples.

**** Data Structure :
1. Find a loop in a linked list and remove it.

**** Design :
1. Design a simple list with help of retrofit, recyclerview. Implement onitemclick and open another webview to load imageUrl.
2. Design a analytics library for android app as a stand alone sdk.
3. Design a data structure with search, delete and add with O(1) complexity. You can take my kind of predefined data structure (No space contraints).
