# REVT_calculator_OPEN
REVT 수용 계산기. 기초선과 최고한계선 구하기 가능

# 🧩 REVT 자동 계산기 (REVT Calculator)

**김하은 | 나사렛대학교 IT인공지능학부**
**진유빈, 진승빈 | 나사렛대학교 언어치료학과**

---

## 📍개발 목적
언어치료사가 REVT(수용·표현어휘력검사)를 실시할 때,
정답·오답 결과에 따라 **기초선과 최고한계선을 자동으로 계산**해주는 프로그램입니다.
복잡한 수동 계산을 줄이고 평가의 정확도와 효율성을 높이기 위해 개발했습니다.

---

## 💡주요 기능
- 정답(✅) / 오답(❌) 버튼 클릭 시, 자동으로 기초선·최고한계선 계산  
- 실시간 동적 계산 구조 (별도의 입력 불필요)  
- 점수 및 진행 상태 실시간 표시  
- Python(Flask) + HTML5로 제작  

---
시작화면에서 아동의 나이를 선택할 수 있습니다.
<img width="751" height="563" alt="Image" src="https://github.com/user-attachments/assets/3009721e-b0bc-42ac-8976-a1fc9e1e185f" width="50%"/>

---
> 위 화면처럼 정답(+) 또는 오답(-)을 누르면 프로그램이 자동으로 출력됩니다.
> 기초선과 최고한계선을 찾아내고 결과를 저장합니다.
<img width="718" height="614" alt="Image" src="https://github.com/user-attachments/assets/2fa1e887-5319-4c09-9692-7f14daf27c1c" width="50%"/>

---
> 기초선이 잡히면 검사 중 기초선 위치가 하단에 나타납니다.
<img width="571" height="546" alt="Image" src="https://github.com/user-attachments/assets/0f6439d4-c2eb-4301-b074-b26f94a5fef0" width="50%"/>
---
> 최고한계선이 설정되면 자동으로 검사가 종료됩니다.
> 오답문항과 기초선, 최고한계선을 한 번에 볼 수 있는 페이지가 생성됩니다.
<img width="525" height="879" alt="Image" src="https://github.com/user-attachments/assets/26881e81-9441-4324-b3cd-affc3152a713" width="50%"/>

---
검사 결과를 pdf로 출력하여 받아볼 수 있습니다.
[검사결과지.pdf](https://github.com/user-attachments/files/23295814/default.pdf)



---
## 🚀 향후 계획
현재는 수용어휘 자동 계산까지만 구현되었습니다.
이후 버전에서는 음성 입력·자동 기록 기능을 적용해
표현어휘 계산까지 확장할 예정입니다.

# 🧩 REVT 자동 계산기 (수용어휘 영역)

REVT(수용·표현어휘력검사)의 수용어휘 부분을 자동으로 계산하는 웹 프로그램입니다.  
아동의 정·오답을 입력하면 즉시 기초선과 최고한계선을 산출하는 동적 계산 구조로 설계되었습니다.

📍 현재는 수용어휘까지 구현되었으며,  
다음 단계로 **음성 입력 기반의 표현어휘 계산기**를 개발할 예정입니다.  


🔒 전체 코드는 비공개로 관리되고 있습니다.  
연구·실습용 협업 또는 확인이 필요하신 분은 아래로 연락해 주세요.  

📩 Contact: kyua5568@naver.com
## 🧰 기술 스택
Python, Flask, HTML5, CSS, ChatGPT API, Copilot
