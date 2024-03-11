# Database(DB)

- [제로초님의 DB강의](https://www.inflearn.com/course/%EB%B9%84%EC%A0%84%EA%B3%B5%EC%9E%90-%EC%A0%84%EA%B3%B5%EC%9E%90-%EB%94%B0%EB%9D%BC%EC%9E%A1%EA%B8%B0-%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4-sql/dashboard)를 듣고 정리한 내용

- [내가 참고할 링크 - 제로초님 repo](https://github.com/ZeroCho/cs-database)

## 데이터베이스를 왜 배워야 하는가?

- 회사에서 가장 중요하게 생각하는게 뭘까?
  → data
- 유튜브 소스코드를 얻었다 쳐보자
  → 유튜브에 코드가 다 있지만 클론코딩해도 사람들은 그걸 쓰지 않는다. 유튜브만의 자산이 있기에(유튜버 등)
- 프론트엔드는 DB에 접근하려면 백엔드를 거쳐야함. 직접 못가져옴.
  - 프 → 백 → DB → 백 → 프

## SQL(Structured Query Language)

- 나와 데이터베이스 사이에서 소통하는 언어
- **ANSI SQL - 표준 SQL 문법**. 대부분 DBMS에서 돌아감.

## DBMS(Database Management System)

- MySQL 설치하기(PostgreSQL, MSSQL, Oracle, MariaDB, SQLite 등등) - SQL 언어의 사투리
- [다운로드 링크](https://dev.mysql.com/downloads/installer/)
- 5버전 8버전 다 괜찮음 - ANSI SQL 쓸거니까
- SQL 문법 이 강의 듣고 다 까먹을거임(백엔드 아닌 이상 쓸 일이 없다보니). 그럴 땐 [database cheat sheet](https://cheatography.com/tag/database/) 검색해서 보기
  - 치트 시트 하나만 있어도 까먹더라도 나중에 보면 기억 날 것임. 마음에 드는거 딱 하나. 나에게 맞게 고쳐쓰기. 치트 시트 많이 활용해보기
  - 물고기를 잡아주기 보단(지식을 알기보단) 물고기를 잡는 방법을 알려주는 강좌
- **MySQL 대표 포트: 3306**
- MySQL도 **DB ‘Server’**다.
  - 항상 실행중 상태로 유지시키기. 컴퓨터 킬때 자동으로 실행됨
