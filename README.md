# assigment-spark

The [assignment problem](https://en.wikipedia.org/wiki/Assignment_problem) is a fundamental combinatorial optimization problem. In its most general form, the problem is as follows:

*The problem instance has a number of agents and a number of tasks. Any agent can be assigned to perform any task, incurring some cost that may vary depending on the agent-task assignment. It is required to perform as many tasks as possible by assigning at most one agent to each task and at most one task to each agent, in such a way that the total cost of the assignment is minimized.*


Currently there is no direct implementation of these algorithms in spark so this repository proposes a solution to apply the [Hungarian algorithm](https://en.wikipedia.org/wiki/Hungarian_algorithm) in pyspark.

**The solution supports recatangular matrices where not all elements have to be assigned and can be discarded.**
