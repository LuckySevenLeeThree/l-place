![Lplace (1)](https://github.com/user-attachments/assets/fd73f43c-2478-4ded-8aa0-71117c0f8bb8)


</div> 

## 📝 소개
실시간 픽셀아트 프로젝트로 자유롭게 캔버스에 그리고싶은 도트디자인을 그려보세요!

- 프로젝트 기간: 2024.11.13~2025.01.16
- 배포 : 

## 💁‍♂️ 프로젝트 팀원
| BE & FE  | BE & FE | DevOps
|:---:|:---:|:---:|
| ![](https://github.com/Hello-LSY.png?size=120)  | ![](https://github.com/realcold0.png?size=120) | ![](https://github.com/lee-JunR.png?size=120)
| [이신영](https://github.com/Hello-LSY)         |  [이승환](https://github.com/realcold0) | [이준렬](https://github.com/lee-JunR)          


## 화면 구성
|실시간 캔버스|채팅|
|:---:|:---:|
|<img src="https://user-images.githubusercontent.com/80824750/208456048-acbf44a8-cd71-4132-b35a-500047adbe1c.gif" width="400"/>|<img src="https://github.com/user-attachments/assets/25c8ad40-e65c-4067-8a95-da2d252e6810" width="400"/>|



## **⚙ 기술 스택**
### **Back-end**
<div>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
</div>

---

### **Front-end**
<div>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
</div>

---

### **Infra**
<div>
<img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</div>

---

### **CI/CD & Tools**
<div>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
</div>

## 🤔 기술적 이슈와 해결 과정

- 실시간성을 어떻게 보장할까?
  - [비트필드 방안](https://github.com/LuckySevenLeeThree/l-place-back-end/pull/1)
    - [비트필드 오류 수정](https://github.com/LuckySevenLeeThree/l-place-back-end/pull/7)
  - [dom -> canvas방식으로 최적화](https://github.com/LuckySevenLeeThree/l-place-front-end/pull/2)
- 서버 운영 시 과부하가 발생한다면 어떻게 체크해야할까?
  - [grafana + promethus 모니터링 구성하기](https://github.com/LuckySevenLeeThree/l-place-back-end/issues/4)
- 픽셀아트 서비스를 어떻게 개선해야할까?
  - 실시간 캔버스 수정
    - [팔레트 ui 수정, 줌, 드래그 수정 1차](https://github.com/LuckySevenLeeThree/l-place-front-end/pull/3)
    - [드래그, 줌 수정 2차](https://github.com/LuckySevenLeeThree/l-place-front-end/pull/5)
  - [사용자 커서 기능 추가](https://github.com/LuckySevenLeeThree/l-place-front-end/pull/4)
    - [커서 오류 수정](https://github.com/LuckySevenLeeThree/l-place-front-end/pull/7)
  - [채팅 기능 추가](https://github.com/LuckySevenLeeThree/l-place-front-end/pull/1)
## 🛠️ 프로젝트 아키텍쳐


