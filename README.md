# Checkout-Line-Simulator-C
This project is written in C with Visual Studio 2015. This project acts as a simulator for the normal and express lanes at a grocery store. The progam will ask the user how many times they would like to run the simulator, and then populate each lane with customers until the time runs out. Each customer struct contains a unique identificatino number, a service time, and a total time variable how long they spent in the lane. Each lane is implemented as a Queue for their FIFO properties. The express and normal lanes each have their own parameters that dictate whether a customer can be in their lane or not. These parameters include service time and, and arrival time. This way the simulator can more closely match the behavior of a real express and normal checkout lane. 