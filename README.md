# Toxicity Detection using Natural Language Processing
### 악성댓글 탐지를 위한 자연어처리 모델
2023년 2학기 자연언어처리 기말 프로젝트 결과물입니다. 

## 👨‍🏫프로젝트 소개
"악성댓글 탐지를 위한 자연어처리 모델"이라는 주제의 프로젝트입니다.
수업에서 배운 여러가지 모델 중 
구현이 간단하고 단어의 중요도에 초점을 둔 BOW 기반 모델
단어의 순서와 문맥정보를 반영하면서 LSTM보다는 빠른 학습과 예측이 가능한 GRU 기반 모델
장기 의존성을 더 잘 학습할 수 있는 LSTM 기반 모델을 적용하여 결과를 비교했습니다.


## ⏲개발 기간
2023년 10월 ~ 2023년 12월

## 🧑‍🤝‍🧑개발자
1인 개발

## 📜프로젝트 파일 목록
![image](https://github.com/user-attachments/assets/de4a828e-3e2d-4222-8a5a-c604cfe05f98)<br>
data와 model은 용량이 너무 커서 업로드가 되지 않습니다.
data의 경우 아래 구글 드라이브를 통해 확인하실 수 있습니다.

[학습과 추론할 데이터] https://drive.google.com/drive/folders/1xdNv1RXF0C2jiZ9K-nfRXhhWtpBRRasJ?usp=sharing
[추론 결과 데이터] https://drive.google.com/drive/folders/1hI-JF2H1OGzgeQcHF6u3lmaFGYUCcaM9?usp=sharing

## 🔍프로젝트 결과
![image](https://github.com/user-attachments/assets/ee9f0625-5489-4997-8d30-436f37a87182)
![image](https://github.com/user-attachments/assets/2df5dd09-dd01-4c83-9e03-e33bdf148162)

악성댓글 탐지는 잘못된 양성(정상 댓글을 악성댓글로 분류하는 경우)를 줄이고 실제 악성 댓글을 놓치지 않고 검출하는 등
정밀도와 재현율 그리고 F1 점수가 중요한데, 이를 체크해보지 못한 점이 아쉽다.
