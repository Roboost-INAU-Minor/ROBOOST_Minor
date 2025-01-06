# Task Overview
This document outlines the structure of a collaborative project involving multiple robotic systems. 
Each robot is assigned to a student who serves as the project leader, responsible for developing a guide for the group and explaining the robot's functionality. 
The project focuses on four robots: WeldingRobot, KuKaRobot, DoosanRobot, and AMR. 
For each robot, the assigned student leads development, explains the robot's operation, and collaborates with their project group, which provides assistance and gains knowledge throughout the process.


## Project distribution
The diagram represents a project with four robot systems: WeldingRobot, KuKaRobot, DoosanRobot, and AMR. Each system has a project leader (Bram, Dylan, Gijs, and Hailing) who develops the student program and explains it to others. The project groups assist the leaders and learn from their progress.

```plantuml
@startuml
package "Project Overview" {
    Top to bottom direction

    package "WeldingRobot" {
        Left to right direction
        class Bram {
            + Project Leader
            + Develops student program
            + Explains to other students how the robot works
        }
        class Project_Group {
            + Assists Bram as needed
            + Learns from Bram's progress
        }
    }

    package "KuKaRobot" {
        class Dylan {
            + Project Leader
            + Develops student program
            + Explains to other students how the robot works
        }
        class Project_Group {
            + Assists Dylan as needed
            + Learns from Dylan's progress
        }
    }

    package "DoosanRobot" {
        class Gijs {
            + Project Leader
            + Develops student program
            + Explains to other students how the robot works
        }
        class Project_Group {
            + Assists Gijs as needed
            + Learns from Gijs's progress
        }
    }

    package "AMR" {
        class Hailing {
            + Project Leader
            + Develops student program
            + Explains to other students how the robot works
        }
        class Project_Group {
            + Assists Hailing as needed
            + Learns from Hailing's progress
        }
    }
}
@enduml

```
## Indivisual project overview
The diagram represents a project with three robot systems: KUKA, Welding, and Doosan.

Right now we are at the beginning of the project. The plan for now is to do the following:

* KUKA: Plays tic-tac-toe with the project leader and teaches others how the game works.
* Welding: Focuses on welding tasks, with the leader developing the program and explaining it to others.
* Doosan: Picks and places blocks, sorting them by colors, with the leader guiding and teaching the process.

Each project group assists their leader and learns from their progress.

![Robot project overview](image-1.png)