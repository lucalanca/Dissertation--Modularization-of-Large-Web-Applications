# Context

Modularization of applications is key to reduce the development cycles and increase time to market. The focus for this thesis is to research and deliver a technical architecture and implementation that enables modularization of an already existent application with an extremely large code base with more than 50 developers contributing to it on a daily basis. 

# Problem to be studied

# Solution perspectives

# State-of-the-art

# Work plan


# Drafts

Modularization of applications is key to reduce the development cycles and increase time to market. There are several architectural patterns, such as Service-Oriented Architecture (SOA) that promotes modularity in highly transactional, concurrent and scalable systems.

That being said, in the real world, sometimes there isn't enough time to dedicated to a well-though future-predicting architecture. In teams working on building innovative products, is usual to start by implementing a MVP first, adding new functionality over time. The problem with this approach is that architectural changes in the system are very hard to accomplish. Although there is a lot of literature in refactoring already existing code, namely of to refactor to software design patterns, architecture refactoring is somehow new to sofware engineering. 

Some major issues in doing so (architecture refactoring) is that: 
1. one must ensure a minimum down-time
2. one must ensure quality
3. one must ensure scalability

The Betfair system is an interesting one to study. First, because it has suffered several architecture modifications over time since its beginning. Second, because its a system with huge scalability, consistency and availabily constraints. 

This master's thesis will focus on studying architecture refactoring of systems. It will hava as case study the Betfair system, where an architecture refactoring will be made by the introduction of SOA patterns (specifically Enterprise System Bus). <THINGS TO BE TESTED> This experience will provide insights to common problems in refactoring architecture of system and techniques and methods to achieve this.

