# TM-02

실시간 웹캠 이미지를 캡처하고 Teachable Machine을 통해 이미지를 분류하는 웹 애플리케이션을 만드는 과정은 여러 기술과 리소스를 필요로 합니다.

필요한 기술 및 도구
1. HTML/CSS/JavaScript: 웹 페이지의 구조와 스타일링을 위해 필요합니다.
2. WebRTC API: 웹캠 액세스 및 실시간 스트림을 캡처하기 위해 사용됩니다.
3. Teachable Machine: 머신러닝 모델을 훈련하고 배포하는 데 사용됩니다.
4. TensorFlow.js: 브라우저에서 머신러닝 모델을 실행하는 데 사용됩니다.

단계별 구현 방법
1. HTML 페이지 구성
기본 HTML 페이지를 만들어 웹캠 피드와 결과를 표시하는 요소를 추가합니다.

2. 웹캠 액세스 설정
WebRTC API를 사용하여 웹캠 피드를 가져옵니다.

3. Teachable Machine 모델 로드 및 예측
Teachable Machine에서 훈련된 모델을 로드하고 웹캠 이미지를 분류합니다.
