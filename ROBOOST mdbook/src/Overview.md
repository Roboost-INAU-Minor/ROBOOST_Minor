# Chapter 1
```plantuml

@startuml
actor Students
actor ResearchersSaxion
actor TeachersSmeot

entity TechYourFuture
entity SMEOT
entity MinorIndustrialAutomation

usecase WeldingStation
component WeldingRobot
component KuKaRobot
component DoosanRobot
component AMR

usecase vision
usecase/ "welding/" 

Students -- MinorIndustrialAutomation : Following the minor
MinorIndustrialAutomation -- TechYourFuture : Assisting TechYourFuture
ResearchersSaxion -- TechYourFuture : Developing educatinal material

TechYourFuture -- SMEOT : Designing a module for level 3 students in robotics
TeachersSmeot -- SMEOT : Designing a module for level 3 students in robotics

KuKaRobot -- vision
DoosanRobot -- vision

SMEOT -- WeldingRobot : Welding a item
SMEOT -- DoosanRobot : Assist the welding robot
SMEOT -- KuKaRobot : Select the right components for the robot with the use of vision

DoosanRobot -- WeldingStation : Assist the welding robot
WeldingRobot -- WeldingStation : Welding a "Thor" hammer

KuKaRobot -- AMR : Brings selected components to on the AMR
AMR -- WeldingStation : Brings components to the welding robot

WeldingStation -- "welding/"

@enduml

