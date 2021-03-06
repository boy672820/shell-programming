Shell Programming
=================
2017-02-13(월) 리눅스 셸 프로그래밍 교육내용

# 목차
>1. ## Getting started with Linux
>	1. ### 리눅스 기초
>		1. 리눅스의 구조
>
>	2. ### 리눅스 환경 구축
>		1. 가상머신(Virtual Machine)
>			1. 가상머신(Virtual Machine) 이란?
>			2. 가상머신의 종류
>			3. Oracle VM VirtualBox 설치
>			4. 가상머신 만들기
>		2. 페도라 설치하기
>			1. 디스크 파티션 수동 설정하기

>2. ## 리눅스 디렉터리와 파일 사용하기
>	1. ### 리눅스 파일의 종류와 특징
>		1. 파일의 종류
>			1. 일반 파일(Regular File)
>			2. 디렉터리(Directory)
>			3. 심볼릭 링크
>			4. 장치파일
>			5. 파일의 종류 확인: file 명령어
>
>	2. ### 디렉터리의 종류와 특징
>		1. 디렉터리의 종류
>			1. 루트 디렉터리의 서브 디렉터리
>			2. 작업 디렉터리
>			3. 홈 디렉터리
>			4. 디렉터리의 주요 기능
>		2. 디렉터리 내용보기
>			1. ls 명령어
>			2. ls 명령어 사용
>			3. ls 명령어 사용: -a 옵션으로 숨김 파일 확인
>			4. ls 명령어 사용: -F 옵션으로 종류 구분하여 출력하기
>			5. ls 명령어 사용: 지정한 디렉터리 내용 출력하기
>			6. ls 명령어 사용: -l 옵션으로 상세한 정보 출력하기
>		3. 파일 상세 정보
>			1. 파일 상세 정보 확인: ls -l 명령어
>			2. 2.3.2. 파일 상세 정보
>			3. 파일 종류
>
>	3. ### 파일 다루기
>		1. 파일 내용 연속 출력하기
>			1. cat 명령어
>			2. cat 명령어 사용: 파일 내용 확인
>			3. cat 명령어 사용: 행 번호 붙이기
>		2. 화면 단위로 파일 내용 출력하기
>			1. more 명령어
>			2. more 명령어 사용
>		3. 파일 뒷부분 출력하기
>			1. tail 명령어
>			2. tail 명령어 사용
>			3. tail 명령어 사용: 지정한 숫자만큼 출력하기
>			4. tail 명령어 사용: 주기적으로 반복 출력하기
>		4. 파일 복사하기
>			1. cp 명령어
>			2. cp 명령어 사용: 두 인자가 모두 파일인 경우
>			3. cp 명령어 사용: 두 번째 인자가 디렉터리인 경우
>			4. cp 명령어  사용: 인자를 여러 개 지정할 경우
>			5. cp 명령어 사용: -i 옵션 사용하기
>			6. cp 명령어 사용: 디렉터리 복사하기
>		5. 파일 이동하기
>			1. mv 명령어
>			2. mv 명령어 사용: 파일을 파일로 이동하기
>			3. mv 명령어 사용: 파일을 다른 디렉터리로 이동하기
>			4. mv 명령어 사용: 파일 여러 개를 디렉터리로 이동하기
>			5. mv 명령어 사용: -i 옵션 사용하기
>			6. mv 명령어 사용: 디렉터리를 디렉터리로 이동하기
>		6. 파일 삭제하기
>			1. rm 명령어
>			2. rm 명령어 사용
>			3. rm 명령어 사용: -i 옵션 사용하기
>			4. rm 명령어 사용: 디렉터리 삭제하기
>		7. 파일 링크
>			1. 파일 링크란?
>			2. 리눅스 파일의 구성
>			3. ln 명령어
>			4. ln 명령어 사용
>			5. 심벌릭 링크 만들기: -s 옵션
>			6. 심벌릭 링크와 하드 링크의 차이
>		8. 파일 내용 검색하기
>			1. grep 명령어
>			2. grep 명령어 사용
>		9. 파일 찾기
>			1. find 명령어
>			2. find 명령어 사용
