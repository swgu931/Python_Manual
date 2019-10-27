# Python_Manual

 구글에서 제공하는 Colab 을 활용
 - 별도 환경을 로컬PC에 셋업하지 않고, 인터넷만 연결하면 손쉽게 Python을 익히는데 집중할 수 있음

## 환경 세팅 및 간단 사용법

### 환경 세팅
1) Google 계정으로 로그인

2) colab.research.google.com 으로 접속 --> 새파일을 생성
   - 혹은 Drive 로 접속 --> 새파일을 만둘고, --> 연결할 앱 (더보기) --> colab 연결하기
  
3) 사용할 준비 완료
   - GPU 를 사용하고 싶으면 '수정' --> '노트설정' 에서 GPU 를 선택
    (런타임유형 : Python 3 , 하드웨어 가속기 : GPU 선택)

### 간단 사용법
1) numpy, TensorFlow 버전 확인
2) Short Key 사용법
   - 셀 실행은 Shift + Enter 혹은 Ctrl + Enter
   - 아래에 셀 추가는 Ctrl + M + B
   - 위에 셀 추가는 Ctrl + M + A
   - 셀 삭제는 Ctrl + M + D
   - 행번호 출력 출력상태에서는 감춤 은 Ctrl + M + L
   - 기타 단축키가 보고 싶거나 추가로 설정하고 싶으면 Ctrl + M + H
3) 구글 드라이브와 연결 (mount) 하여 활용
   - 아래 명령어를 실행
   
    from google.colab import drive
   
    drive.mount('/content/drive')
 
4) Github에 있는 소스를 직접 연결 
   - https://colab.research.google.com/github/<github.com 이후 path>
   
   
4) Linux shell 명령어는 다음과 같이 "!" 와 함께 실행 (간단한 것만)

    !ls

    !pwd
    
5) 현재 dir 내의 file 들을 보고 싶으면 
   - import os 를 실행
   - Directory 를 이동할 때는 cd 혹은 os.chdir 을 사용합니다

Appendix
   - 내 PC 에 있는 file 을 upload 하거나 download 하는 방법
    
    https://colab.research.google.com/notebooks/io.ipynb
