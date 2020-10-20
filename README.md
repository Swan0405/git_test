# git_test
# git 사용방법 정리

* 초기 세팅 사용법
1. github Web에서 프로젝트를 생성한다.그 후 프로젝트 주소를 복사해 둔다.
2. mkdir xxx : xxx 디렉토리를 만든다.
   - cd xxx : xxx 디렉토리로 이동한다.
   - git init: 현재 xxx 디렉토리를 git 저장소로 지정한다.
   - git remote add origin [프로젝트 주소]
3. 해당 디렉토리에서 abc 파일을 만든다.
4. git add abc 
5. git commit -m "new file"
6. git push origin master
   - git ID/PW 를 입력하면
7. github 해당 프로젝트에 작성한 abc 파일이 업로드 된다.

* Branch 사용법
- git branch : 브랜치 목록 확인
- git branch xxx : xxx이라는 브랜치 생성
- git checkout xxx : xxx이라는 브랜치 활성화
- git branch -b xxx : xxx이라는 브랜치 생성 및 활성화
- 해당 디렉토리에 abc 라는 파일 생성 후,
- git add abc
- git commit -m "설명"
- git push origin xxx : xxx 이라는 브랜치 이름으로 파일 업로드

* 브랜치 병합
- git checkout master : master 활성화
- git merge xxx : xxx 이라는 브랜치 병합
- git push origin master : xxx의 파일이 master로 파일이 병합됨


* 키워드 정리
- 원하는 디렉토리에서 git clone [해당 프로젝트 주소] : 해당 프로젝트를 원하는 디렉토리에 복사한다.


https://tagilog.tistory.com/377
https://imasoftwareengineer.tistory.com/9?category=769323
https://velog.io/@eodyd6564/git-%EC%82%AC%EC%9A%A9%EB%B2%95
