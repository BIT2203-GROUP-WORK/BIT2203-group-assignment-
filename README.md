# BIT2203-group-assignment-
Group assignment for data structure and algorithm 

Data Structure Classification Task

Lecturer Submission Link

Classification from Course Notes
We have provided separate code files for each classification type:

**1. Linear Data Structures**
 
**Static (Array)**: Located in data management,static array c language.c. Used for fixed datasets.

**Dynamic (Linked List)**: Located in linked_list_dynamic.py. Used for memory flexibility.

**Dynamic (Stack)**: Located in stack data structure.c. Used for LIFO operations.

**Dynamic (Queue)**: Located in queue dynamic.py. Used for FIFO operations.

**2. Non-Linear Data Structures**

**Tree:** Located in tree nonlinear.py. Used for hierarchical data.

**Graph**: Located in graph nonlinear.py. Used for interconnected networks.

**Research: Applications & Reasons**

Array: Used in Image Processing because pixels are stored in fixed grids which is crucial for efficient manipulation like applying filters or rendering. (Static).

Linked List: Used in Music Players for playlists because  it allows for seamless addition or removal of songs and easy navigation to the next or previous track by following the pointers.  (Dynamic insertion).

Stack: Used in Browsers for the "Back" button. (Undo logic).

Queue: Used in Printer Buffers.They temporarily store data that arrives faster than it can be processed, managing the flow in the correct sequence.(First job in, first job out).

Tree: Used in HTML DOM (Hierarchy of a website).

Graph: Used in Social Networks like Facebook (Mapping friends).

**Examples of application that are using data structure type and algorithm and reasons why**

In operating systems, queues are used alongside scheduling algorithms like Round Robin or Priority Scheduling to manage processes waiting for CPU time. Queues ensure fairness and order, while the algorithms determine efficiency and responsiveness, balancing system load and user experience.

Networking systems depend heavily on graphs and algorithms like Dijkstra’s shortest path. Graphs model the network topology, and Dijkstra’s algorithm ensures data packets travel the most efficient route, reducing latency and optimizing bandwidth usage.

Even in retail applications, such as Point of Sale (POS) systems, arrays are used to manage inventory and transactions because arrays allow direct indexing, making search and sort operations efficient for fixed-size collections., 

In music playlist management,songs in a playlist are often played sequentially, but users may want to add, remove, or reorder tracks dynamically. A linked list allows efficient insertion and deletion of songs without shifting all other elements, unlike arrays. Each song node can store a pointer to the next (and sometimes previous) song, making it easy to move forward or backward through the playlist.

Trees rely on algorithms such as binary search, tree traversal (inorder, preorder, postorder), and balancing algorithms (like AVL rotations).Example; databases use B-tree algorithms to quickly locate records, while search engines use tree traversal to parse and index web pages. The hierarchical structure of trees allows logarithmic search times, making them efficient for large datasets where quick lookup and insertion are critical.

 compilers use stacks to evaluate arithmetic expressions and manage function calls through recursion because stack uses  Depth-First Search (DFS). DFS relies on a stack to explore nodes deeply before backtracking, which is why it’s effective in maze-solving or pathfinding problems. 

**How DSA Works Within Systems**

Data structures determine how data is stored in memory (RAM), while algorithms determine how fast that data is processed. Efficient DSA choices prevent system crashes and ensure the CPU can handle millions of requests per second.Data structures and algorithms form the backbone of how systems operate, ensuring that information is stored efficiently and processed effectively. Data structures provide the organized framework for storing and managing data, whether through arrays for sequential access, linked lists for dynamic memory, trees for hierarchical organization, or hash tables for rapid lookups. Algorithms, on the other hand, are the logical procedures that act upon these structures to solve problems, such as searching, sorting, routing, or optimizing resources. Within systems, the two work hand in hand: operating systems use queues and scheduling algorithms to manage processes, databases rely on trees algorithm and hashing for fast retrieval, and networks employ graph algorithms to determine optimal paths. 
