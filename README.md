<div align="center">

# 김윤기 · Backend Developer

우아한테크코스 8기 백엔드 **토리**

<a href="https://tory4953.tistory.com"><img src="https://img.shields.io/badge/Blog-FF5A4A?style=flat-square&logo=tistory&logoColor=white"/></a> <a href="https://solved.ac/tuise/"><img src="https://img.shields.io/badge/solved.ac-17CE3A?style=flat-square"/></a> <a href="mailto:kimyungi1008@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>

<br/>

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>

</div>

<br/>

## 🎓 우아한테크코스 8기 백엔드

| 레벨 | 학습 주제 | 미션 |
|:---:|---|---|
| 1 | Java · 객체지향 설계 | 블랙잭, 장기 (DB 적용) |
| 2 | Spring 웹 애플리케이션 | 방탈출 예약 관리 · 사용자 예약 · 예약 대기, 인증과 인가 |
| 3 | 팀 프로젝트 | DFGG (아래) |
| 4 | Spring 내부 동작 직접 구현 | HTTP 서버(Tomcat) · 동시성 확장, @MVC 프레임워크, JDBC 라이브러리 |

🎤 **테코톡** "Rate Limit을 만나면 백엔드는 어떻게 동작해야 할까?" 발표 (DFGG의 Riot API 호출 제한 대응 경험)

📚 전체 미션과 리뷰 기록 → [woowacourse-8th](https://github.com/K-iise/woowacourse-8th)

<br/>

## 🎮 DFGG

> **내 게임의 10명 조합을 보고 아이템 순서와 이유를 추천하는 LoL 아이템 추천 서비스**
> &nbsp;[GitHub](https://github.com/woowacourse-teams/2026-dfgg) · [dfgg.pro](https://www.dfgg.pro/) · 2026.08 ~ · 백엔드

- 📥 **데이터 수집** · Riot API 기반 수집·정규화·통계 파이프라인 설계 및 운영
- 🚦 **호출 제한 대응** · 429 재시도, DB 우선 조회, 참가자 티어 추가 조회 생략으로 API 호출량 절감
- 🤖 **추천 모델** · LightGBM Learning-to-Rank 모델 기반 v4 추천 API 구현
