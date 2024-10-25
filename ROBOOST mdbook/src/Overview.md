# Task overview
```plantuml

@startuml
package "Project Overview" {
    class Hailing { 
        + Make sure the documentation of the 3 projects stays on point.
        + Communication with the client.
    }
    package "WeldingRobot" {
        class Bram {
            + Project leader.
            + Develop stundent program.
            + Explain the rest of the students how the robot works.
        }
        class Project_group {
            + Assist bram where needed.
            + Learn from the progress Bram makes.
        }
    }

    package "KuKaRobot" {
        class Dylan {
            + Project leader.
            + Develop stundent program.
            + Explain the rest of the students how the robot works.
        }
        class Project_group {
            + Assist bram where needed.
            + Learn from the progress Bram makes.
        }
    }

    package "DoosanRobot" {
        class Gijs {
            + Project leader.
            + Develop stundent program.
            + Explain the rest of the students how the robot works.
        }
        class Project_group {
            + Assist bram where needed.
            + Learn from the progress Bram makes.
        }
    }
}
@enduml
