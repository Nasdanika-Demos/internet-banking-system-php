This is an example of a code component documentation with a [PlantUML sequence diagram](https://plantuml.com/sequence-diagram).
"Mainframe Banking System" sequence diagram element is linked to the [Mainframe Banking System](../../../../mainframe-banking-system/index.html) page.

```uml
hide footbox

boundary MainframeBankingSystemFacadeImpl

MainframeBankingSystemFacadeImpl -> BankingSystemConnection: Uses
BankingSystemConnection -> Alice: Authentication Response
BankingSystemConnection -> Mainframe Banking System [[../../../../mainframe-banking-system/index.html]]: Sends
BankingSystemConnection <-- Mainframe Banking System: Receives
```

