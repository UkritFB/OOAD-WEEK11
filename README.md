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

LED_RED -r-> LED_GREEN : CHENGE LED
LED_GREEN -r-> LED_YELLO : CHENGE LED
LED_YELLO -r-> [*]
LED_YELLO --> LED_RED  : CHENGE LED


@enduml
 ```
 ![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUAArefLq2tIjLFmSNM93t9ruIh9BCb9LGW9SdHqytHMy77q3U22IYbOAOGdPfQavHSfc1ae5AScv-Ub58CbtODSNVrmIqUw-lZuOvM56mrt0imePmzNFtTNa12I3N1LO1CnLK64mQg0_a8MGdXG0LKR5vT3QbuAC2W0)

รูปที่ 2

```
@startuml

title CAR
[*] -l-> READY
READY --> [*]
READY : CAR THIS STOP
LEFT : CAR GO LEFT
RIGH: CAR GO RIGH
GO: CAR GO STAGE

READY -up-> GO 
GO  -l-> LEFT 
LEFT -down-> RIGH

READY --> READY
READY --> GO 
READY --> LEFT 
READY --> RIGH

GO  --> READY
GO  --> GO 
GO  --> LEFT 
GO  --> RIGH

LEFT --> READY
LEFT --> GO 
LEFT --> LEFT 
LEFT --> RIGH

RIGH --> READY
RIGH --> GO 
RIGH --> LEFT 
RIGH --> RIGH

@enduml
```

![](http://www.plantuml.com/plantuml/img/NP512y8m38Nl-HKv2_q37cH3PpSG9bil8Xw4xI3CJRJ3ls-Ihbdn4lZIzruUDFlu-zlFpm70F_pGupvluBgveHdC3fiYFrn09XfYUbXeoq9qPTLYw-epd8gZMvQsHYPeAblgXW5ihTowt1OGe-SNXTEM51WkIrv8DTtq7RaCHoHb_iknVwKGaAZ5BVdgZQINrQSwSOKQQbDadqBQU6rBCoqRKRf6MAggL9oGzMD7__83)

รูปที่ 3
