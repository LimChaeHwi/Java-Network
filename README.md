# Java-Network
자바네트워크 프로그래밍
- 채널(Channel) : 애플리케이션 간의 데이터 흐름을 나타냄
- 버퍼(Buffer) : 데이터를 처리하기 위한 채널과 함께 동작
- 셀렉터(Selector) : 다중 채널을 처리하기 위한 싱글 스레드를 허용하는 기술

- FileChannel : 파일과 함께 동작
- DatagramChannel : UDP 통신을 지원
- SocketChannel : TCP 클라이언트와 함께 사용
- ServerSocketChannel : TCP 서버와 함께 사용

서버가 클라이언트와 통신을 하기 위해 사용하는 것이 소켓이다.
소켓에는 여러 종류가 존재함. TCP UDP

