#Concept Evaluation and Product Architecture
 ## Pugh Chart
 ***
 Table 1:Pugh chart for four alternative designs
| SL NO. | Design Objective        | Weights | Design 1 | Design 2 | Design 3 | Design 4 |
|--------|-------------------------|---------|----------|----------|----------|----------|
| 1      | Safety                  | 8       | -        | Datum    | +        | 0        |
| 2      | Ease of use             | 8       | +        | Datum    | +        | +        |
| 3      | Portability             | 5       | -        | Datum    | +        | +        |
| 4      | Use of standard parts   | 6       | +        | Datum    | -        | -        |
| 5      | Cost                    | 9       | +        | Datum    | -        | +        |
| 6      | Aesthetics              | 5       | +        | Datum    | +        | +        |
| **Score (+)**             |         |         | 28       | 0        | 26       | 27       |
| **Score (-)**             |         |         | 13       | 0        | 15       | 6        |
| **Total Score**           |         |         | 15       | 0        | 11       | 21       |
***
## Justification for the scores given
***

|Design No.|Objective|Score Allocated|Justification|
|----------|---------|---------------|-------------|
|          |Safety|-|Because sliding doors are not as air-tight|
|          |Ease of use|+|Because sliding doors are easy to use and automatic|
|      1   |Portability|-|Shape is less proprietary|
|          |Use of standard parts|+|Made out of rather available part sand material|
|          |Cost|+|Made out of cheaper parts |
|          |Aesthetics|-|Exposed wiring and minimum space to customize it|

|Design No.|Objective|Score Allocated|Justification|
|----------|---------|---------------|-------------|
|          |Safety|Datum| |
|          |Ease of use|Datum| |
|      2   |Portability|Datum| |
|          |Use of standard parts|Datum| |
|          |Cost|Datum| |
|          |Aesthetics|Datum| |

|Design No.|Objective|Score Allocated|Justification|
|----------|---------|---------------|-------------|
|          |Safety|+|Because of air tight sealing|
|          |Ease of use|+|Because of better UI interface|
|      3   |Portability|+|Because of a more standardized shape |
|          |Use of standard parts|-|Requires proprietary parts |
|          |Cost|-|because of the price of the parts which are more advanced|
|          |Aesthetics|+|It is compactly packed and there is no exposed wiring|

|Design No.|Objective|Score Allocated|Justification|
|----------|---------|---------------|-------------|
|          |Safety|0| |
|          |Ease of use|+|Because of  GPS navigation and RFID |
|      4   |Portability|+|Compact size|
|          |Use of standard parts|-|Lots of proprietary parts |
|          |Cost|+|Cheaper and more available technology is used|
|          |Aesthetics|+|Lots of free space to customize it |

##6.3 subsystem interaction details
***
|subsystem 1|subsystem 2|subsystem 3|subsystem 4|
|---------|---------|---------|----------|
|Spatial||y|||
|Data|y||y||
|material|||||
***
|subsystem 2|subsystem 1|subsystem 4|subsystem 3|
|--------|---------|----------|--------|
|spatial|||y|
|Data||y||
|material||||
***
|subsystem 3|subsystem 1|subsystem 2|subsystem 4|
|------|-------|-------|------|
|spatial||||
|Data|||y|
|material||||
***

