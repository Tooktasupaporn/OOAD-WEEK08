# OOAD-WEEK08

## Use Case Diagram 
 ภาพที่ 1
 ![](@startuml

:tookta:
:mint: as Men2  
actor ton
actor :toon: as Men4

@enduml)

ภาพที่ 2
![](@startuml

mint -> (Start)
mint --> (Use the application) : A small label

:tookta: ---> (Use the telephone) : This is\nyet another\nlabel

@enduml)
 ภาพที่ 3
 ![](@startuml
:mint: as Admin
(Use the computer) as (Use)

tookta <|-- Admin
(Start) <|-- (Use)

@enduml)

ภาพที่ 4
![](@startuml
:tookta: --> (Use computer)
:tookta: -> (Use phone)
@enduml)

ภาพที่ 5
![](@startuml
:mint: -left-> (dummyLeft) 
:mint: -right-> (dummyRight) 
:mint: -up-> (dummyUp)
:mint: -down-> (dummyDown)
@enduml)
