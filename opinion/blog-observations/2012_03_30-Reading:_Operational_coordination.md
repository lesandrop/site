# Reading: Operational Coordination

_by Lesandro Ponciano  / May 30, 2012 at 01:30PM_
 
I would like to present some more notes on coordination theory. Now, I would like to analyze coordination from its operational angle. As previously discussed, coordination can be defined as the process of managing dependencies between activities.  From an operational angle, coordination comprises five fundamental components: activity, agent, order, location, and time.  In a coordinated system, _“appropriate activities are performed, in a certain order, by a set of capable agents, in a fitting location, at a suitable time, in order to complete a set of defined tasks”_ (Whitfield et al. 2000). 
 
An appropriate **activity** needs to be performed in order to fulfil a task. The expression “appropriate activity” is used because different activities may result in different results. For this reason, it is necessary to choose among several options the most appropriate activity to carry out and fulfill the task. An activity may be, for example, an algorithm that an agent uses to solve a specific problem.
 
In coordination systems, one or more **agents** are required to perform an activity. An agent may be, for example, a human, software, or even a processor. The choice of which agent will perform the activity impacts the way the activity is performed. For example, if the agent is an individual, different individuals may perform the same activity in different ways. If the agent is a processor, different processors may perform the same activity at different speeds. _“The correct choice of agent (or agents), will ensure that the activity is performed in the most suitable fashion and the task is completed satisfactorily.”_ (Whitfield et al. 2000).
 
**Order** is the sequence in which activities should be performed to fulfill tasks. In coordination systems, it may exist, for example, an optimal order in which, when activities are performed, it maximizes the execution time of all tasks. Interdependency between tasks may indicate the correct order in which task activities need to be performed. For example, if two tasks present a consumer-producer relationship, their activities need to be performed sequentially. In this way, it is possible to identify which activities need to be performed sequentially and which need to be performed in parallel.
 
**Location** refers to the appropriate place where certain activities may be performed. In coordination systems,  location is important especially when agents are working together _“in the same team, or related team, or complete the same task, or related task”_. For example, it is possible to increase communication security and/or reduce coordination costs when agents work geographically close to one another.
 
Finally, the **time** in which an activity is performed directly affects the completion of a task. Furthermore, the coordination component time may also influence the completion of other activities.  For example, in a shared processor, if an activity arrives when the processor is busy it will wait a time to start execution and, therefore, its completion time will be impacted. If another activity depends on a certain output derived from the first activity, its completion time will also be impacted.
 
Some references on coordination theory on which this text is based:
* Coates et al. (2000) [“Coordination Approaches and Systems - Part II: An Operational Perspective”](http://www.springerlink.com/content/qk496l5q7je5f488/).  Research in Engineering Design, 12 (2). pp.73-89.
* Simone and Schmidt (1996). ["Coordination Mechanisms: Towards a Conceptual Foundation of CSCW Systems Design."](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.11.4960) Computer Supported Cooperative Work: The Journal of Collaborative Computing 5, pp. 155-200.

