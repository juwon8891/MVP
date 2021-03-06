# 프로젝트 개요
- 시각장애인의 이동권 향상을 위해, 컴퓨터 비전 기술을 통해 전방의 지형지물 및 장애물을 안내하여 안전하게 보행하실 수 있도록 돕는 프로젝트

## 주요기능
- 바닥지형 안내
- 횡단보도 건너기 보조
- 장애물 충돌 위협 감지

## 아키텍처

# 개발자
- 지우석
- 이동관
- 황주원

# 규약

## Commit convention rule

### Commit Heading

> 1. feat : 새로운 기능 ✨
> 2. fix : 버그 수정 🐛
> 3. build : 빌드 관련 파일 수정 🏗️
> 4. chore : 그 외 자잘한 수정 ✏️
> 5. ci : CI관련 설정 수정 👷
> 6. docs : 문서 수정 📝
> 7. style : 코드 스타일 혹은 포맷 등 💄
> 8. refactor :  코드 리팩토링 ♻️
> 9. test : 테스트 코드 수정 ✅

### Commit Message

```
heading : 커밋 메세지 (한글 25자, 영어 50자 이내)

- 커밋 설명 1 (한글 36자, 영어 72자 이내)
- 커밋 설명 2
- 커밋 설명 3
```

예시
```
fix : 로그인 시 쳣 자를 잘못 인식하는 버그 수정

- 특정 조건에서 아이디의 첫 글자를 무시하는 현상 수정 (#23h246)
- 향후 패스워드에서도 동작하는지 확인 필요, 리팩토링 필요
```