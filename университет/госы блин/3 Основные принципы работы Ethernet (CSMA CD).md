
CSMA/CD - Carrier Sense Multiple Access with Collision Detection - технология множественного доступа с прослушиванием несущей частоты и обнаружением коллизий.
протокол, использующий эту технологию, также называется CSMA/CD, в модели OSI работает на канальном уровне.
CSMA/CD используется в сетях Ethernet и высокоскоростных сетях Fast Ethernet, Gigabit Ethernet.

применяется в сетях с логической общей шиной. все устройства имеют доступ к общей шине и она может быть использована для передачи информации между любыми двумя узлами сети. все устройства имеют возможность немедленно получить данные. кабель, к которому подключены все устройства, работает в режиме множественного доступа, поэтому существует риск коллизии.

коллизия - событие, при котором два устройства одновременно отправляют данные, из-за чего содержимое кадров сталкивается на общем кабеле и данные могут быть смешаны.

методы обнаружения коллизий зависят от используемого оборудования, но на электрических шинах, таких как Ethernet, коллизии могут быть обнаружены сравнением передаваемой и получаемой информации. если она различается, то другая передача накладывается на текущую (возникла коллизия) и передача прерывается немедленно. посылается сигнал преднамеренной помехи, что вызывает задержку передачи всех передатчиков на произвольный интервал времени, снижая вероятность коллизии во время повторной попытки.

чтобы получить возможность отправить кадр, устройство должно убедиться, что среда свободна. для этого устройство прослушивает текущую частоту. если во время передачи кадра рабочая станция обнаруживает другой сигнал, занимающий передающую среду, она останавливает передачу, посылает сигнал преднамеренной помехи и ждёт в течение случайного промежутка времени (известного как «backoff delay» и находимого с помощью экспоненциального двоичного алгоритма выдержки), перед тем как снова отправить кадр.

после окончания передачи все устройства делают технологическую паузу в 9,6 мкс для приведения сетевых адаптеров в исходное состояние.

обнаружение коллизий используется для улучшения производительности CSMA с помощью прерывания передачи сразу после обнаружения коллизии и снижения вероятности второй коллизии во время повторной передачи.

сигнал преднамеренной помехи (англ. jam signal) в телекоммуникациях — 32-битный сигнал с битовым шаблоном, отправленным станцией, чтобы информировать остальные станции о том, что они не должны осуществлять передачу.

Замечания:

- В carrier sense multiple access with collision detection (CSMA/CD) сетях jam signal обозначает возникновение коллизии.
- В carrier sense multiple access with collision avoidance (CSMA/CA) сетях jam signal обозначает намерение станции начать передачу.
- Не надо путать сигнал преднамеренной помехи с электронными помехами.