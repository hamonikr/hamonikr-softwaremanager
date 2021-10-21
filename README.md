# Hamonikr-softwaremanger

![license](https://img.shields.io/badge/GPL-License3.0-green.svg)



- Hamonikr-softwaremanger 는 mintinstall 패키지를 하모니카 환경에 맞게 변경한 프로그램입니다.
- [하모니카 커뮤니티](https://hamonikr.org/board_softwaremngr) 내에 패키지 정보 업데이트시에 소프트웨어 매니저에 반영됩니다.
  - 커뮤니티에 패키지 정보가 등록되어있으면 해당 내용이 출력되고 없을 경우 패키지 내에 있는 description 내용이 출력됩니다
  - 커뮤니티 소프트웨어 매니저 게시판에 패키지 정보를 올릴 경우 제목은 패키지명과 동일한 소문자로 입력해주세요.
  - 이미지는 최대 4장까지 가능합니다.
- 빌드하기

```
dpkg-buildpackage -T clean
dpkg-buildpackage -b -us -uc -ui 
```

