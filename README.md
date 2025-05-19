# 음성 인식 웹 어플리케이션
음성_인식_웹_어플리케이션

## 애플리케이션 구조
```text
```

## 사전 준비사항
1. 아래 명령어 실행
```text
pip install flask flask-cors flask-sock openai-whisper pyngrok soundfile
```

## 시작하기
# ngrok 인증토큰 생성
1. ngrok 웹사이트에 가입합니다 (아직 계정이 없는 경우).
2. 가입 후 대시보드에서 인증 토큰을 확인합니다.
3. 아래 코드를 새로운 셀에 붙여넣고, YOUR_AUTH_TOKEN 부분을 본인의 토큰으로 바꿔 실행합니다:

# 로컬 실행
1. 아래 명령어 실행
```text
ngrok authtoken YOUR_NGROK_AUTH_TOKEN
ngrok --version
```
 > `{{YOUR_AUTH_TOKEN}}`은 앞서 생성한 ngrok토큰 값
2. 아래 명령어 실행
```text
python run_server.py
```
3. 터미널 창에 생긴 주소로 접속

