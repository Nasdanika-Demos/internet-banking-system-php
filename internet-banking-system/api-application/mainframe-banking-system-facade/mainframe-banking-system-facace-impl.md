This is an example of a code component documentation with a [PlantUML sequence diagram](https://plantuml.com/sequence-diagram).
"Mainframe Banking System" sequence diagram element is linked to the [Mainframe Banking System](../../../../mainframe-banking-system/index.html) page.

```uml
hide footbox

boundary MainframeBankingSystemFacadeImpl 
control BankingSystemConnection
participant "[[../../../../mainframe-banking-system/index.html{Stores all of the core banking information} Mainframe Banking System]]" as MBS 

MainframeBankingSystemFacadeImpl -> BankingSystemConnection: Uses
BankingSystemConnection -> MBS : Sends
BankingSystemConnection <-- MBS : Receives
```

