# wall

> 현재 로그인된 사용자들의 터미널에 메시지를 작성합니다.
> 더 많은 정보: <https://manned.org/wall>.

- 메시지 보내기:

`wall {{메시지}}`

- 특정 그룹에 속한 사용자들에게 메시지 보내기:

`wall {{[-g|--group]}} {{그룹_이름}} {{메시지}}`

- 파일에서 메시지 보내기:

`wall {{파일}}`

- 타임아웃과 함께 메시지 보내기 (기본값 300초):

`wall {{[-t|--timeout]}} {{초}} {{파일}}`
