# 🚀 Git Bash 명령어

## ⚙️ Git 설정 목록
```bash

# 📂 현재 작업 디렉터리 확인
pwd

# 📁 현재 디렉터리의 모든 파일 및 폴더 상세 정보 표시
ls -al

# 🚀 Git 버전 확인
git --version

# ⚙️ Git 설정 목록
git config --list

# ❓ Git 도움말
git --help

# Git 버전 확인
git --version

# 🔄 줄바꿈 자동 변환
git config --global core.autocrlf true

# 🔒 줄바꿈 안전 설정
git config --global core.safecrlf false

# ⚙️ Git 설정 목록
git config --list

# 🖊️ 기본 편집기 설정
git config --global core.editor 'code --wait'

# 👤 사용자 정보 설정
git config --global user.name "Your Alias"
git config --global user.email "your.email@example.com"

# 📘 파일 내용 출력
cat <파일 이름>

# 🔄 Git 변경사항 확인
git diff

# 💾 Git 변경사항 스테이징 및 커밋
git add .
git commit -m "커밋 메시지"

# 📝 화면에 메시지 출력
echo "메시지 내용"

# 📁 파일 삭제
git rm <파일 이름>            # 작업 폴더와 스테이징 영역에서 파일(f) 삭제
git rm --cached <파일 이름>   # 스테이징 영역에서만 파일(f) 삭제

# 🚀 Git Bash 명령어

# 📁 파일 복구
git restore <파일 이름>                           # 작업 폴더에서 파일(f) 복구
git restore --staged <파일 이름>                  # 스테이징 영역에서 파일(f) 복구
git restore --source=HEAD --worktree <파일 이름>  # 깃 저장소의 HEAD에서 작업 폴더에 파일(f) 복구
git restore --source=HEAD --staged --worktree <파일 이름>  # 깃 저장소의 HEAD에서 스테이징 영역과 작업 폴더에 파일(f) 복구

# 🌟 깃허브 기본 명령어 모음집 🚀
