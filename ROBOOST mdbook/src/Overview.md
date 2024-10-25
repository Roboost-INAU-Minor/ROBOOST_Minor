# Task overview
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
