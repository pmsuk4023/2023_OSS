#!/user/bin/env bash

echo "---------"
echo "name :"

echo

echo "---------"
echo "student id :"

file_path='find /home/kau2/ -name w2_homework.txt 2>dev/null'
echo "---------"
echo
echo "file path :"
echo $file_path
echo

2023_OSS
=============

2023 OSS 수업 
-------------

#3주차 git

##이미지

<img src="https://github.com/nparkcourage/2023-kau-0504/blob/main/w3/2023_OSS/img/kau/kau.png?raw=true">

##ProGit 링크

[ProGit] (https://git-scm.com/book/ko/v2)

##주요 git 명령어

* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
	* 예) git add
* commit
* git reset HEAD : stage된 파일을 unstaged로 변경
* git checkout -- : stage되어 있는 파일을 수정한 후 수정 전으로 되돌림
* branch
* merge
* status
* log
	* 예) git log --oneline --decorate --graph --all

