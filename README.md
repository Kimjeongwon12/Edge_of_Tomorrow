# Edge of Tomorrow

![Image](https://github.com/user-attachments/assets/558666a7-24e9-4c78-ade5-8a2ff03c0927)

## 📖 프로젝트 소개
Memory Loop RPG는 영화 Edge of Tomorrow에서 영감을 받아 제작한 텍스트 기반 루프 생존 게임입니다.
플레이어는 전장에서 반복적으로 죽음을 경험하면서 기억을 축적하고, 점차 더 멀리 전진해
최종 보스 오메가를 처치하여 인류를 구원하는 것이 목표입니다.

## 📌 주요 기능
|기능 | 설명 |
|---|---|
|고정된 전장 시나리오 | 총 5단계 전장 (해변, 참호, 단독 탈출, 통신탑, 오메가 전투)|
|자유 입력 방식 | 선택지가 아닌 텍스트 입력으로 행동을 직접 입력|
|AI 생존/사망 판정 | Ollama의 EEVE-Korean-10.8B 모델로 생존/사망 여부 판단|
|루프 시스템 | 사망 시 기억을 유지한 채 루프 재시작|
|보스전 시스템 | 최종 단계에서 오메가와 결전|

## 🛠 기술 스택
|구분 | 기술
|---|---|
|언어 | Python|
|LLM API | Ollama (EEVE-Korean-10.8B)|
|UI 프레임워크 | Gradio |
|개발 환경| Jupyter Notebook|

## 🎬 게임 플레이 흐름
전장의 상황이 출력됩니다.

사용자는 자신의 행동을 자유롭게 입력합니다.

EEVE 모델이 생존 또는 사망 여부를 판정합니다.

생존 시 다음 전장으로 넘어가고, 사망 시 기억을 남긴 채 루프가 다시 시작됩니다.

모든 단계를 넘어 최종 보스를 물리치면 게임을 클리어합니다.

## 📜 전장 구성
|단계 | 설명|
|---|---|
|1단계 | 해변 착륙 후 기계 생명체 공격 속 은폐 및 초기 대응|
|2단계 | 참호 전투, 매복 회피 및 근접 교전 생존|
|3단계 | 상관 전사 후 단독 생존, 통신 복구 및 은밀 이동|
|4단계 | 적 통신탑 돌파, 방어 드론 회피 및 교란|
|5단계 | 오메가 본진 침투, 약점 공략 및 최종 전투|

## 🛤 향후 개선 방향 (Roadmap)
🔥 루프 수 카운트 및 플레이 요약 기능

🔥 다양한 전장의 상황 생성

🔥 메모리(기억) 로그를 플레이어에게 보여주는 시스템

🔥 다양한 엔딩 분기 추가 (숨겨진 히든 엔딩)

🔥 생존 확률 통계 및 행동 추천 기능

🔥 사운드 효과 / 배경음 추가 (몰입 강화)
