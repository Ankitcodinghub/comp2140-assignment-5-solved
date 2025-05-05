# comp2140-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [COMP2140 Assignment 5 Solved](https://www.ankitcodinghub.com/product/comp2140-assignment-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101073&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2140 Assignment 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Question 1: Simulating a Hospital Emergency Room

This question can be done after Week 11.

You will implement a priority queue and use it to simulate a hospital emergency room. Input will be a list of people arriving at the ER, read from a txt file (described below). Output will be a list of events in the ER, where each event is either (i) a patient arriving at the hospital, or (ii) the doctor completing a treatment and becoming available to treat another patient, or (iii) a patient being called in to see the doctor.

The Patient Class

Create a Patient class as follows:

<ul>
<li>Each patient will have a unique patient number (integer). For the emergency room simulation, the patients will be given a patient number in the order they arrive at the emergency room, beginning with 1.</li>
<li>Each patient will have an urgency (an integer between 1 and 10), where 1 is low priority (the least urgent cases) and 10 is high priority (the most urgent cases).</li>
<li>Each patient will have a treatment time (an integer representing a number of minutes). This represents the amount of time that the doctor will be occupied treating that patient.</li>
<li>Include public methods to get the patient number, urgency, and treatment time.</li>
<li>Write a toString method that returns a String containing the Patient information (and
use it while debugging). Depending on the desired format of the information, methods outside the Patient class that need to print patient information could use the toString method, or use the get methods to retrieve data to be included in output.

The Priority Queue Class

You will use a priority queue of patients to determine the order that patients are seen by the doctor. Before writing the code to simulate the emergency room, you should implement the priority queue as below. Remember to test the priority queue as you develop it.
</li>
</ul>
<ul>
<li>Your priority queue must be implemented using a heap of Patients.</li>
<li>The public methods for your priority queue will be insert (add a new item to the queue), deleteMax (remove the highest priority item from the priority queue), peek (peek at the
highest priority item in the priority queue), and isEmpty.
</li>
<li>The highest priority patients should be located at the top of the heap (front of the priority
queue).
</li>
<li>The isEmpty method will return true if the queue contains no items and false otherwise.</li>
<li>The insert method will insert a patient into the priority queue, so that the highest priority
patient is at the front of the queue (i.e. you will pass insert a Patient object).
</li>
<li>The deleteMax method will return the patient at the front of the priority queue (i.e.
deleteMax will return a Patient object), and will remove that patient from the queue.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 5

DEPARTMENT AND COURSE NUMBER: COMP 2140

• The peek method will return the patient at the front of the priority queue, but will leave that patient in the queue.

The Emergency Room Simulation

Simulate an emergency room with one doctor. As patients arrive, they are placed in a priority queue according to the urgency of their case. When the doctor is available (e.g. when one treatment ends), the next patient in the queue will be called in.

<ul>
<li>Assume that the input file is named patients.txt and stored in the same directory as your .java file. The input file contains a list of patients, one per line. Each line contains the arrival time, the urgency, and the required time with the doctor. The integers are separated by a single space. See the sample input below.</li>
<li>Use a “clock” that starts at 0 when the simulation begins, and tracks the number of minutes that have elapsed in the simulation. For efficiency, the clock time should “jump” from one event to the next, and not run through all minutes one by one.</li>
<li>The arrivals (input) file is in order by time of arrival. You should read in only one arrival at a time, and only read the next arrival when the previous has been entered in the queue.</li>
<li>A patient should only be entered in the queue when the clock time is equal to the patient’s arrival time. That is, the queue should always represent the situation in the waiting room
at the current time.
</li>
<li>When the doctor is free, and there is a patient waiting, the patient at the front of the
priority queue will be called in for treatment.
</li>
<li>Print a statement for each event (when a patient arrives at the hospital, when a patient
is called in to see the doctor, when the doctor finishes treating a patient and becomes

available). Use a format similar to the sample output below.
</li>
<li>The output must be ordered by the event time, but might not be exactly as below. For
example, depending on your implementation, you might have an arrival printed before or after a treatment starting at the same time.

Sample Program Input

