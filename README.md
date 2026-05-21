# 🦵 Re-Legs  
### 사용자 능동 참여형 다리 재활 의료기기 (CPM)

> 기존의 단순 수동 운동(Passive Motion) 기능에  
> 환자의 능동적 참여(Active Motion)를 결합하여  
> 효과적인 근력 강화 및 보행 준비를 돕는 스마트 재활 시스템

---

# 📌 프로젝트 개요 (Overview)

기존의 CPM(Continuous Passive Motion) 장비는 환자가 직접 힘을 주지 않아도 기기가 반복적으로 다리를 움직여주는 방식으로, 초기 관절 구축 방지에는 효과적입니다.  

하지만 수동적인 운동만으로는 실제 보행에 필요한 **근력 회복 및 능동적 재활 단계**로 이어지기 어렵다는 한계가 존재합니다.

**Re-Legs**는 이러한 문제를 개선하기 위해:

- 🔹 Passive Mode 기반 반복 재활 운동
- 🔹 환자의 힘을 직접 감지하는 Active Mode
- 🔹 실시간 상태 모니터링 시스템

을 통합하여, 환자의 능동적 참여를 유도하는 스마트 재활 의료기기를 목표로 개발되었습니다.

---

# 🎯 주요 기능 (Key Features)

## 🔄 Rehabilitation Modes

### 🟦 Passive Mode

기존 CPM 방식과 동일하게 모터를 이용하여 설정된 각도 범위를 반복 운동합니다.

- 일정 속도의 반복 운동 수행
- 관절 강직 및 구축 예방
- 초기 재활 단계 지원

---

### 🟥 Active Mode

환자가 직접 힘을 가하면 압력 센서(로드셀)가 이를 감지하여 운동이 수행됩니다.

- 환자의 능동적 참여 유도
- 근력 강화 훈련 가능
- 열린사슬운동(OKC) 및 부분체중부하(PWB) 훈련 지원
- 실제 보행 단계 이전의 근육 활성화 목적

---

# 🖥️ Real-time Monitoring

## LCD 디스플레이 기반 상태 출력

실시간으로 운동 상태를 확인할 수 있도록 LCD 기반 UI를 구성하였습니다.

### 표시 정보
- 현재 재활 모드 (Active / Passive)
- 실시간 압력 수치
- 관절 각도 데이터
- 운동 상태 및 진행 정보

---

# 🚀 Future Roadmap (미구현)

## 🤖 AI 기반 개인 맞춤형 재활 시스템

향후에는 환자의 재활 데이터를 기반으로 한 AI 분석 시스템을 추가할 예정입니다.

### 계획 기능
- 환자별 근력 및 회복 데이터 저장
- 운동 패턴 및 저항 변화 분석
- 강화학습(RL) 기반 재활 프로토콜 추천
- 환자 맞춤형 저항 부하 자동 조절

---


# 📐 System Architecture



---

# 📸 Project Results

## Hardware 



## UI Screen
<img width="500" height="300" alt="Active_mode" src="https://github.com/user-attachments/assets/abe2823c-90b4-4885-aead-1e6f8ad71537" />
<img width="500" height="300" alt="passive_mode" src="https://github.com/user-attachments/assets/bb0dc754-b9fc-44ae-9475-4171b9bf9827" />


---

# 👥 Team Members

| 이름 | 역할 | 담당 업무 |
|:---:|:---:|---|
| **안세환** | 👑 팀장 | 전체 시스템 구성 및 재활 방식 기획/개발<br>UI 제작 |
| **김관우** | 💻 개발 | Unity 연동 및 콘텐츠 개발<br>DB 설계 및 중계 PC 시스템 개발<br>각도 모듈 및 통신 프로토콜 개발 |
| **김정헌** | ⚙️ 개발 | 모터 제어 알고리즘 개발<br>압력 측정 모듈 개발<br>STM32 내부 제어 시스템 구현 |
| **송선대** | 🛠️ 기구부 | 기구부 설계 및 제작 프로세스 자문 |

---
