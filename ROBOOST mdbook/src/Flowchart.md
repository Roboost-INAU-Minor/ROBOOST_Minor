# Flowchart

This flowchart outlines the development and implementation process for four distinct robots: the WeldingRobot, KuKaRobot, DoosanRobot, and AMR. Each robot's workflow is broken into clearly defined steps to facilitate task execution and progression. 

- **WeldingRobot**: This robot's process involves assembling a hammer mold, programming the robot based on video guides, and ultimately using the hammer produced.
- **KuKaRobot**: The workflow includes conducting research on the robot and its vision system, followed by the creation of a student program incorporating vision capabilities.
- **DoosanRobot**: The process involves researching the robot and Coral def board, implementing the AMR system, and developing a student program. Each step builds on the previous to integrate functionality.

The steps for each robot are interconnected to guide the development process seamlessly.

```plantuml
@startuml
!define CIRCLE class
!define RECTANGLE class

CIRCLE WeldingRobot
RECTANGLE Step_1_Welding {
  Assemble the hammer mold.
}
RECTANGLE Step_2_Welding {
  Program the robot based on video guides.
}
RECTANGLE Step_3_Welding {
  Use the completed hammer.
}

WeldingRobot --> Step_1_Welding
Step_1_Welding --> Step_2_Welding : Place the mold into the welding tool.
Step_2_Welding --> Step_3_Welding : Remove the hammer from the mold.

CIRCLE KuKaRobot
RECTANGLE Step_1_KuKa {
  Conduct research on the robot.
}
RECTANGLE Step_2_KuKa {
  Develop the vision system.
}
RECTANGLE Step_3_KuKa {
  Create a student program with vision capabilities.
}

KuKaRobot --> Step_1_KuKa
Step_1_KuKa --> Step_2_KuKa : Develop a preliminary program.
Step_2_KuKa --> Step_3_KuKa : Enhance the program with vision integration.

CIRCLE DoosanRobot
RECTANGLE Step_1_Doosan {
  Conduct research on the robot.
}
RECTANGLE Step_2_Doosan {
  Explore the Coral def board.
}
RECTANGLE Step_3_Doosan {
  Test with the AMR system.
}
RECTANGLE Step_4_Doosan {
  Create a student program.
}

DoosanRobot --> Step_1_Doosan
Step_1_Doosan --> Step_2_Doosan : Study the Coral def board.
Step_2_Doosan --> Step_3_Doosan : Conduct simple tests with the vision system.
Step_3_Doosan --> Step_4_Doosan : Test and integrate the AMR system.

@enduml