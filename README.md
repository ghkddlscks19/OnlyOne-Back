# 벗킷(BuddKit)
<img width="931" height="504" alt="image" src="https://github.com/user-attachments/assets/e6512fdb-5d0a-4644-b64e-8425c6662a7c" />

## 프로젝트 개요
액티브 시니어는 관심과 의지는 충분하지만, 모임을 찾고 오프라인으로 전환하는 과정에서 주저하게 됩니다. <br>
벗킷(Bukkit)은 그런 시니어들을 위해 만들어진 **손쉽게 모임을 찾고 참여할 수 있는 시니어 콘텐츠 플랫폼**입니다.
> **액티브 시니어?**  
> 은퇴 이후에도 하고 싶은 일을 능동적으로 찾는 50~60대를 일컫는 말로,  
> 적극적으로 소비하고 문화 활동에 나선다는 점에서 ‘실버 세대'와 구분되는 시니어

- **기간**: 25.07 - 25.09
- **인원**: 6명 (풀스택)
- **영상**: https://drive.google.com/file/d/1P80JXV3FX1BPlqDrWWR8dHxgiOI-zlSb/view
- **역할**: 검색 도메인 풀스택 개발

## 기술 스택

### Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

### DataBase
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

### Infra
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

## 검색 기능

### 1. 키워드 기반 모임 검색 
Elasticsearch의 Nori 형태소 분석기로 한국어 검색 최적화 및 동의어·불용어 처리
### 2. 관심사 및 지역 필터 검색
사용자가 선택한 관심사 및 지역 조건을 QueryDSL 동적 쿼리로 처리
### 3. 사용자 맞춤 모임 추천
가입 시 설정한 지역·관심사 기반 2단계 추천 로직 구현 (위치 + 관심사 → 관심사 단독)
### 4. 팀원 모임 조회
함께 활동한 팀원들의 모임 탐색 기능
### 5. 내 모임 조회
참여 중인 모임 및 정산 미완료 일정 여부 조회
