<h1>Aim</h1>
<p>To study and implement linked list</p>
<hr>
<h1>Software Used</h1>
<p>VScode</p>
<hr>
<h1>Theory</h1>
<p>A linked list in C++ is a dynamic data structure consisting of nodes, where each node contains two parts: the data and a pointer to the next node in the sequence. Unlike arrays, linked lists allow efficient insertion and deletion of elements since they don't require shifting elements around. Linked lists can be singly linked (each node points to the next node) or doubly linked (each node points to both the next and the previous nodes). They are commonly used when the size of the data structure is unknown or when frequent insertions and deletions are required.</p>
<hr>
<h1>Algorithms</h1>
<h2>Basic Linked List</h2>
<ol>
        <li><strong>Start</strong></li>
        <li>Define a class <strong>Link</strong> with two public members:
            <ul>
                <li>An integer <strong>data</strong>.</li>
                <li>A pointer <strong>next</strong> of type <strong>Link*</strong>.</li>
            </ul>
        </li>
        <li>Create a constructor for the <strong>Link</strong> class that:
            <ul>
                <li>Accepts an integer <strong>num</strong>.</li>
                <li>Assigns <strong>num</strong> to <strong>data</strong>.</li>
                <li>Initializes the <strong>next</strong> pointer to <strong>NULL</strong>.</li>
            </ul>
        </li>
        <li>In the <strong>main</strong> function:
            <ul>
                <li>Dynamically allocate memory for a new object <strong>l1</strong> of the <strong>Link</strong> class, passing the value <strong>6</strong> to the constructor.</li>
                <li>Output the value of <strong>data</strong> and <strong>next</strong> for the <strong>l1</strong> object.</li>
            </ul>
        </li>
        <li><strong>End</strong></li>
    </ol>
<hr>
<h2>Node at the Beginning</h2>
<ol>
        <li><strong>Start</strong></li>
        <li>Define a class <strong>Node</strong> with two public members:
            <ul>
                <li>An integer <strong>data</strong>.</li>
                <li>A pointer <strong>next</strong> of type <strong>Node*</strong>.</li>
            </ul>
        </li>
        <li>Create a constructor for the <strong>Node</strong> class that:
            <ul>
                <li>Accepts an integer <strong>num</strong>.</li>
                <li>Assigns <strong>num</strong> to <strong>data</strong>.</li>
                <li>Initializes the <strong>next</strong> pointer to <strong>NULL</strong>.</li>
            </ul>
        </li>
        <li>Define a function <strong>insertHead</strong> that:
            <ul>
                <li>Accepts a reference to a pointer <strong>head</strong> of type <strong>Node*</strong> and an integer <strong>newData</strong>.</li>
                <li>Creates a new node using the <strong>Node</strong> constructor.</li>
                <li>Sets the <strong>next</strong> pointer of the new node to the current <strong>head</strong>.</li>
                <li>Updates the <strong>head</strong> to point to the new node.</li>
            </ul>
        </li>
        <li>Define a function <strong>Disp</strong> that:
            <ul>
                <li>Accepts a pointer <strong>head</strong> of type <strong>Node*</strong>.</li>
                <li>Traverses the list using a temporary pointer.</li>
                <li>Outputs the <strong>data</strong> of each node followed by "->" until the end of the list.</li>
                <li>Outputs <strong>"NULL"</strong> to indicate the end of the list.</li>
            </ul>
        </li>
        <li>In the <strong>main</strong> function:
            <ul>
                <li>Initialize <strong>head</strong> to <strong>NULL</strong>.</li>
                <li>Call <strong>insertHead</strong> to insert nodes with values <strong>10</strong>, <strong>20</strong>, and <strong>30</strong>.</li>
                <li>Call <strong>Disp</strong> to display the list.</li>
            </ul>
        </li>
        <li><strong>End</strong></li>
    </ol>
    <hr>
    <h2>Node at the End</h2>
    <ol>
        <li><strong>Start</strong></li>
        <li>Define a class <strong>Node</strong> with two public members:
            <ul>
                <li>An integer <strong>value</strong>.</li>
                <li>A pointer <strong>next</strong> of type <strong>Node*</strong>.</li>
            </ul>
        </li>
        <li>Create a constructor for the <strong>Node</strong> class that:
            <ul>
                <li>Accepts an integer <strong>data</strong>.</li>
                <li>Assigns <strong>data</strong> to <strong>value</strong>.</li>
                <li>Initializes the <strong>next</strong> pointer to <strong>NULL</strong>.</li>
            </ul>
        </li>
        <li>Define a function <strong>insertAtHead</strong> that:
            <ul>
                <li>Accepts a reference to a pointer <strong>head</strong> of type <strong>Node*</strong> and an integer <strong>value</strong>.</li>
                <li>Creates a new node using the <strong>Node</strong> constructor.</li>
                <li>Sets the <strong>next</strong> pointer of the new node to the current <strong>head</strong>.</li>
                <li>Updates the <strong>head</strong> to point to the new node.</li>
            </ul>
        </li>
        <li><strong>End</strong></li>
    </ol>
    <hr>
    <h1>Conclusion</h1>
    <p>In conclusion, C++ codes to implement linked list and nodes at the end/beginning were written and successfully executed.</p>
