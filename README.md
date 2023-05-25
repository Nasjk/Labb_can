# Labb 2 CAN

Laborationen genomfördes i grupper om 2 studenter

Arbetet inleddes med att ta reda på vilka meddelanden som sänds från den lilla fordonsriggen och identifiera i vilket meddelande som information om blinkers sänds. Detta gjordes med hjälp av CAN funktionen i något av de nyare oscilloskopen och rätt trigger-funktion inställd.

Därefter skrevs det mjukvara för Arduino som tar emot data från fordonsriggen och blinkar rätt LED beroende på om blinkers kommando för vänster/höger sväng ges.

Mjukvaran skrevs i Arduino IDEt för enkel åtkomst till de drivrutiner som CAN interfacet kräver.


