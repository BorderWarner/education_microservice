# Создание ADR 

## Схема

```puml
@startuml
title Course of action for ADR

top to bottom direction

!includeurl https://raw.githubusercontent.com/RicardoNiepel/C4-PlantUML/master/C4_Component.puml

System("furps", "Требования FURPS+", "Функциональные, удобство, надежность, производительность, сопровождаемость, +ограничения")
System(adl, "Создаем ADR", "Описываем проблемы по шаблонам")
System(use_ceses, "Формулируем Use Cases исходя из функциональных требованийп", "Описываем проблемы по шаблонам")

Rel(furps, adl, "")
Rel(adl,use_ceses,"")
@enduml
```

---