# OS

HTTPS 는  HTTP에서 보안성이 강화되었다고 생각하면 된다 

## HTTP 란?
  -> Hypertext transfer protocol 의 약자 -> 인터넷에서 사용하는 웹서버와 사용자의 인터넷 브라우저 에 문서를 전송하기 위한 통신규약
 - 인터넷에서 하이퍼텍스트를 교환하기 위해 사용되는 통신규약! - 포트번호 80이다. 
 - HEAD, GET , POST, DELETE, OPTION 등의 메소드를 사용
 - 팀버너스리 World Wide Web

 

## HTTPS란?
   ->HTTP프로토콜의 보안성을 강화한 프로토콜
   ->Hypertext Transfer Protocol over. 
   ->HTTP Secure , 통신의 인증과 암호화 -> 전자상거래에서 사용 
   
 ### 1) URL의 차이 : http:// ,  https://
 ### 2) 암호와의 차이 : HTTP : 암호화가 전혀 되지 않는 프로토콜 
                         -> 패킷캡쳐를 하면 다 드러남
                         -> HTTPS는 보안성을 위해 패킷을 암호화하여 전송 
                                                 *암호화는 Transport 계층에서 이루어진다. 
                         ->HTTPS는 HTTP보다 느리지만, 요즘은 속도에서 큰 차이가 없다. 
