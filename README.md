# OOAD-WEEK11
State Diagram
 
 รูปที่ 1
 
 ```
@startuml

[*] -r-> LED_RED
title TRAAFIC LAMP
LED_RED : Waitfor 60 seconds
LED_GREEN : Waitfor 60 seconds
LED_YELLO: Waitfor 60 seconds

LED_RED -r-> LED_GREEN
LED_GREEN -r-> LED_YELLO
LED_YELLO -r-> [*]
LED_YELLO --> LED_RED 


@enduml


@enduml
 ```
 ![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUAArefLq2tIjLFmSNM93t9ruIh9BCb9LGW9SdHqytHMy77q3U22IYbOAOGdPfQavHSfc1ae5AScv-Ub58CbtODSNVrmIqUw-lZuOvM56mrt0jWe94FX4c134CP1982kHnP2U4E1YulB8JKl1UX70000)
