---
name: "[Module]"
about: 모듈 템플릿
title: ''
labels: ''
assignees: ''

---

# 모듈 설명
Contest 모듈은 대회 관련 데이터를 관리하고 대회 생성 및 삭제, 대회별 랭킹 서비스 등을 제공합니다.

# 관련 데이터베이스 테이블
- contest
- contest_notice
- contest_rank_acm

# Use-Case(기획)
### contest
- public contest: 모든 user가 자유롭게 참여. `super_admin`이 개최 / `group_admin`의 요청으로 개최 가능
- private contest: `group_admin` 이 하나의 group 내에서 자유롭게 개최 가능
-  ,,,
### contest_notice
- `group_admin`은 대회 공지사항 생성, 열람, 수정, 삭제를 할 수 있다.
- `user`는 대회 공지사항의 목록과 내용을 열람할 수 있다.
### contest_rank_acm
- 대회의 랭킹은 acm rule을 따라 ...
