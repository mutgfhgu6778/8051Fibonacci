# 留学生日常作业/课程设计/代码辅导/CS/DS/商科，仅为漂洋过海的你❥
标签：Computer Science、Data Science、Business Administration，留学生编程作业代写&&辅导

## 个人介绍:
本人是一名资深码农，酷爱投资。

为您提供 CS , DS , 商科 编程作业代写

<img src="design2023866.jpg"  width="200" />


Q. Assignment Question: Dynamic Fibonacci Sequence with Timers
Background:
You're developing a dynamic Fibonacci sequence calculator. This calculator should use the 
8051's timer to compute Fibonacci numbers at specific intervals and store each successive 
Fibonacci number in the microcontroller's internal RAM. 
Objective:
1. Use Timer 1 of the 8051 microcontrollers to control the calculation rate of the Fibonacci 
sequence. 
2. Store each successive Fibonacci number in successive addresses starting from a given 
memory address, e.g., 30h. 
3. If the Fibonacci number calculation exceeds the storage limit or exceeds a given 
maximum number, reset and start the sequence from the beginning. 
4. Implement a pause and resume functionality using a specific pin (e.g., P3.2) on 
EdSim51. 
Task Breakdown:
1. Timer Initialization:
 Configure Timer 1 in mode 1 (16-bit mode). 
 Load the appropriate values into TH1 and TL1 to generate a 20-microsecond delay 
using the provided clock frequency. 
2. Compute Fibonacci Sequence:
 Initialize two registers with the starting values of the Fibonacci sequence (0 and 1). 
 On each timer interrupt, compute the next Fibonacci number. 
 Use the stack (with PUSH and POP operations) to manage and retrieve data efficiently. 
 Utilize jumps and calls (Lcall, Acall) to manage the program flow. 
3. Store in RAM:
 Store the Fibonacci number at the next address in RAM. If the value is too large or the 
memory address exceeds the defined range, reset the sequence. 
4. Pause and Resume:
 Monitor a specific pin (e.g., P3.2) on EdSim51. 
 If pressed, pause the Fibonacci computation. If pressed again, resume from where it 
was paused. 
Guidelines:
 Create subroutines for Fibonacci computation, RAM storage handling, and 
pause/resume functionality to modularize your code. 
 Handle potential overflows and ensure the system can handle large Fibonacci numbers 
up to the defined limit. 
 Make use of logical operations, conditional jumps, and arithmetic operations where 
necessary. 
 Provide comments in your code for clarity. 
Hints:
1. Timer Initialization: Use the formula of Delay (refer to the notes/slides) 
2. Fibonacci Calculation: Utilize the stack efficiently. If you encounter an overflow 
while adding, reset the sequence or implement logic to continue with the larger 
numbers. 
3. RAM Storage: Consider starting from the address 30h and increment the address for 
each new Fibonacci number. Be conscious of the address range and maximum value 
constraints. 
4. Pause and Resume: Polling is a simple way to monitor the state of a pin. When paused, 
ensure the timer is not running. When resuming, the timer should continue from where 
it was paused. 
5. Modularization and Flow: Using LCALL or ACALL makes the code more readable 
and easier to debug. Conditional jumps (like JC, JNC, JZ, JNZ) can be very useful in 
controlling the program flow. 
6. Note: For the purpose of this assignment, assume the microcontroller is operating at a 
frequency of 12MHz (XTAL frequency).
Grading Criteria:
Total Marks: 100 
1. Documentation and Code Organization: (10 marks)
o Proper comments explaining each section and operation: 5 marks
o Readable code layout with consistent indentation and naming conventions: 5 
marks
2. Timer Initialization and Configuration: (20 marks)
o Properly initializing Timer 1 in mode 1: 5 marks
o Correct calculation and loading of values into TH1 and TL1 for a 2-second 
delay: 10 marks
o Properly handling timer overflow or interrupts to trigger the next Fibonacci 
calculation: 5 marks
3. Fibonacci Sequence Computation: (30 marks)
o Correct initialization of the sequence with starting values (0 and 1): 5 marks
o Correctly computing subsequent Fibonacci numbers: 10 marks
o Proper use of the stack (PUSH and POP) for data management: 10 marks
o Handling overflows or large Fibonacci numbers appropriately: 5 marks
4. Storing Fibonacci Numbers in RAM: (20 marks)
o Correctly storing each Fibonacci number in successive RAM addresses: 10 
marks
o Implementing proper logic to reset the sequence if a storage limit or defined 
maximum number is exceeded: 10 marks
5. Pause and Resume Functionality: (15 marks)
o Monitoring the specified pin (e.g., P3.2) correctly for pause and resume 
functionality: 5 marks
o Successfully pausing Fibonacci computation when the pin is pressed: 5 marks
o Resuming the Fibonacci computation from where it was paused upon the next 
press: 5 marks
6. Bonus/Extra Credit: (5 marks)
o Implementation of additional features or optimizations that enhance the 
functionality or efficiency of the program: 5 mark

## 作业代写价格:

|类型|美元|人民币|
|-----:|-----:|-----:|
|Assignment|$60-$120|¥400-¥800|

### 为了方便快速定价和确定是否代做，麻烦提供私聊的时候提供以下信息：
如果是作业，提供本次作业要求文档；如果是考试，提供考试范围和考试时间
一两句话概括一下作业任务或者考试任务，比如”可以帮忙实现一个决策树算法吗？”、”网络安全选择题考试，范围是内网横向移动知识点”
### 作业定价有两种方式：
    - 根据定价标准进行
    - 通过微信我们一起协商
## 联系方式

微信（WeChat）：design2023866

<img src="design2023866.jpg"  width="200" />
