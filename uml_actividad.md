---
marp: false
---

@startuml
start
:Add games to cart;
:Checkout;
:Check coockie;
while(if cookie?) is (is invalid)
:Show login form;
endwhile
fork
:Mail invoice;
fork again
:Load games;
end fork
:Install and play;
end
@enduml