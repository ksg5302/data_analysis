git hub 기본 사용법

1. bash 터미널 연결 
    = ctrl + , (설정) -> terminal.integrated.Automationshell.windows 검색 후 json 세팅 -> "terminal.integrated.defaultProfile.windows": "Git Bash" 작성 -> ctrl + ` 터미널 열기
    = 하지만 그냥 터미널 열어서 클릭 2번으로 쌉가능

2. 터미널 명령어

    git init : git 에게 현재 경로 모든 파일 추적 명령
    git remote add origin https://github.com/ksg5302/Test_num_01.git : 현재 경로 디렉터리를 해당 주소 github Repositories 주소와 연결
    git config --global user.email "ksg5302@gmail.com" : 커밋 작성자 정보를 저장
    git config --global user.name "O.G" : 커밋 작성자 정보를 저장
    git add . : stage 상태로 올린다
    git commit -m "test2" : 커밋 메세지 작성
    git push origin main : 메인 브렌치에 푸시
    git pull : github Repositories 변경 사항 가져옴
    