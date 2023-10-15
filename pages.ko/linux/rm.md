# rm

> 파일 또는 디렉터리 삭제.
> 같이 보기: `rmdir`.
> 더 많은 정보: <https://www.gnu.org/software/coreutils/rm>.

- 특정 파일 삭제:

`rm {{경로/대상/파일1 경로/대상/파일2 ...}}`

- 존재하지 않는 파일은 무시하고 특정 파일 삭제:

`rm --force {{경로/대상/파일1 경로/대상/파일2 ...}}`

- 특정 파일을 삭제하기 전에 대화형 메시지를 표시하여 특정 파일을 삭제:

`rm --interactive {{경로/대상/파일1 경로/대상/파일2 ...}}`

- 특정 파일을 삭제하고 삭제한 파일 정보를 출력:

`rm --verbose {{경로/대상/파일1 경로/대상/파일2 ...}}`

- 특정 파일 및 디렉터리를 재귀적으로 삭제:

`rm --recursive {{경로/대상/파일_또는_폴더1 경로/대상/파일_또는_폴더2 ...}}`