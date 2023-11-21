git&gitHub 순서

* 초기 디렉터리 생성 시 순서

1. git init 저장소 등록
2. git branch -M main<br>
    master -> main으로 변경
3. git remote add origin HTTPS주소 붙여넣기<br>
    origin == gitHub HTTPS 주소별칭

-----------------------------------------------
* 초기 디렉터리 생성 후 작업 진행 시 순서

1. git add .<br>
    .이란? == 현재 디렉터리 안 모든 파일과 폴더를 뜻함.
2. git commit -m 'message'<br>
    현재 스테이징된 파일의 기록명을 작성(영어, 한글 모두 가능하나 영어 추천, 짧게 키워드 위주로 작성하기)<br>
    ex) 쇼핑몰 상품 페이지를 만들었다면?<br>
    git commit -m 'shp man-product end'
3. git push origin main<br>
    drigin == gitHub 주소<br>
    main == Local 내 컴퓨터 위치<br>
    해석 == gitHub에 내 작업물을 push 하겠다.
-------------------------------------------

* 위 add -> commit -> push 순서 중간중간 작업 확인 리눅스 명령어

1. git status<br>
    Local과 Staging 상태에서 작업물의 등록 상태 체크
2. git log<br>
    Commit과 Push 상태에서 작업물의 Commit 기록과 업로드 정보 체크

    -------------------------

# H1~H6 Tag(block)
* 제목 태그는 검색 키워드 역할을 하며 페이지 내에서 대/중/소 제목 역할을 한다.
* H1이 가장 중요한 제목이며 H1, H2, H3 위주로 많이 사용한다.
