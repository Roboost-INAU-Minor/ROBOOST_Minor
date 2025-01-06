# Task Overview
This document outlines the structure of a collaborative project involving multiple robotic systems. 
Each robot is assigned to a student who serves as the project leader, responsible for developing a guide for the group and explaining the robot's functionality. 
The project focuses on four robots: WeldingRobot, KuKaRobot, DoosanRobot, and AMR. 
For each robot, the assigned student leads development, explains the robot's operation, and collaborates with their project group, which provides assistance and gains knowledge throughout the process.

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
