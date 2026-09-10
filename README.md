# BerryHunt

ZX베리자사 배포처입니다.

## 내려받기

최신본은 **[릴리스](https://github.com/elancibal/BerryHunt/releases/latest)** 에만 올립니다.

- 최신 파일 바로 받기: <https://github.com/elancibal/BerryHunt/releases/latest/download/BerryHunt_win7-11.exe>
- 프로그램 안에서 `설정 → 자동 업데이트 → 업데이트 확인` 을 눌러도 같은 파일을 받습니다.

## 올릴 때 지키는 것

- 저장소에는 exe 를 커밋하지 않습니다. 커밋하면 git 히스토리에 14MB 씩 영구히 쌓입니다.
- 릴리스 자산 이름은 `BerryHunt_win7-11.exe` **로 고정**합니다. 이름에 버전을 붙이면
  위의 `releases/latest/download` 고정 주소가 깨집니다.
- 버전은 태그(`v1.5.9`)에만 적습니다. 업데이터가 태그에서 버전을 읽어,
  지금 쓰는 것보다 예전 빌드면 받지 않습니다.
- 커밋 메일은 `elancibal@users.noreply.github.com` 만 씁니다.
