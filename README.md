# Alone-Unity-
# 프로젝트 소개
맵을 탐색하며 아이템을 획득하고, 적과 싸우며 레벨을 올려 다양한 스킬을 배워가며 생존하는 게임입니다.
<br>
대학교에서 창업동아리로 인정받아 지원금을 받으며 5명의 인원이 모여 Unity 엔진을 학습하면서 동시에 개발하였습니다.
<br>(파일은 에셋 저작권 이슈로 못 올렸습니다.)
# 프로젝트 개요
- 개발기간 : 약 1년
- 개발인원 : 5명
- 개발도구 : Unity
- 개발언어 : C#
- 플랫폼 : PC
- 게임장르 : 생존게임

# 담당 역할
인벤토리와 관련된 모든 기능 구현을 담당하였습니다. 아이템 기능구현, DB 생성, 획득, 사용, 버리기, 무기 장착 등과 UI를 담당하였습니다.

# 개발 주요 포인트
접근성을 낮추기 위해
- 복잡한 키 입력없이 마우스 클릭만으로 플레이
- 직관적인 UI 채택

자유도를 높이기 위해
- 다양한 아이템의 종류를 구현하여 사용자의 성향에 맞춰 플레이
- 다양한 스킬을 구현하여 매 게임마다 다른 육성이 가능
- 제작시스템을 도입하여 다양한 아이템을 제작할 수 있도록 함

# 게임 기능
### 시스템 구조도
![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/05abb235-08d0-41a0-8463-1247f90b5c6e)

### 메인화면
![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/c1a5755c-539d-4a36-b3e2-04f40e0926af)

초기화면에서 옵션을 통해 사운드와 해상도 조절이 가능합니다.

### 튜토리얼
![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/1d076369-6c4f-48fc-89ba-c95b4f449c8c)

주인공의 간단한 서사와 함께 플레이 진행방식을 설명합니다.

### 맵 탐색
![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/eb393068-f19f-4873-b998-d13499b7ae2d)

주인공을 클릭하여 주위 지형으로 이동이 가능합니다.

![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/38bf2088-a49e-448f-a189-86c7531dbed9)

타일 클릭시 해당 출현 몬스터와 출현 아이템 등의 정보를 확인할 수 있습니다.

![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/d2c9727d-ba4b-40dd-a77a-2ef0c7538387)

탐색 시 아이템을 획득하거나 몬스터와 조우 할 수 있습니다. 경험치 또한 얻을 수 있습니다.

![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/6545fb79-26e2-43fc-9843-a33244cf5575)

획득한 아이템은 사용하거나 조합하여 새로운 아이템을 제작할 수 있습니다.

![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/439f7041-32b6-4dd6-a2fc-838155ce4420)

획득한 장비를 장착하여 능력치를 높일 수 있습니다.

### 전투 시스템
![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/a12dbb2a-d92d-42db-bdac-aa346c14b9bf)

적과 조우하게 되면 전투에 도입하게 됩니다.

![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/290b0612-ff72-4e43-8fd8-edfd96bfa33e)![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/ed3b0e31-afcf-456d-837e-8e89cfe74631)

전투 시작 전 상대 몬스터의 특징을 확인하고 인벤토리에서 적절한 장비를 착용할 수 있습니다.
또한 전투에 사용할 수 있는 스킬은 최대 5개입니다. 시작 전 스킬을 선택하여 전투에 돌입하게 됩니다.
이후 턴제 방식으로 전투가 벌어집니다.

![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/0a3c8838-db0e-421f-926b-a96921c8b55c)

전투에서 승리하게 되면 보상 아이템과 경험치를 얻을 수 있습니다. 이때 레벨업을 하게 된다면 랜덤으로 새로운 스킬을 배울 수 있습니다.

![image](https://github.com/sbs524/Alone-Unity-/assets/80670002/355a797f-7c6e-4716-8148-4b00d13d4c99)

전투에서 패배하게 된다면 게임은 종료됩니다.
