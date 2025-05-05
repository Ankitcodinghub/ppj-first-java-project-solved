# ppj-first-java-project-solved
**TO GET THIS SOLUTION VISIT:** [PPJ First Java Project Solved](https://www.ankitcodinghub.com/product/ppj-first-java-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100234&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;PPJ First Java Project Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Problems:

Problem 1: Linked lists

In this problem, you should develop a linked list class similar to that provided in the C++ STL. The public interface of your class should provide basic insertion and deletion functions. In addition, it should provide an iterator class as an inner class in order to access the data stored in the list. For example, if we have a list of three elements, and want to access the second element, we should

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 1 of 6

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
declare an iterator and initialize it to the position of the first element, and move to the second position as shown in the code below:

list&lt;int&gt; myList;

myList.push_back(1); myList.push_back(2); myList.push_back(3);

list&lt;int&gt;::iterator it = myList.begin(); it++;

cout&lt;&lt; *it;

notice the usage of the scope operator in the declaration of the iterator, this is because the iterator class is defined as an inner class inside the list class:

template&lt;class type&gt; class myList { public:

class iterator {

// your code for the iterator class here

};

// your code for the list class her

};

Your list class should be a template class. [3 points]

The list class should have the following public interface:

<ul>
<li>● &nbsp;list() – default constructor. [2 points]</li>
<li>● &nbsp;list(type value, int initial_size) – constructs a list having ‘initial_size’elements whose values are ‘value’. [3 points]</li>
<li>● &nbsp;~list() – a destructor to clear the list and leave no memory leaks. [3 points]</li>
<li>● &nbsp;int size() – returns the current number of elements in the list. [2 points]</li>
<li>● &nbsp;void insert(type value, iterator position)</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 2 of 6

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
adds an element at position specified by the iterator. For example, if the passed iterator currently points to the second element, this element will be shifted on position, and the new value should be added at the second position. [3 points]

<ul>
<li>● &nbsp;iterator erase(iterator position) – erases the element specified by the iterator and return an iterator to the next element, throws exception if position points after the last element. [3 points]</li>
<li>● &nbsp;list&lt;type&gt;&amp; operator = (list&lt;type&gt; another_list) – overloads the assignment operator to deep copy a list into another list and return the current list by reference. [3 points]</li>
<li>● &nbsp;iterator begin() – returns an iterator pointing to the first element. [3 points]</li>
<li>● &nbsp;iterator end() – returns an iterator pointing after the last element. [3 points]</li>
<li>● &nbsp;You should develop an iterator class the following public interface:○ void operator ++ () – overloads the operator ++, it should advance the iterator one position towards the end of the list, throws exception if it is currently pointing after the last element. [3 points]
○ void operator — () – overloads the operator –, it should move the iterator one position toward the beginning of the list, throws exception if it is currently pointing to the first element of the list. [3 points]
</li>
<li>● &nbsp;All node pointers in the list class of the iterator class should be private and inaccessible from outside of the class. [3 points]</li>
<li>● &nbsp;No memory leaks or dangling pointers. [3 points]</li>
<li>● &nbsp;It is highly recommended to implement it as a double linked list.</li>
<li>● &nbsp;Write a main function to test all the above.————————————————————————————————————————————-
Problem 2: Sorting [15 Points]

In this problem, we will develop classes to use for testing two sorting algorithms (Selection

and Quick sort). The TestSorting class will have methods to support experimenting and analyzing sorting algorithms performance.

TestSorting class has the following functions that you should complete:
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3 of 6

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
1. GenerateRandomList(min, max, size) Generate a given number of random integer data from a certain range. For example, one can generate a vector/array of 10000 integer numbers that fall in the range from 1 to 100000, e.g., [5554, 32300, 98000, 342, …]

2. RunOnce(sorter, data, size) Run a given sorting algorithm (sorter is either a Selection or Quicksort) on a given set of data and calculate the time taken to sort the data.

1. RunAndAverage(sorter, min, max, size, sets_num) Run a given sorting algorithm on several sets of data of the same length and same attributes (from the same range) and calculate the average time.

Write a main function to test.

————————————————————————————————————————————-

Problem 3: Stacks [15 Points]

In this problem, you should develop a stack class similar to that provided in the C++ STL. You can use arrays or your linked list class developed in the previous problem as an underlying data structure, however, you cannot use any of the C++ STL classes in this problem.

<ul>
<li>● &nbsp;Your stack class should be template. [3 Points]</li>
<li>● &nbsp;The stack class should have the following public interface:
<ul>
<li>○ &nbsp;stack() – default constructor. [2 Points}</li>
<li>○ &nbsp;stack(type value, int intial_size)constructs a stack having‘initial_size’ elements whose values are ‘value’. [3 points]</li>
<li>○ &nbsp;~stack() – a destructor to clear the stack and leave no memory leaks. [3 Points]</li>
<li>○ &nbsp;type&amp; top() – returns the top element by reference. [3 Points]</li>
<li>○ &nbsp;void pop() – removes the top element. [3 Points]</li>
<li>○ &nbsp;void push(type value) – adds an element to the top of the stack. [3 Points]</li>
<li>○ &nbsp;int size() – returns the number of elements in the stack. [2 Points]</li>
</ul>
</li>
<li>● &nbsp;Write a main function to test all the above. ————————————————————————————————————————————-Problem 4: Using stack [15 Points]
In this problem, use the stack implemented in question 3. Given an input string of brackets ‘(‘ and ‘)’, square brackets ‘*‘ and ‘+’, curly brackets ‘,‘ and ‘-’, and multiple line comment token ‘/*’ and ‘*/’, check if this string is valid or not.

A string is considered valid if and only if:
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 4 of 6

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
For each opened bracket, there should be a closing bracket of the same type.

Each closing bracket should close the lastly opened bracket.

Multiple line comment tokens consist of two characters, and any text between them should be ignored. However, they are treated the same way as brackets regarding the rules described above. ([{}])(){}[]{[]} – valid.

({)} – invalid.

({/*)}]]]]]]}*/}) – valid.

({/*[][[]]]]]}) – invalid, the comment is not closed.

[{/*******/}] – valid.

Write a main function to test. ————————————————————————————————————————————- Problem 5 Priority Queue [15 Points]

Priority Queue is an extension of queue with following properties.

<ol>
<li>Every item has a priority associated with it.</li>
<li>An element with high priority is dequeued before an element with low priority.</li>
<li>If two elements have the same priority, they are served according to their order in thequeue.</li>
</ol>
Implement:

● string enqueue(string value, int priority)

● string dequeue() – dequeue according to the priority ● Write a main function to test.

<pre>Example:
q.enqueue(“world”, 10)
q.enqueue(“Hello”, 5)
cout &lt;&lt; q.dequeue() &lt;&lt; “ “ &lt;&lt; q.dequeue() &lt;&lt;endl;
Hello world
</pre>
Rules:

<ul>
<li>● &nbsp;Cheating will be punished by giving -2 * assignment mark.</li>
<li>● &nbsp;Cheating is submitting code or report taken from any source that you did not fully writeyourself (from the net, from a book, from a colleague, etc.)</li>
<li>● &nbsp;Giving your code to others is also considered cheating. Both the giver and the taker will get-10. Page 5 of 6</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>● &nbsp;People are encouraged to help others fix their codes but cannot give them their own code.</li>
<li>● &nbsp;Do not say we solved it together and we understand it. You can write the algorithm on papertogether but each group should implement it alone.</li>
<li>● &nbsp;If you do not follow the delivery style (time and files names), your assignment will be rejected.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 6 of 6

</div>
</div>
</div>
</div>
