Download Link: https://assignmentchef.com/product/solved-coen266-homework-1
<br>
<strong>Problem 1: </strong>Define in your own words the following terms: agent, agent function, agent program, performance measure, rational agent.

<strong>Problem 2:</strong> Give the task environment description of the following scenarios (Fully observable vs. partially observable? Deterministic vs. stochastic/strategic? Episodic vs. sequential? Static vs. dynamic/semi-dynamic? Discrete vs continuous? Single-agent vs. multi-agents?) a. Taxi driving.

<ol>

 <li>Playing soccer.</li>

 <li></li>

</ol>

<strong>Problem 3:</strong> Implement a Model-Based-Reflex-Agent for the Vacuum World problem.




x Define the “state” as a list of three elements: the 1<sup>st</sup> element specifies the status of the left square (“Clean” or “Dirty”), the 2<sup>nd</sup> element specifies the status of the right square (“Clean” or “Dirty”), and the 3<sup>rd</sup> element specifies the current location of the agent (0 for left square, 1 for right square).




x The candidate actions are “Suck”, “Left” (moving to the left square), “Right” (moving to the right square). Each action costs 1 point.




x The agent will take an action based on the current state of the world. The agent program can update the state every time an action is taken. The program terminates when both squares are clean.




x Create a test case to verify your code. The test case takes two inputs: the current state, and an empty list that will store the actions; then it will generate two outputs: the sequence of actions, and the total cost.




x Your test case should be able to take any possible inputs, generate the corresponding outputs, and verify whether the outputs are correct or not.




x Explain in detail how your code works (for example, what each function does, and how the test case works).


