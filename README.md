# **오픈소스SW개발론**
# 오픈소스소프트웨어

## Week1-1 강의개요 (강의계획서)
* 강의 계획서
    * [강의 계획 영상](https://sel.jnu.ac.kr/mod/vod/view.php?id=837532)
## Week1-2 오픈소스소프트웨어 개요
1. **What is Open Source Software?**
    * 소프트웨어 저작권 소유자가 모든 사람에게 소스 코드를 게시, 사용, 복사, 수정 및 배포할 권리를 부여한 소프트웨어
    * 일괄 사전 이용허락, 로열티 없음, 기간/목적 제한 없음
2. **OSS License**
    * 오픈소스 소프트웨어의 사용, 복제, 수정, 배포 권한의 범위를 지정
    * ex) GPL, LGPL, MIT License, BSD License,  APACHE License, MPL

    [참고자료1] : [오픈소스소프트웨어 개요와 라이센스](https://docs.google.com/presentation/d/1HJM_NecZ2YZMin9NEL7-_PbZnj44ahYD/edit#slide=id.p1)

    [참고자료2] : [오픈소스소프트웨어 개요](https://drive.google.com/file/d/1IRvsG418jiyQqhjOXMc-maEaL17ypBuw/view)

## Week2-1 버전 관리 개요
1. **Version Control System(VCS)**
* What is VCS?
        
    Track your files over time so that _you can easily get back to a previous working version_
* VCS Software
    
    CVS, SVN, Mercurial, Darcs, Git
*  Action
        
    - Checkin : 파일을 체크인하고 여러번 수정

    - Checkout and editing : 파일 체크아웃, 편집, 체크인

    - Diffs : 두 파일 비교 (줄기에 이전 파일 변화 기록 잔여)
        
    - Branching : 독립적인 작업 영역(저장소) 안에서 마음대로 소스코드를 변경 가능하게 함 

    - Merging : 서로 다른 브랜치를 병합

    - Conflicts : 변화 오버랩

2. **_Centralized VCS_ VS  _Decentralized(Distributed) VCS_**
* Centralized VCS
    - One central repository with many users
    - E.g. CVS, SVN, Darcs
* Decentralized(Distributed) VCS 
    - Every user owns his or her local repository
    - A separate remote (central) repository
    - E.g. GIT, Mercural


## Week2-2 Git
    ![GIT](https://ibb.co/PWL27VB)

## Week2-3 Github, fork, pull request
* Github [바로가기](https://github.com/)
* Gighub에 fork, pull request 하기 [강의 보기](https://www.youtube.com/watch?v=oRazSAenlfs&list=TLGGF3Ca4HLrfx0yNDA5MjAyMg)

## Week3 Markdown
John Gruber and Aaron Swartz (2004) 개발
> "A lightweight markup language for creating formatted text using a plain-text editor"
* Heading and Seperator lines
    - Heading : "#" 을 사용, "#"의 개수에 따라 크기 조절
    - Seperator lines : "===", "---" 을 통해 경계선 생성
* Italic, Bold, etc
    - Italic : "_" 를 원하는 문장, 단어 양 끝에 붙이기
    - Bold : "**" 를 원하는 문장, 단어 양 끝에 붙이기
* List
    - "숫자.", "*", "-" 등을 이용해 리스트 생성
* Link, Images
    - Link : " [클릭시 링크 연결](링크 주소) "
    - Images : " ![대체 텍스트](이미지 주소) "

[참조]

[위키피디아](https://en.wikipedia.org/wiki/Markdown)

[마크다운 튜토리얼](https://www.markdowntutorial.com)
