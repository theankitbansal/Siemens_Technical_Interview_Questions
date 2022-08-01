# Siemens_Technical_Interview_Questions
Siemens Technical Interview Questions: Siemens Technical Interview Questions:

1. What is a web application?

In contrast to computer-based software applications that run locally on the operating system (OS) of the device, a web application (or web app) is application software that operates on a web server. The user uses a web browser with an active network connection to access web apps. These apps are built on a client-server architecture, in which the user ("client") receives services from an off-site server hosted by a third party. Webmail, online retail purchases, online banking, are all examples of regularly used web applications.

2. What are the advantages and disadvantages of DHCP?

DHCP stands for Dynamic Host Configuration Protocol, and it is a client-server architecture.

The following are the advantages or benefits of DHCP:

1. DHCP is simple to set up and assign IP addresses to request clients automatically. As a result, the time it takes to manually configure IP addresses can be decreased.
2. There are no additional expenditures associated with the deployment.
3. Duplicate or erroneous IP address assignment is avoided. As a result, there are no IP address disputes.
4. It makes network administration easier.
5. It supports a variety of scopes, such as multicast and super scopes.
6. It benefits mobile users greatly because correct configuration parameters are received immediately from the new network.

The following are DHCP's drawbacks or downsides:

1. In networks with only one configured DHCP server, the DHCP server might be a single point of failure.
2. Because DHCP packets cannot cross routers, a relay agent is required to ensure that the DHCP server handles all leases on both network segments. Relay agents accept broadcast DHCP packets and forward them to the DHCP server as unicast packets. In this case, the relay agent must be configured with the DHCP server's IP address.
3. Security: Because the DHCP server lacks a secure means for client authentication, it can get unauthorised access to IP addresses by submitting credentials such as DHCP client identifiers.
4. When a new IP address is assigned, the machine name does not change.

3. Explain Bug Life Cycle.

The bug life cycle, also known as the defect life cycle, is a process by which a defect progresses through many phases throughout its lifetime. This lifetime begins when a tester reports a bug and ends when a tester determines that the problem has been resolved and will not recur.

In a defect workflow, the following defects states can occur.

New: When a new defect is first documented, it is referred to as "new" and given the status of New.
Assigned: Once the tester has filed the bug, the tester's lead accepts it and assigns it to the programming team.

Open: The developer begins analyzing and working on the defect.

Fixed: A developer can mark an issue as "Fixed" once he or she has made a necessary code modification and verified it.

Pending Retest: Once the defect is fixed, the developer gives the tester a specific code to retest the code. The status given is "pending retest" because the software testing is still waiting from the testers' end.

Retest: At this level, the tester retests the code to see if the defect has been fixed by the developer and changes the status to "Re-test."

Reopen: The tester updates the status to "reopened" if the bug continues after the developer has solved it. The bug goes through the life cycle once more.

Verified: The tester re-tests the bug after the developer has solved it. If no bugs are found in the software, the bug is fixed, and the status is changed to "verified."

Closed: When a bug is no longer present, the tester marks it as "Closed."

