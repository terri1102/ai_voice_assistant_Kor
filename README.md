# Ai_voice_assistant_Kor
---
한국어 음성 인식 비서를 만드는 프로젝트입니다.


주요 기능은 다음과 같습니다.

1. Wake-word detection
2. Speech Recognition
3. Text Summarization


## 1. Wake-word detection
제 목소리로 'A비서'라고 부르는 2초 가량의 오디오 파일을 수집하였고 이를 타겟 클래스 1로 설정하였고,
주변 소리와 일상 대화 음성 파일을 2초 가량으로 잘라서 타겟 클래스 0으로 설정하여 이를 분류하는 이진분류 모델을 만들었습니다.
