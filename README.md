@startuml
left to right direction
actor "клиент" as fc
rectangle Автомойка {
  usecase "Найти автомойку" as UC1
  usecase "Найти дату и время" as UC2
  usecase "Оплата" as UC3
  usecase "Выбрать услугу" as UC4
  usecase "Поддержка" as UC5
}
fc --> UC1
fc --> UC2
fc --> UC3
fc --> UC4
fc --> UC5
@enduml
