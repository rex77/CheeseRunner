# CheeseRunner
다수의 사용자가 목적지까지 경주하는 서버/안드로이드 어플리케이션

# 제작 목적
하나의 목적지를 설정하여 서로 다른 위치에 있는 참가자들이 그 목적지까지 이동하고, 최종적으로 누군가가 먼저 목적지에 도착하면 승리하는 게임을 구현한다. 
참여자들은 실시간으로 서로의 위치를 공유한다.

# 가상 시나리오
모임을 하는 4명의 젊은 친구들이 있다. 이 친구들은 항상 약속 시간과 약속 장소를 정해놓아도 제각각 도착해 서로에게 불만 아닌 불만이 쌓인 상태이다. 어느날 그들은 약속을 지킬 방법을 궁리하다 약속 장소까지 일찍 도착하면 승리하는 게임을 하면 어떨까? 라는 생각을 하게 된다. 그런 목적에 맞게 CheeseRunners라는 어플리케이션을 사용한다.

# 사용 기술
Monitering Application:
Android OS

Application SDK:
Flutter

IDE:
Visual Studio Code

Server(WAS):
Ubuntu 20.04
Tomcat 8
(On Amazon EC2)

DataBase:
MySQL 8.0
Server-Application Interface:
Restful API

Back-end Framework:
Spring Boot 
(Managed By Gradle)

IDE:
IntelliJ IDEA
Restful API

역할분담:
Rexa: Android App, Project Management
changeme: Backend Application, Server, DataBase
