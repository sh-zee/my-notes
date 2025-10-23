
# 3 keys of Systems
1. Reliability
2. Scaleability
3. Maintain ability

## Reliability
It about saving your system from following errors.
1. Hardware failures
2. Software failures
3. Human errors

### Hardware Failures
1. Redendecy 
2. Diversification

### Software Failures
1. Coomon bugs across instaces (Simentaneous crashes)
2. Runway process (Resource hog): Starving other processes.
3. Slow/Faulty core or dependecy services
4. Fault propagation: Fault in one service started traveling into another service.

### Human Failure
1. Confustion and Complexity
	1. Problem: Confusion and Complexity causes the system to get difficult to maintain.
	2. Solution: Simplify it
		1. Clean interface
		2. Clean Code
		3. Clean Architechre
		4. Clean System
		5. Clean Documentation
2. Places to make mistakes vs Place to deploy: (Un tested assumptions)
	1. Prblem: Developers make mistakes when then can't test assumptions
	2. Solution: Give them playgrounds to test things
		1. Code testing areas
			1. Interpreters
			2. Learning tests
			3. Testing enviroments: Dev / Staging
		2. API testing areads
			1. Swagger UI
			2. Postman
		3. App logic testing areas
			1. Admin panels
3. Corner cases:
	1. Problem: Application cases that are not normal
	2. Soulutions:
		1. Unit tests
		2. Exception handeling
4. Easy recovery system: Make it less expensive to make mistakes
5. Indepth: Monitoring, Measurements and alerts for back-tracking and undoing the mistakes.
6. Good managment.

## Scaleability
### Define the load
1. Read/Write ratio
2. Request per second.
3. Concurrent connections
4. Active users
### Describe the performance
1. Latency - time and p-x
	1. p-50
	2. p-90
	3. p-95
	4. p-99
	5. p-999
2. Throughput

### Scaling Techniques
It is not one-fit for all.
1. Horinotal Scaling
2. Vertical Scaling
3. Hybrid



## Maintainability

1. For Operations Team (DevOps)
	1. Level 1: Make it work
		1. Easy to understand
		2. Monitor and recover faults
		3. Keep a log of common faults (types and recovery applied)
	2. Level 2: Automate
		1. Define the process
		2. Automate as much as possible
		3. Setup knowledge sharing.
	3. Level 3: robustness
		1. Disaster recovery drills
		2. Backups
		3. schedules chaose
		4. Routine updates
	4. Level 4: Plan ahead
		1. Impact of fault in one system on the other systems (relations)
		2. Capacity planning.
2. For Developers
	1. Easy to read and understand
	2. Easy to modify: Open-close