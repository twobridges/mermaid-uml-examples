[README](../../README.md)
| 
[THE EXAMPLES](../the-examples.md)
| 
[TIPS](../general/the-examples.md)
| 
[ISSUES](../general/issues.md)

# Class Diagrams in UML

https://www.visual-paradigm.com/guide/uml-unified-modeling-language/uml-aggregation-vs-composition/


# Mermaid Model Examples

```mermaid
classDiagram
    %% Inventory Item
        InventoryItem <|-- LotNumberedInventoryItem : is a
        InventoryItem : size()
        InventoryItem : int chimp
        InventoryItem : int gorilla

    Invoice *-- InvoiceItems : cannot exist without

    %% Class09
    Class09 --> C2 : Where am i?
    Class09 --* C3
    Class09 --|> Class07

    %% Class07
    Class07 .. Class08
    Class07 : equals()
    Class07 : Object[] elementData
    Class08 <--> C2: Cool label
    Car o-- Wheel : part of, can be removed
```
