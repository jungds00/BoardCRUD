# 게시판 관리 시스템 CRUD

## 📌 프로젝트 설명
이 프로젝트는 간단한 게시판 관리 시스템을 구현한 것으로, 사용자는 개별 게시판에 게시글을 작성하거나, 댓글을 달 수 있습니다.

## 🛠 프로젝트 설치 및 실행 방법

### 1. Java 설치

#### 이 프로젝트는 Java 17 버전을 기반으로 합니다. Java 17을 설치해주세요.
  
### 2. 프로젝트 클론
```bash
   git clone [프로젝트_레포지토리_링크]
```

### 3. Dependencies 설치

#### 이 프로젝트는 다양한 의존성을 가지고 있습니다. 프로젝트의 pom.xml 또는 build.gradle 파일을 통해 의존성을 확인하고 설치해주세요.

### 4. 프로젝트 실행
  
  
## 📖 프로젝트 사용방법

#### 프로젝트를 시작하고 테스트 하기 전에, [H2 Console](http://localhost:8080/h2-console/) 링크로 접속하여 아래의 쿼리를 실행하셔서 사용자를 추가해야합니다.
```sql
INSERT INTO writer(display_name) VALUES ('[사용자이름]');
```
## ✨ 주요 기능 

### 아래 기능들에 관한 [API 명세서](https://documenter.getpostman.com/view/26198634/2s9Y5SW667) 와 [데이터 스키마](https://dbdiagram.io/d/64e0617102bd1c4a5e09ab95) 링크로 접속하여 기능과 상황별 테스트 결과와 데이터 스키마를 확인하실 수 있습니다.
---
### 게시판 관리

사용자는 게시판을 생성, 수정, 삭제할 수 있습니다.
각 게시판은 고유한 이름, 타입, 순서번호 등을 가집니다.
사용자는 자주 방문하는 게시판을 즐겨찾기로 설정할 수 있습니다.

 * 게시판 목록 조회
 * 게시판 상세 조회
 * 게시판 생성  
 * 게시판 수정  
 * 게시판 삭제  

### 게시글 관리

사용자는 특정 게시판에 게시글을 작성, 수정, 삭제할 수 있습니다.
게시글은 제목, 내용, 작성시간, 수정시간 정보를 포함하며, 어떤 게시판에 속하는지도 표시됩니다.

 * 게시글 목록 조회
 * 게시글 상세 조회
 * 게시글 작성
 * 게시글 수정  
 * 게시글 삭제  
 
### 댓글 기능

사용자는 게시글에 댓글을 달 수 있습니다.
댓글은 내용, 작성시간, 수정시간 정보를 포함합니다.

 * 댓글 목록 조회
 * 댓글 상세 조회
 * 댓글 작성
 * 댓글 수정
 * 댓글 삭제
---