2 4 15 535

7 9 12 14 5 9 131 2 5 138 3 10
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 5

DEPARTMENT AND COURSE NUMBER: COMP 2140

Sample Program Output

<pre>  Doctor is available at time = 0
</pre>
<pre>  Patient 1 arrived at time = 2 with urgency = 4 and treatment time =
  15.
</pre>
<pre>  Doctor is available at time = 2
</pre>
<pre>  Patient 1 in for treatment at time = 2 with urgency = 4 and treatment
  time = 15.
</pre>
<pre>  Patient 2 arrived at time = 5 with urgency = 3 and treatment time = 5.
</pre>
<pre>  Patient 3 arrived at time = 7 with urgency = 9 and treatment time =
  12.
</pre>
<pre>  Patient 4 arrived at time = 14 with urgency = 5 and treatment time =
  9.
</pre>
<pre>  Doctor is available at time = 17
</pre>
<pre>  Patient 3 in for treatment at time = 17 with urgency = 9 and treatment
  time = 12.
</pre>
<pre>  Doctor is available at time = 29
</pre>
<pre>  Patient 4 in for treatment at time = 29 with urgency = 5 and treatment
  time = 9.
</pre>
<pre>  Doctor is available at time = 38
</pre>
<pre>  Patient 2 in for treatment at time = 38 with urgency = 3 and treatment
  time = 5.
</pre>
<pre>  Doctor is available at time = 43
</pre>
<pre>  Patient 5 arrived at time = 131 with urgency = 2 and treatment time =
  5.
</pre>
<pre>  Doctor is available at time = 131
</pre>
<pre>  Patient 5 in for treatment at time = 131 with urgency = 2 and
  treatment time = 5.
</pre>
<pre>  Doctor is available at time = 136
</pre>
<pre>  Patient 6 arrived at time = 138 with urgency = 3 and treatment time =
  10.
</pre>
<pre>  Doctor is available at time = 138
</pre>
<pre>  Patient 6 in for treatment at time = 138 with urgency = 3 and
  treatment time = 10.
</pre>
<pre>  Doctor is available at time = 148
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 5

DEPARTMENT AND COURSE NUMBER: COMP 2140

Additional Notes

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>You may assume that the input file will be free of errors. Each line in the file will represent one patient and consist of three integers, separated by a space. The urgency will always be a valid integer between 1 and 10. The treatment duration will be a valid positive integer.</li>
<li>You may assume that there will be a maximum of one arrival per minute. That is, no two patients listed in the input file will have the same arrival time.</li>
<li>It is STRONGLY recommended that you create your own test data, and thoroughly test</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
your code.

• Submit ONE .java file containing all the source code for question 1 (i.e. place all classes in the same file). Do not submit any output. Your code will be run during marking. Make sure that your code compiles and runs without errors (see the Assignment Information file for some common issues).

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
[Programming Standards are worth 4 marks]

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 5

DEPARTMENT AND COURSE NUMBER: COMP 2140

Question 2: Graphs [24 marks]

This question requires material from Week 12.

For EACH of the two graphs given below, complete the following four items. No code is required for this question.

<ul>
<li>Draw the graph corresponding to the given adjacency matrix (graph 1) / adjacency list (graph 2). These graphs have more nodes and edges than many of the examples in the course materials. There will be many edges and it will not be possible to draw a pretty graph. Do your best to make it legible.</li>
<li>Complete a depth-first traversal of the graph, beginning at vertex B. Format your answer in a table containing (i) the event (visit/pop), (ii) the stack contents, and (iii) the current depth-first list of nodes, as in the depth-first traversal example in Week 12. Once the traversal is complete, write out the depth-first list of nodes, in the order they were visited.</li>
<li>Complete a breadth-first traversal of the graph, beginning at vertex L. Format your answer in a table containing (i) the event (visit/remove), (ii) the queue contents, (iii) the current vertex, and (iv) the current breadth-first list of nodes, as in the breadth-first traversal example in Week 12. Once the traversal is complete, write out the breadth-first list of nodes, in the order they were visited.</li>
<li>Use Dijkstra’s shortest path algorithm to find the lowest-cost paths from vertex H to all other vertices. Submit a table showing the details of each step of the algorithm. At each step, show the current least cost distance to each vertex, the previous vertex on that least cost path, and mark completed paths with an asterisk. That is, format your answer in a table, as in the Dijkstra’s algorithm example in Week 12. Once the algorithm is complete, write out the lowest-cost path from H to each other vertex (i.e. list the vertices along each path and state the total cost of each path).
Caution: Be aware of how the graphs would be stored in a computer. Use the adjacency matrix or adjacency list to determine the order that nodes are visited. Remember that a computer will process the vertices in a very systematic way.

