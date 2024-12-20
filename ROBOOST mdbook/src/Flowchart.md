# Flowchart

This flowchart provides a detailed process for the development and implementation of four different robots: the WeldingRobot, KuKaRobot, DoosanRobot, and AMR. Each robot follows a series of steps designed to complete specific tasks. The WeldingRobot involves assembling a hammer mold, programming the robot, and using the completed hammer. The KuKaRobot focuses on research, including vision system development and creating a student program. The DoosanRobot undergoes research on the robot and Coral def board, testing with vision and AMR systems, before developing a student program. Each robot's steps are linked in a clear progression to guide the development process.


```plantuml

@startuml
!define CIRCLE class
!define RECTANGLE class


CIRCLE WeldingRobot
RECTANGLE Step_1_Welding {
  Assemble the hammer mold.
}
RECTANGLE Step_2_Welding {
  Program the robot according to the video guides.
}
RECTANGLE Step_3_Welding {
  Enjoy the hammer 
}

WeldingRobot --|> Step_1_Welding
Step_1_Welding --|> Step_2_Welding : Place the mold into the welding tool.
Step_2_Welding --|> Step_3_Welding : Take the hammer out the mold.



CIRCLE KuKaRobot
RECTANGLE Step_1_KuKa {
  Research on the robot.
}
RECTANGLE Step_2_KuKa {
  Research the vision part.
}
RECTANGLE Step_3_KuKa {
  Develop a student program.
}


KuKaRobot --|> Step_1_KuKa
Step_1_KuKa --|> Step_2_KuKa : Create a small programm.
Step_2_KuKa --|> Step_3_KuKa : Create a small programm with vision.

CIRCLE DoosanRobot
RECTANGLE Step_1_Doosan {
  Research the robot.
}
RECTANGLE Step_2_Doosan {
  Research the Coral def board.
}
RECTANGLE Step_3_Doosan {
  Implement the AMR system.
}
RECTANGLE Step_4_Doosan {
  Develop a student program.
}


DoosanRobot --|> Step_1_Doosan
Step_1_Doosan --|> Step_2_Doosan : Place the mold into the welding tool.
Step_2_Doosan --|> Step_3_Doosan : Simple test with vision system.
Step_3_Doosan --|> Step_4_Doosan : Simple test with the AMR system.


@enduml
