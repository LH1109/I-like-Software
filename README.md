# I-like-Software

1. top 명령어 : top 명령어는 실시간으로 시스템의 프로세스와 자원 사용 상태를 모니터링하는 명령어입니다.
               명령어를 입력하게되면 CPU, 메모리 사용량, 각각의 프로세스 상태 등을 실시간으로 업데이트해서 보여주는 기능을 합니다.
               top의 주요 기능으로는 상위 자원 사용 프로세스 목록, 시스템의 요약 정보(CPU,메모리,스왑 등) 

2. ps 명령어 : ps명령어는 핹제 실행하고 있는 프로세스의 정보를 스냅샷 방식으로 출력하는 명령어입니다.
              사용방법은 ps명령어 뒤에 다양한 옵션을 붙여서 출력 형식을 조정할 수 있습니다.
              예를 들면 ps aux는 모든 사용자와 관련된 프로세스를 보여주고, ps -ef는 포맷된 스타일로 모든 프로세스를 보여줄수가 있고, ps -e명령어는 현재 실행중인 시스템의 모든 프로세스를 보여주는 역할을 합니다.


3. jobs 명령어 : jobs 명령어는 현재 쉘 세션에서 실행 중인 백그라운드 작업의 목록을 보여주는 역할을 하는 명령어입니다.
                사용법은 주로 백그라운드 작업 관리를 위해 백그라운드에서 &기호를 사용해 상태를 확인할 수 있습니다.
                각 작업의 상태(실행 중, 중단됨 등) 을 표시하며, 잡 번호를 통해 제어할 수 있습니다.

4. kill 명령어 : 마지막으로 kill 명령어는 특정 프로세스를 종료시키거나 신호를 보내는 역할을 하는 명령어입니다.
                사용방법은 프로세스 ID(PID)를 인수로 받아서 해당 프로세스에 종료 신호를 보내는 것이고, 주요 기능으로는 말한것처럼 종료신호를 보내는 것이지만, 옵션을 통해서 다양한 신호를 보낼 수 있습니다.
                예) kill [PID] : 기본 종료 신호
                   kill -9 [PID] : 강제 종료 신호 (SIGTERM)을 보냄.
                   kill -l : 사용 가능한 모든 신호 목록을 출력함.
   
