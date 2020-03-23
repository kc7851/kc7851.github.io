---
layout: post
title: 2020-03-20 Daily Journal
date: 2020-03-20 09:16:01 0900
category: DailyJournal
---

## 이번 달 목표
매일 목표를 꾸준히

### 매일 목표:
- [ ] ~~스쿼트 50개 이상~~
- [ ] ~~명상하기~~
- [x] 출근 후 책 읽기
- [x] 인강 1개씩 보기

### 토요일:
- [ ] ~~스쿼트 50개 이상~~
- [x] 명상하기
- [x] 인강 1개씩 보기

### 일요일:
- [x] 스쿼트 50개 이상
- [x] 명상하기
- [x] 인강 1개씩 보기

### 읽을 책 목록:
- [ ] ~~iDDD~~

### 어제 한 일:
* 조회된 리스트에서 특정 항목을 사용자 입력을 받아 업데이트 처리.

### 장애물:
* 출근 후 책 읽기를 실천해야 겠다.
* ajax로 data를 json으로 보낼 때 value에 객체의 배열일 때 controller에서 어떤 argument resolver를 사용해야 할지 어렵고 어떤 type으로 받아야 할 지 어려움.
  * 처음 원한 형태는 List<Map<String, Object>> dataList 였는데 잘 안됨.
  * javascript에서 배열에 객체를 담을 때 JSONStringify를 사용해서 String으로 변환 후 Controller에서 @RequestParam(value="dataList[]") List<String> dataList 로 받음.
  * list를 loop돌면서 객체문자열을 JSONObject로 변환후 Map으로 변환. 이 Map을 List<Map>에 add하면서 처음 생각한 List<Map<String, Object>>의 형태로 만듬

### 오늘, 주말 할 일:
* 엑셀파일 업로드해서 값 읽는 것.
* 게시판 글 쓰기, 그림파일 업로드 처리.