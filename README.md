# network-security
[whs] network-security

1. 프로그램 실행 오류 시 ip a 명령어를 실행하여 네트워크 인터페이스를 확인
2. 129줄 코드 handle = pcap_open_live("eth0", BUFSIZ, 1, 1000, errbuf); 중 eth0 인자를 본인의 네트워크 인터페이스로 교체
3. gcc 컴파일을 수행 후 해당 프로그램으로 재실행 후 테스팅 필요
