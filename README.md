# wairi_upgrader

1. 기존 버전 존재 (ex. 1.15.0)
2. 새 버전 심사 요청 (ex. 1.16.0)
3. 새 버전 심사 완료 및 스토어 업데이트
4. appcast.xml 버전 수정
5. 설치된 버전과 새 버전 넘버가 차이날 경우 upgrader 알림 (ex. 1.15.0 != 1.16.0)

- 강제 업데이트 적용시(x.xx 자리까지 수정될 경우)만 4번 수행
- 일반 업데이트 적용시 수정 하지 않음
- 설치된 버전 >= 새 버전 일 경우 upgrader 알림 뜨지 않음