You may use Photoshop, Powerpoint, or other software to draw your graphs and tables, or you may draw your graphs and tables by hand on paper and scan/photograph your solution. Whatever method you choose, convert your solution into a pdf file. Each graph should occupy a full page. Your answer (including all vertices, lines, and labels) must be legible after conversion to pdf, and be well-organized so that it can be easily marked.

Your pdf file must be named &lt;your last name&gt;&lt;your first name&gt;A5Q2.pdf (e.g. SmithJohnA5Q2.pdf). Submit your pdf file to the Assignment 5 dropbox in UM Learn, along with your solution to question 1.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
ASSIGNMENT 5

DEPARTMENT AND COURSE NUMBER: COMP 2140

Graph 1: This graph is stored in an adjacency matrix. toA B C D E F G

</div>
<div class="column">
H I J

0 0 0 0 0 0 50 0 0 0 0 30 0 0 20 30 0 0 0 0 0 0 0 0 40 0 70 0 0 0 0 0 0 0 0 0

</div>
<div class="column">
K L

700 5 0 30 30 50 0 0 20 0 60 80 0 0 0 0 10 90 0 0 0 0 0

</div>
</div>
<div class="layoutArea">
<div class="column">
from

<ol>
<li>A &nbsp;0</li>
<li>B &nbsp;0</li>
<li>C &nbsp;0</li>
<li>D &nbsp;0</li>
<li>E &nbsp;0</li>
<li>F &nbsp;10</li>
<li>G &nbsp;0</li>
<li>H &nbsp;60</li>
<li>I &nbsp;0</li>
<li>J &nbsp;10</li>
<li>K &nbsp;20</li>
<li>L &nbsp;0</li>
</ol>
</div>
<div class="column">
40202030800 0 0 20 40 0 0 0 0 0 0 30 0 0 10 0 0 0 0 0 0 0 0 0 40 0 0 0 0 0 0 0 30 90 0 60 0 0 0 50 10 0 70 0 0 0 0 0 0 60 0 0 0 80 10 60 0 0 20 0 20 70 60 0 0 90 0

</div>
</div>
<div class="layoutArea">
<div class="column">
Graph 2: This graph is stored in an adjacency list, where each list lists the vertices adjacent to a given vertex, and each entry in the list gives the adjacent vertex and the edge weight. (That is, the arrows below represent links in the linked lists, not edges in the graph.)

A: (E, 70)→(G, 40)→(H, 60)→(K, 30)

B: (D, 70)→(E, 50)→(I, 20)→(L, 40)

C: (F, 40)→(G, 20)→(H, 70)→(K, 10)→(L, 50)

D: (B, 70)→(G, 50)→(H, 90)→(I, 30)→(J, 60)→(L, 10) E: (A, 70)→(B, 50)→(I, 10)→(L, 30)

F: (C, 40)→(G, 60)→(I, 80)→(J, 50)→(L, 30)

G: (A, 40)→(C, 20)→(D, 50)→(F, 60)→(I, 10)→(K, 30) H: (A, 60)→(C, 70)→(D, 90)→(J, 20)

I: (B, 20)→(D, 30)→(E, 10)→(F, 80)→(G, 10)→(K, 60) J: (D, 60)→(F, 50)→(H, 20)→(K, 80)

K: (A, 30)→(C, 10)→(G, 30)→(I, 60)→(J, 80)

L: (B, 40)→(C, 50)→(D, 10)→(E, 30)→(F, 30)

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
