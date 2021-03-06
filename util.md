# 유틸리티

## 계산

입력된 수식을 계산합니다, 다양한 수식이 가능합니다.

- !계산 `계산식`

> !계산 1+2\*3/4 \
> !계산 2^10

## 알람

설정한 시간 후에 개인 메시지로 알려줍니다.

- !알람 `초:숫자` `메모:옵션`
- 시간은 초 단위의 숫자나 `!계산` 기능의 수식을 입력할 수 있습니다.
- 시간 뒤에 메모를 입력할 수 있습니다.
- 시간 0은 설정된 알람을 초기화합니다.
- 알람 중복 설정 시 기존 알람을 덮어씌웁니다.

> !알람 60 \
> !알람 300 오분 대기조 \
> !알람 60\*60\*2 두시간짜리 알람 \
> !알람 0

## 한영

한국어/영어/일어/중국어를 번역합니다.

- !한영 `문장`
- `!한영`, `!한일`, `!한중`, `!영한`, `!일한`, `!중한`

> !한영 바나나 \
> !한일 테스트 \
> !영한 test \
> !일한 もしもし

## 로마자

한글 이름을 로마자 표기로 보여줍니다.

- !로마자 `이름`
- 입력한 이름의 로마자 표기를 사용 빈도 순서대로 보여줍니다.

> !로마자 홍길동 \
> !로마자 김철수

## 시간

해당하는 국가의 현재 시간을 보여줍니다.

- !시간 `국가명`
- `!시간 국가`로 가능한 국가 목록을 확인하세요.

> !시간 국가 \
> !시간 미국 \
> !시간 영국