![image](https://user-images.githubusercontent.com/81725794/182076966-302e3139-ed50-413c-be5a-0a24facf3238.png)

4. What are SDLC phases?

The SDLC (system development life cycle) is a project management model. It specifies the several stages that must be completed in order to take a project from conception to deployment and afterwards maintenance.

The 7 Stages of the System Development Life Cycle:

![image](https://user-images.githubusercontent.com/81725794/182076981-8afea240-e596-4169-b8ee-55c6fea81d69.png)

1. Planning Stage: The planning stage (also known as the feasibility stage) is the time when developers start thinking about the next project. It helps in understanding the definition of the problem and scope of any existing systems, as well as the determination of the new system objectives.
2. Feasibility or Requirements of Analysis Stage: Gathering all of the specific details required for a new system, as well as defining the first prototype concepts, is part of the analysis step.
3. Design and Prototyping Stage: The design stage is required before moving on to the primary developer stage. Developers will begin by outlining the overall application's characteristics, as well as individual aspects such as User interfaces, System interfaces, Network requirements, Databases.
4. Software Development Stage: The development stage is when programmers write code and build the application based on the design papers and specifications that were created earlier.
5. Software Testing Stage: Developers will go over their software with a fine-tooth comb during the testing stage, identifying any flaws or defects that need to be recorded, corrected, and retested.
6. Implementation and Integration: The general design for the app will come together after testing. Developer efforts will integrate different modules or designs into the source code, usually by using training environments to find more faults or defects.
7. Operations and Maintenance Stage: This can include resolving new issues that arise as a result of user reports or dealing with leftover bugs that were not able to be corrected before launch

5. What are the types of kernel objects?

The following are the several types of kernel objects:

Access token objects
Event objects
File objects
File-mapping objects
I/O completion port objects
Job objects
Mailslot objects
Mutex objects
Pipe objects
Process objects
Semaphore objects
Thread objects
Waitable timer objects 

6. What is the use of pointers?

Pointers are used to store and maintain the addresses of memory blocks that are dynamically allocated. Data objects or arrays of objects are stored in these blocks. The heap or free store is a memory space in most structured and object-oriented languages from which objects are dynamically allocated.

Example in C:

#include <stdio.h>
void printpointer()
{
 int var = 10;
 int *pt;
 pt = &var;    
 printf("The address is: %p \n",pt);
 printf("The value is: %d \n", *pt);   
}
int main()
{
 printpointer();
}

7. What is meant by stack and queue?

A stack is a linear data structure in which elements can only be added or removed from the top side of the list. The LIFO (Last In First Out) principle dictates that the element put last is the first to come out of a stack. Pushing an element into a stack is referred to as a push operation while removing an element from a stack is referred to as a pop operation. With a pointer called top, we always maintain track of the last entry in the list in the stack.
A queue is a linear data structure in which elements can only be inserted from one side of the list, called the back, and only deleted from the other side, called the front. The FIFO (First In First Out) principle governs the queue data structure, which means that the element placed first in the list is the first one withdrawn from the list. Enqueue operations are used to add items to a queue, and dequeue operations are used to remove items from a queue.

8. What are the different types of OSI layers?

Open Systems Interconnection (OSI) is an acronym for Open Systems Interconnection. It was created in 1984 by ISO or the International Organization for Standardization. It is a seven-layer architecture, with each layer performing distinct functions. These seven layers work together to send data from one person to another across the globe.

![image](https://user-images.githubusercontent.com/81725794/182077196-bda372d5-aa6b-4b36-a291-0fde24e64a8f.png)

Physical Layer: The physical layer is the lowest layer in the OSI reference model. It is in charge of establishing a physical connection between the devices. Bits of information are stored in the physical layer. It is in charge of sending individual bits from one node to another. When this layer receives data, it converts the signal received into 0s and 1s and sends them to the Data Link layer, which reassembles the frame.

Data Link Layer: The data link layer is in charge of message transport from node to node. The major purpose of this layer is to ensure that data transfers from one node to another through the physical layer are error-free. There are two sublayers in the Data Link Layer:

Media Access Control (MAC)
Logical Link Control (LLC)

Network Layer: The network layer is responsible for data transmission between hosts that are connected to various networks. It also handles packet routing, which is the choosing of the shortest path to send a packet from a large number of options. The network layer places the IP addresses of the sender and receiver in the header.

Transport Layer: The application layer receives services from the transport layer, while the network layer receives services from the transport layer. Segments are the units of data in the transport layer. It is in charge of the full message's delivery from beginning to end. If an error is detected, the transport layer acknowledges the successful data transmission and re-transmits the data.

Session Layer: This layer is in charge of establishing connections, maintaining sessions, authenticating users, and ensuring security.

Presentation Layer: The data from the application layer is retrieved and processed here so that it may be transmitted across the network in the proper format.

Application Layer: The Application layer, which is implemented by network applications, is at the very top of the OSI Reference Model stack of layers. These programs generate the data that must be sent across the network. This layer also acts as a window for application services to connect to the network and show the information they receive to the user.

9. What is the default port for the MySQL server?

The MySQL client, MySQL Connectors, and utilities like mysqldump and mysqlpump all use port 3306 as the default port for the old MySQL protocol (port).

10. What is a virtual memory?

A segment of memory that is produced momentarily on the storage device is referred to as virtual memory. It occurs when a computer's RAM gets depleted as a result of multiple processes executing at the same time.

A part of the storage disc is made accessible for usage as RAM by the operating system. Because processor power is consumed by moving data around rather than performing instructions, virtual memory is substantially slower than main memory. The operating systems guide shows how the operating system handles memory. When the computer needs to use virtual memory, latency increases. The operating system employs swapping to transport data between RAM and virtual memory. Data from processes that aren't in use right now is moved out of RAM and stored in virtual memory by the operating system. When the process is needed again, it copies the data back into RAM.

As transferring to a hard disc takes far longer than reading and writing RAM, using virtual memory slows down the machine.


11. What is
