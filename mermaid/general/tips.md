[README](/README.md) | [THE EXAMPLES](/mermaid/the-examples.md) | [TIPS](/mermaid/general/tips.md) | [ISSUES](/mermaid/general/issues.md)

# Tips

### Comments

```mermaid
classDiagram

%% This is a comment
A .. B

                    %% This is another comment

```

### Identation is ignored

identation is ignored.  Therefore, use it to make the mermaid code more readable

```mermaid
classDiagram

%% Without Identation
InventoryItem2 <|-- LotNumberedInventoryItem2 : is a
InventoryItem2 : size()
InventoryItem2 : int chimp
InventoryItem2 : int gorilla

%% With Identation...

%% InventoryItem
    InventoryItem <|-- LotNumberedInventoryItem : is a
        %% Properties
        InventoryItem : int chimp
        InventoryItem : int gorilla
        %% Methods
        InventoryItem : size()
```