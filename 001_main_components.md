# Main Components

<br/>

## CPU

- Central Processing Unit
- a.k.a. **Processor**
- 프로그램으로부터 명령을 입력 받아 연산을 수행한다.
- CPU의 구성요소

  - `Control Unit`
    - CPU에 입력되는 명령의 순서를 관리한다.
    - 명령을 입력받고 디코딩하여 CPU가 명령을 수행할 수 있도록 한다.
    - CPU 및 CPU의 주변 기기들을 컨트롤한다. 즉, I/O 디바이스, ALU, 메모리 등이 CPU에 입력되는 명령에 대응하는 방식을 결정한다.
  - `ALU (Arithmetic Logic Unit)`
    - Register의 값을 이용해 연산을 수행한다.
    - 컴퓨터의 primary memory와 secondary memory 사이의 데이터 이동은 모두 ALU를 거친다.
  - `Register`
    - CPU의 연산을 위한 데이터를 저장한다. - 가장 작고 제일 빠른 기억 장치
  - `Cache`
    - RAM의 한 종류로서 CPU가 primary memory에서 읽은 데이터를 임시적으로 저장하여 데이터 접근 시간을 줄인다.
  - `Bus`
    - 서로 다른 하드웨어 구성요소 간의 링크이다. - 3가지 버스: Address bus, Data bus, Control bus

  <br>

---

## Main Board

- CPU, GPU, Main Memory 등 컴퓨터의 구성요소들을 한 데 묶는 중추역할을 한다.
- a.k.a. Mother Board

<br>

---

## RAM

- Random Access Memory
- Primary Memory
- Random Access는 CPU가 메모리의 어떠한 위치에도 즉시 접근할 수 있음을 의미한다.
- 일시적인 데이터 저장을 위한 칩들로 이루어져 있어 컴퓨터의 전원이 꺼지면 데이터가 사라진다.

<br>

---

## Hard Disk Drive (HDD)

- Secondary Memory
- RAM과 달리 컴퓨터의 전원이 꺼져도 데이터가 유지된다.

<br>

---

## Device Controller

- 컴퓨터의 주변 기기(입력 장치, 출력 장치, 저장 장치)들을 CPU와 연결.
- 각각의 기기마다 디바이스 컨트롤러를 갖고 있다.
  > 모니터, 프린터, 키보드, USB etc.
- 예를 들어 타자를 치면 키보드의 디바이스 컨트롤러가 CPU에 인터럽트를 걸어 디바이스 컨트롤러의 data register의 값을 읽도록 한다.

<br>

---

> 위 장치들은 비동기적으로 작동한다.
