## 린스랑 샴프랑 프로젝트
### 2021.05.22 
* 네이버AI 자료 첨부

1. 강현영 씨 : 와이어프레임 만들기 
2. 구동현 씨 : DB만들기, GITHUB 확인
3. 이재우 씨 : 오픈 API 확인
4. 이선욱 씨 : 유해성분 리스트 조사, 스프링 코딩

### 2021.05.25

1. 오픈API확인
2. EWG 등급 확인

## + Branch 사용법

    1. 원하는 작업github 코드를 복사합니다.

    2. git bash를 실행합니다.

    3. 작업을 원하는 폴더로 들어갑니다.(`cd`)

    4. `git clone 작업 github 코드` 를 입력합니다.

    5. 복사한 파일로 들어갑니다. (`cd 파일명`)

    6. `git status`를 입력해 현재 git의 상태를 확인합니다.(`main`상태로 branch 존재)

    7. 자신의 branch 를 만듭니다.(`git branch koo`)

    8. `git branch` 를 입력해서 branch가 만들어졌는지 확인합니다.

    9. `git checkout koo`를 입력해서 자신의 branch로 변경합니다.

    10. code . 창을 열어서 수정하거나, 자신이 수정한 부분을 붙혀넣습니다.

    11. `git status`를 입력하여, 자신이 수정한 부분이 어떤 파일인지 확인합니다.

    12. 자신이 수정한 파일을 git에 add 작업합니다. (`git add README.md`)

    13. 커밋을 메세지와함께 추가합니다.(`git commit -m "Add Contents"`)

    14. `git log --oneline`을 통해서 내가 수행한 작업이 기록되었는지 확인합니다.

    15. `git push orugin koo`를 입력하여, Push 작업을 한 뒤, `exit`로 git bash실행을 마칩니다.

* git bash 수행사진1

![git bash 수행사진_1](https://postfiles.pstatic.net/MjAyMTA1MjVfMTc3/MDAxNjIxODk2MTQ4MzQ5.Zclw1NDXvfYmbZoYVRAHJAj5JOJuvn8u4uJUqfweo1Ag.umeWcfJna7IYjs9ci04cURzT_k-I2garz2XnRt5V7ccg.JPEG.paul5000/gitbash_1.JPG?type=w773)

* 수행사진2

![수행사진_2](https://postfiles.pstatic.net/MjAyMTA1MjVfOTIg/MDAxNjIxODk2MTUwNzE0.ALxj41a-E8iWN4XBzZbAY6eAAxiNqTH38vdvr9fXMg4g.L-l8HgAbKSdNE1J8CKmobjmIXVRorLiUGiPQeG0jxNMg.JPEG.paul5000/gitbash_2.JPG?type=w773)

## branch 업로드

    1. 관리자는 추가된 브랜치를 확인합니다.

    2. `pull request`를 확인하고, 체킹하여 merge 작업을 진행하여, 변경된 파일을 확인합니다.


1. 브랜치 확인

![추가된 브랜치](https://postfiles.pstatic.net/MjAyMTA1MjVfMjE0/MDAxNjIxODk2MTUzNzM2.4ztOsygmdz3iBmpVrEHmFOTDpxULtR4mm1CnjEN9kkMg.fOP2bMs4gg2qmySNImNLYjpeGqQ2iWaNAj6uwNm2MYEg.JPEG.paul5000/3.JPG?type=w773)

2. 변경사항 적용 및 확인

![1](https://postfiles.pstatic.net/MjAyMTA1MjVfMjMx/MDAxNjIxODk2MTU2MzUz.I97ZfISyiQ44Fz5oaXYBr5dS_jwRtV8CWl9JTXmhNrog.ZZ3eI5HVJi2WmpKbokED-SW5S1rG9w510obzwmbYLqUg.JPEG.paul5000/4.JPG?type=w773)

![2](https://postfiles.pstatic.net/MjAyMTA1MjVfOTgg/MDAxNjIxODk2MTU4MzI0.4G24BCLMXywkSbzq4XFutxnZLTFUbS-6b_Clc1TgDzEg.RGC1STZLTkxo-37wKoYvPEuHHPFU-VmCPWDtrHbifzQg.JPEG.paul5000/5.JPG?type=w773)