# Task overview
This overview illustrates the structure of a collaborative project involving multiple robotic systems. 
Each robot is assigned to a student who is responsible for developing a guiding for rest of the group and the students. 
The project focuses on four robots: the WeldingRobot, KuKaRobot, DoosanRobot, and AMR. 
For each robot, the responsable student leads development and explains the robot's functioning, while their project group provides assistance and learns from the progress made.



![alt text](image-1.png)

```plantuml

@startuml
package "Project Overview" {
Top to bottom direction
    package "WeldingRobot" {
        Left to right direction
        class Bram {
            + Project leader.
            + Develop student program.
            + Explain the rest of the students how the robot works.
        }
        class Project_group {
            + Assist Bram where needed.
            + Learn from the progress Bram makes.
        }
    }

    package "KuKaRobot" {
        class Dylan {
            + Project leader.
            + Develop student program.
            + Explain the rest of the students how the robot works.
        }
        class Project_group {
            + Assist Dylan where needed.
            + Learn from the progress Dylan makes.
        }
    }
    package "DoosanRobot" {
        class Gijs {
            + Project leader.
            + Develop student program.
            + Explain the rest of the students how the robot works.
        }
        class Project_group {
            + Assist Gijs where needed.
            + Learn from the progress Gijs makes.
        }
    }

    package "AMR" {
        class Hailing {
            + Project leader.
            + Develop student program.
            + Explain the rest of the students how the robot works.
        }
        class Project_group {
            + Assist Hailing where needed.
            + Learn from the progress Hailing makes.
        }
    }
}
@enduml
