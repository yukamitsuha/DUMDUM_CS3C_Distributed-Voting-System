# DUMDUM_CS3C_Distributed-Voting-System

![Alt text](https://github.com/yukamitsuha/DUMDUM_CS3C_Distributed-Voting-System/blob/main/DIAGRAM.png?raw=true)

![Alt text](https://github.com/yukamitsuha/DUMDUM_CS3C_Distributed-Voting-System/blob/main/From%20Supabase%20table.png?raw=true)




REFLECTION AND ANALYSIS:
Using the distributed voting system helped me to understand better distributed computing in a practical cloud computing environment. The distributed voting system allowed multiple edge nodes to create and send votes simultaneously. This created a more efficient and scalable process as opposed to a sequential execution where all tasks are executed one by one. Through the use of Pub/Sub and the worker service, I was able to see that both services were successful in managing message flow even during high traffic periods; however, I experienced some delays due to asynchronous processing and eventual consistency.

One of my main difficulties in the implementation was properly configuring the cloud services, specifically regarding API authentication, RLS policies, and database integration. Debugging was also much more difficult, since many errors could have been generated from different distributed components and not from one specific source. Despite these difficulties, the project demonstrated how distributed systems can improve scalability and fault tolerance, while at the same time, creating additional complexity in synchronization, communication, and debugging. Overall, this project provided me with valuable real-world experience using cloud distributed computing.
