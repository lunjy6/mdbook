Introduction 
===

This is the introduction of the book.

鬼佬好賓妹  
港女愛洋腸  
阿姨包鮮肉  
北姑求港佬


```mermaid
   graph TB;
    id1(男)
    id2(女)
    id3(男)
    id4(女)
        id3 <--> id2;
        id1 <--> id4;
                
    subgraph ide1[陳]
        id1 <--> id2;
        
    end

    subgraph ide2[張]
     id3 <--> id4;
     
    end

  
```

``` mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    ORDER ||--|{ LINE-ITEM : contains
    ORDER {
        int orderNumber
        string deliveryAddress
    }
    LINE-ITEM {
        string productCode
        int quantity
        float pricePerUnit
    }
```