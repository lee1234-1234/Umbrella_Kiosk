
<img width="416" height="749" alt="6d60002e-00ae-4fc4-b695-af80f892539b" src="https://github.com/user-attachments/assets/4de5e36d-319f-4b08-afcc-f065cbae22c4" />
# ⛱️ 스마트 공유 우산 플랫폼 (Smart Umbrella Sharing Platform)
> **IoT 기반의 지능형 우산 대여·반납 및 통합 관리 시스템**

본 프로젝트는 공유 경제 모델을 바탕으로 공공 우산의 체계적인 관리와 분실 방지를 위해 개발된 **소프트웨어·하드웨어 융합 플랫폼**입니다. 사용자의 NFC 인증을 통해 실시간으로 대여/반납 상태를 판별하며, 최적의 우산 컨디션 유지를 위한 자동 건조 기능을 제공합니다.

---

## ✨ Key Features
* **NFC Authentication**: 스마트폰 및 NFC 카드를 활용한 고유 식별 및 간편 대여/반납 프로세스
* **Intelligent Locking**: 솔레노이드 락과 정밀 설계 브라켓을 결합한 안정적인 우산 고정 메커니즘
* **Real-time Monitoring**: 7인치 LCD를 통해 대여 가능 여부 및 사용자 안내 메시지 출력
* **Automatic Drying**: 반납 감지 시 시로코 팬(Shirocco Fan)을 가동하여 우산의 물기 제거 및 부식 방지

---

## 🏗️ Hardware Architecture
시스템의 안정성을 위해 제어부와 구동부를 분리하여 설계하였으며, 모든 부품은 **Autodesk Fusion 360과 Tinkercad**로 정밀 모델링되었습니다.
<img width="1119" height="662" alt="0295a3eb-8f6e-41d8-8328-b8a0c5afe5e7" src="https://github.com/user-attachments/assets/af3076d0-5ff8-44f2-b738-93e6a64cf4da" />

### 📍 [Explore 3D Models (CAD)](./3d_models)

| 분류 | 상세 구성 (Design Details) | 핵심 부품 (Key Components) |
| :--- | :--- | :--- |
| **Main Control** | 시스템 전체 로직 제어 및 센서 데이터 처리 | **Arduino Giga R1**, 8-Ch Relay |
| **User Interface** | 사용자 인증 및 상태 정보 출력 | **PN532 NFC Module**, 7-inch LCD |
| **Actuator** | 물리적 잠금 및 건조 시스템 구동 | **Solenoid Lock**, **Shirocco Fan** |
