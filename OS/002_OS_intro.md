 # What is Operating System?

## Definition

- **운영체제**는 컴퓨터의 소프트웨어 자원들과 컴퓨터 하드웨어 사이의 중간자 역할을 담당하는 **소프트웨어**이다. 대부분의 소프트웨어들은 하드웨어와 직접적으로 상호작용 할 수 없기 때문에 운영체제가 그 역할을 대신한다.
- 운영체제는 컴퓨터의 모든 **자원을 관리**한다. 여기서 자원 (resource)은 Memory와 CPU를 의미한다. 운영체제는 또한 **프로그램(프로세스)의 실행을 관리**한다.
  - `CPU 관리`: 사용자가 프로그램을 실행하면 OS는 secondary storage에서 프로그램에 해당하는 데이터를 컴퓨터의 main memory에 로드(load)한다. 이후 운영체제는 scheduler를 통해 CPU가 **multi-tasking**을 실현할 수 있도록 한다. 또한 인터럽트를 통해 CPU와 I/O device의 작동을 관리한다.
  - `Memory 관리`: 각각의 프로세스는 메모리를 할당 받는다.
- 사용자 입장에서 운영체제는 **편의성**과 **생산성**을 위한 소프트웨어이다.
  - 운영체제는 복잡한 하드웨어의 작동을 사용자로부터 숨긴다.
  - 사용자는 운영체제로부터 user interface를 제공받는다.
    > CLI (Client User Interface), GUI (Graphic User Interface)
