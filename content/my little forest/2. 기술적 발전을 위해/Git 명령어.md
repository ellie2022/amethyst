---
title:  {"title"}
date: "2023-02-21 14:34:44 "
tags: 
aliases:
---

### remote repository의 폴더 삭제 방법 
(ignore 부분이 한번 복사된 경우 리모트만 삭제하기):

##### 기초작업
1. git bash open

2. 터미널 내에서 git repo가 있는 folder로 이동, 

       $ cd f:/home/obsidian/repo_name)

3. 초기화 상태

       $ git init

4. 현재 상태 확인

       $ git config --list

5. 필요하면 사용자 설정 입력 

       $  git config --global user.name "username")
   
6. 연결상태 확인 : 
   
       $ git remote -v

##### 삭제작업

7.    먼저 리모트에 존재하는 디렉토리를 지운다.    

     $ git rm -r --cached  "first_directory_under_repo_root/second_director/dir_to_be_removed"  
   
   (여기서 첫번째 디렉토리란 repo 이름은 빼고 그 다음에 나오는 디렉토리를 의미. 
   예를들면..  
   내 Vault가 my_vault이고 일기/비밀일기 라는 폴더가 잘못 올라갔다면..  
   $ git rm -r --cached  "posts/my_vault/일기/비밀일기" 로 지운다는 뜻이다.  
   -r option은 recursive,  하위폴더의 내용도 모두 지운다는 뜻  
   --cached는 remote.  --cached가 없으면 local에서 삭제됨)  


8.     다음으로 커밋과 푸시로 적용한다

    $ git commit -am 'dir_to_be_removed removed from the repo'  
    $ git push 



### git submodule

Git 저장소 안에 다른 Git 저장소를 디렉토리로 분리해 넣는 것
템플릿 내에 존재하는 옵시디언 볼트를 별도로 관리하기 위해 필요한 개념이다.







### git checkout  
git branch 명령에 의해 생성 된 지점 사이를 이동하는 명령. 내가 사용할 브랜치를 지정하는 것.

#테크니컬팁