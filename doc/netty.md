데이터모델 볼때 다시볼듯

#### Bootstrap 클래스
* 클라이언트와 서버용(ServerBootstrap) 으로 나뉘며 Netty를 초기화하는 최상위 클래스 이다.
.bind(int) : Netty르르 이용하여 통신할 포트를 지정한다.  
.channel() : 통신방식을 지정한다. (블락킹 or 논블락킹)  
.connect() : 통신을 시작한다.  

#### SimpleChannelInboundHandler 인터페이스
* 클라이언트 핸들러  
.messageReceived() : 데이터 전송 시 실행된다.
#### ChannelInboundHandlerAdapter 인터페이스
* --
.channelActive() : 소켓채널 최초활성화 시 실행된다.