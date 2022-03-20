# Lecture 1  : Software Architecture
### Hardware VS Software
- __Hardware__ : 
	- standardized components
	- impossible to modify
	- wears out as time passes

 - __Software__:
	 - Custom built
	 - continuously modified and updated
	 - Deteriorate over time

- we want to decompose systems to  :
	- Tackle complexity by using ___divide and conquer___ strategy.
	- see if there are some parts already exists and can be reused.
	- Support flexibility and future evolution which is mainly called as ___Separation of concerns___.
-  Software Architecture is not a phase of development. it comes before the development.
- Software Architecture is made up of :
	- Structure --> Building blocks of The system topology.
	- Characteristics --> Quality of the system
	- Architecture Decisions --> Rules, restrictions, conventions.
	- Design Principles --> Implementations guidelines.
	
#### Characteristics 
- general attributes that would acceptable by the stakeholders. (like security, scalability, reusability, etc. )
- Requires collaboration with stakeholders to determine what is truly important from their perspective.
-  To know the characteristics of the system you have to get either :
	-  Domain Concerns.
	- requirements
	- domain knowledge
- when choosing the domain concerns we have to consider that each additional characteristic complicates overall system design and let stakeholders select at most top __3__.
-  try to map the requirements with domain concerns.

when talking about fitting pat together after dividing the system into subsystems you have to __specify semantics if component interface__ _where as it serves as a contract between component providers and clients_ 

- These ___interfaces___ must be :
	- fully documented
	- with semantics (like comments in java for example) not just syntax
	- understandable, unambiguous , accurate

- __Architecture Views__
	- module/Subsystem views : _need to represent _
	- component and connector views
	- allocation views