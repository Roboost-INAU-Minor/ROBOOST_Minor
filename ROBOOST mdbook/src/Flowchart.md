# Flowchart
```plantuml

@startuml
!define RECTANGLE class
!define DIAMOND diamond

RECTANGLE Step_1 {
  Doosan robot picks block of the slide.
}
RECTANGLE Step_2 {
  Coral devboard scans color or shape.
}
RECTANGLE Step_3 {
  Places item on the right place of the AMR 
}
RECTANGLE Step_4 {
  AMR goes to cordinated location
}
RECTANGLE Step_5 {
  
}
RECTANGLE Step_6 {
  
}
RECTANGLE Step_7 {
  
}
RECTANGLE Step_8 {
  
}
RECTANGLE Step_9 {
  
}
RECTANGLE Step_10 {
  
}


Step_1 --|> Step_2 : Block is picked up.
Step_2 --|> Step_3 : Color scanned. \n AMR in place
Step_3 --|> Step_1 : AMR not full. \n requirements
Step_3 --|> Step_4 : AMR full.


@enduml
