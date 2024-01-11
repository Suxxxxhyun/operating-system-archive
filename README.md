# computer-science-archive

## operating-system 
- 운영체제 개요 및 컴퓨터 시스템 동작원리
  - [운영체제란 무엇인가? 또한 어떤 역할을 수행하는가?](https://github.com/Suxxxxhyun/computer-science-archive/blob/main/os/os-learning(1).md)
  - [운영체제의 분류에 대해 알고있니?](https://github.com/Suxxxxhyun/computer-science-archive/blob/main/os/os-learning(7).md)
    - 다중 프로그래밍, 시분할 시스템, 대화형 시스템, 다중 처리기 시스템
  - [커널이란?](https://github.com/Suxxxxhyun/computer-science-archive/blob/main/os/os-learning(2).md)
    - 커널 : 운영체제의 '핵심 서비스'를 담당하는 부분
  - [시스템 콜, 인터럽트? 커널모드, 유저모드?]()
  - [PCB와 Context-Switch?](https://github.com/Suxxxxhyun/computer-science-archive/blob/main/os/os-learning(3).md)
    - PCB : 프로세스 관련 정보를 저장하는 자료구조로, **마치 옷에 달려있는 태그와 같다.**
  - [프로세스의 메모리 영역 중 사용자 영역은 어떻게 되어있을까?](https://github.com/Suxxxxhyun/computer-science-archive/blob/main/os/os-learning(4).md)
    - 사용자 영역 : CODE, DATA, STACK, HEAP
  - [부모 프로세스는 자식 프로세스를 어떻게 만들어내고, 자식프로세스는 어떻게 자신만의 코드를 실행할까?](https://github.com/Suxxxxhyun/computer-science-archive/blob/main/os/os-learning(5).md)
    - fork(), exec()
  - [멀티프로세스와 멀티스레드의 차이는 무엇일까?](https://github.com/Suxxxxhyun/computer-science-archive/blob/main/os/os-learning(6).md)
    - 자원을 공유하느냐, 하지 않느냐
  - [폴링이 뭐야? 인터럽트와 비교되는 개념이라는데?]()
    - cpu를 양도하느냐, 양도하지 않느냐
  - [DMA?]()
    - DMA(Direct Memory Access) : cpu외에 메모리 접근이 가능한 장치
  - [동기식 I/O와 비동기식 I/O의 공통점과 차이점은 무엇일까?]()
    - 동기식I/O와 비동기식 I/O의 공통점은 I/O연산이 완료되면 인터럽트를 통해 CPU에게 알리게 된다.
    - 차이점은 I/O작업이 끝나기를 Requesting process가 기다리냐, 기다리지 않느냐에 차이라고 할 수 있다.