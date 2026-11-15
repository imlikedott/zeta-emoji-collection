# 제타 기분 이모지 도감

상태창 '기분' 옆에 뜬 이모지를 모으는 도감 + 내 도트 캐릭터 놀아주기 (선물 상자·꼬마 친구·미니게임·업적, 채팅방·캐릭터별 도감)

- 버전: **1.0**
- 제작·출처: **제타 여성향 갤러리 ㅇㅇ**
- 사용 사이트: [제타](https://zeta-ai.io/)

## 주요 기능

- 상태창의 기분 이모지 수집·확인
- 채팅방·캐릭터별 도감 분류
- 내 캐릭터 이미지 등록
- 캐릭터 돌보기·놀기·외출·휴식
- 선물 상자·꼬마 친구·미니게임·업적·칭호 제공
- 새 기분 이모지에 따른 캐릭터 자동 반응 및 ON/OFF 설정
- 도감 내보내기·가져오기 제공

## 사용 방법

1. 유저스크립트 관리 확장 프로그램에 스크립트 등록·저장
2. 제타 페이지 새로고침
3. 화면의 도감 버튼 클릭
4. **내 캐릭터 올리기**에서 이미지 등록

수집 범위: 화면에 표시되는 상태창의 새 이모지. 설치 전 전체 대화 자동 조회 미지원.

## 데이터 보관

- 저장 위치: 사용 중인 브라우저의 제타 사이트 저장 공간
- 저장 항목: 도감 기록·캐릭터 이미지·진행 상황·설정
- 사이트 데이터 삭제 또는 브라우저·기기 변경 시 기록 유실 가능
- **내보내기**를 통한 기록 백업 가능
- 내보내기 코드에 캐릭터 이름·채팅방 경로·기분 기록·캐릭터 이미지 포함 가능 — 공개 공유 주의
- 채팅 API·로그인 토큰 미사용
- 글꼴·이모지 이미지 표시를 위한 외부 CDN 접속

## 외부 자료 출처 및 라이선스

### Twemoji — 이모지 이미지

- 제작: Twitter, Inc. 및 Twemoji 기여자
- 사용 프로젝트: [jdecked/twemoji](https://github.com/jdecked/twemoji)
- 이미지 라이선스: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
- [프로젝트의 이미지 라이선스 원문](https://github.com/jdecked/twemoji/blob/main/LICENSE-GRAPHICS)
- 사용 방식: jsDelivr CDN에서 원본 SVG 로드
- 변경 사항: 원본 이미지 수정 없음, 화면 표시 크기만 조정
- Twemoji JavaScript 라이브러리 미포함

### Galmuri — 도트 글꼴

- 제작: [quiple](https://github.com/quiple)
- 프로젝트: [Galmuri](https://github.com/quiple/galmuri)
- 라이선스: [SIL Open Font License 1.1](https://github.com/quiple/galmuri/blob/main/ofl.md)
- 사용 버전: 2.40.3
- 사용 방식: jsDelivr CDN에서 스타일시트·글꼴 로드
- 변경 사항: 글꼴 파일 수정 없음

라이선스 적용 범위: 각 외부 자료에 한정. 스크립트 전체에 대한 별도 오픈소스 라이선스 부여 없음.
