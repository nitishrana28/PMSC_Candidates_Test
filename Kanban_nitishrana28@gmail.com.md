# Topic: Kanban

**Author**: Nitish Rana

**QAs Total**: 3

---

## Q1: Explain Little's Law and it's implications. 

**Difficulty:** `Mid`

**Source:**

https://www.knowledgehut.com/interview-questions/kanban

**Answer:**

Little’s law states that the average number of work items in a stable environment is equal to their average completion rate multiplied by their average time in the system.

Average wait time (Wq) = Average Queue length (Lq) x Average Processing rate (λ - Lamda) 
Work in Progress (WIP) = Throughput x Cycle Time (Average Time in the System)

**Implications:**
Essentially, the implications of Little’s law are that we can reduce the wait time by improving the processing time and by controlling the queue length.
For example: if our capacity is of managing 4 requests per minute but we have an inflow of 8 requests per minute then obviously we have a wait time of 1 minute for first 4 items in the queue. So this is going to lead to a bottleneck and add to the queue.
But if we improve our processing to 8 requests per minute, there will be no bottleneck.
To achieve this, either we make an investment in better processors or capacity or find ways to improve the WIP limit through efficiency improvement techniques such as Value stream mapping.

---

## Q2: Explain Value Stream Mapping. What are it's benefits ?

**Difficulty**: `Senior`

**Source:**

https://www.knowledgehut.com/interview-questions/kanban

**Answer:**

A lot of time is wasted in the processing pipeline due to hand-offs or waiting for the right resources or allocation. This adds to the overall processing time.
So, value stream mapping concept requires you to create a visual flow of order from a customer at initiation stage to final delivery through all stages.
It could be requirement gathering, sign-offs, reviews, testing, development, etc. anything that is required to deliver the product to the customer is mentioned in sequence, along with wait times, processing times.
Finally, the authorities review the entire value map and identify areas where the most impact is occurring. This has led to the improvement of processing times across industries such as manufacturing, HR etc. This concept was first used by Toyota.

**Benefits:**

* Helps find bottlenecks in the system
* Help generate a feeling of togetherness in the team to improve the system as a whole
* Helps in the visualization of problems
* Helps understand the inefficiencies, where they exist and how to fix them

---

## Q3: What is the difference between cycle time and lead time?

**Difficulty:** `Junior`

**Source:**

https://www.acte.in/kanban-interview-questions-and-answers/

**Answer:**

**Cycle time** is the total time including waiting time whereas **lead time** is the time when processing started and finished.

Lead time + wait time = cycle time.
