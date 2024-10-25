# Flowchart
```plantuml

@startuml
!define CIRCLE class
!define RECTANGLE class
!define DIAMOND diamond

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
  
}
RECTANGLE Step_2_KuKa {
  
}
RECTANGLE Step_3_KuKa {
  
}
RECTANGLE Step_4_KuKa {
  
}
RECTANGLE Step_5_KuKa {

}

KuKaRobot --|> Step_1_KuKa
Step_1_KuKa --|> Step_2_KuKa : Place the mold into the welding tool.
Step_2_KuKa --|> Step_3_KuKa : Follow the created guide videos.
Step_3_KuKa --|> Step_4_KuKa : Follow the created guide videos.
Step_4_KuKa --|> Step_5_KuKa : Follow the created guide videos.

CIRCLE DoosanRobot
RECTANGLE Step_1_Doosan {
  
}
RECTANGLE Step_2_Doosan {
  
}
RECTANGLE Step_3_Doosan {
  
}
RECTANGLE Step_4_Doosan {
  
}
RECTANGLE Step_5_Doosan {

}

DoosanRobot --|> Step_1_Doosan
Step_1_Doosan --|> Step_2_Doosan : Place the mold into the welding tool.
Step_2_Doosan --|> Step_3_Doosan : Follow the created guide videos.
Step_3_Doosan --|> Step_4_Doosan : Test
Step_4_Doosan --|> Step_5_Doosan : Test

@enduml
