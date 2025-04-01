
9. класс или классы службы действительны для узла, который пытается войти в систему

Class 2 Svc Parameters
Class 3 Svc Parameters

10. Один из кадров, отправленных узлом, который зарегистрировался, декодируется как GID_FT (Get Port Ids - FC-4 Type). Какой протокол определяется в FC-4 type и какое у него шестнадцатеричное представление?

| No. | Time     | Source   | Destination | Protocol | Length | Info         |
| --- | -------- | -------- | ----------- | -------- | ------ | ------------ |
| 15  | 1.058767 | 2b.00.0a | ff.ff.fc    | dNS      | 80     | GID_FT       |
| 22  | 1.075836 | ff.ff.fc | 2b.00.0a    | dNS      | 92     | ACC (GID_FT) |
| 273 | 5.187617 | 2b.00.0b | ff.ff.fc    | dNS      | 80     | GID_FT       |
| 280 | 5.204877 | ff.ff.fc | 2b.00.0b    | dNS      | 92     | ACC (GID_FT) |

15 > dns

FC-4 Type: FCP (0x08)

11. Какая служба отвечает на запрос GID_FT?

F_CTL: 0x980000 Exchange Responder, Seq Initiator, Exchg Last, Seq Last CS_CTL

GS Type: Directory Service (0xfc)

12. Порты хранения в зоне, к которой принадлежит зарегистрированный узел, их имена:

22  | 1.075836 | ff.ff.fc | 2b.00.0a    | dNS      | 92     | ACC (GID_FT)
dnc
Port Identifier: 2b.00.07
Port Identifier: 2b.00.09
Port Identifier: 2b.00.0a
Port Identifier: 2b.00.0f

280 | 5.204877 | ff.ff.fc | 2b.00.0b    | dNS      | 92     | ACC (GID_FT)
Port Identifier: 2b.00.07
Port Identifier: 2b.00.09
Port Identifier: 2b.00.0b
Port Identifier: 2b.00.0c


Port Identifier: 2b.00.07 | Symbolic Port Name: EMC SYMMETRIX 000187910377 SAF-16cB EMUL B61F0000 128E2A40 38FC00 2C8238 04.22.09 14:55 5671_080  
Port Identifier: 2b.00.09 | Symbolic Port Name: EMC SYMMETRIX 000187910377 SAF- 1cB EMUL B61F0000 128E2A40 38FC00 2C8238 04.22.09 14:55 5671_080  
Port Identifier: 2b.00.0a | Symbolic Port Name: Emulex LP10000 FV1.90A4 DV6.02hx2
Port Identifier: 2b.00.0f | Symbolic Port Name: EMC SYMMETRIX 000187910377 SAF- 1cB EMUL B61F0000 128E2A40 38FC00 2C8238 04.22.09 14:55 5671_080  
Port Identifier: 2b.00.0b | Symbolic Port Name: Emulex LP10000 FV1.90A4 DV6.02hx2
Port Identifier: 2b.00.0c | Symbolic Port Name: EMC SYMMETRIX 000187910377 SAF- 1cB EMUL B61F0000 128E2A40 38FC00 2C8238 04.22.09 14:55 5671_080  

13. Есть ли какие-либо HBAs в этой зоне

HBA (Host Bus Adapter) — это адаптер, который соединяет сервер (хост) с SAN (Storage Area Network) через интерфейс Fibre Channel (FC). Каждый HBA имеет свой уникальный WWPN (World Wide Port Name) и WWNN (World Wide Node Name).


Fabric Port Name: 20:0e:00:0d:ec:18:cb:40 (Cisco)