# Git Test Project

이 프로젝트는 텍스트 파일 기반의 간단한 프로젝트입니다.

## 프로젝트 구조

```
git-test/
├── README.md
├── docs/
│   ├── notes.txt
│   └── ideas.txt
├── data/
│   ├── sample.txt
│   └── backup.txt
└── scripts/
    └── commands.txt
```

## 유용한 명령어들

### Git 명령어

```bash
# 프로젝트 초기화
git init

# 파일 추가
git add .

# 커밋
git commit -m "Initial commit"

# 상태 확인
git status

# 로그 보기
git log --oneline

# 브랜치 생성
git branch feature/new-feature

# 브랜치 전환
git checkout feature/new-feature

# 원격 저장소 추가
git remote add origin https://github.com/username/repository.git

# 푸시
git push -u origin main
```

### 파일 관리 명령어

```bash
# 파일 생성
touch filename.txt

# 디렉토리 생성
mkdir directory_name

# 파일 복사
cp source.txt destination.txt

# 파일 이동/이름 변경
mv old_name.txt new_name.txt

# 파일 삭제
rm filename.txt

# 디렉토리 삭제
rm -rf directory_name

# 파일 내용 보기
cat filename.txt

# 파일 내용 검색
grep "search_term" *.txt

# 파일 찾기
find . -name "*.txt"
```

### 텍스트 편집 명령어

```bash
# nano로 편집
nano filename.txt

# vim으로 편집
vim filename.txt

# 파일 내용 출력
cat filename.txt

# 파일 내용 페이지별로 보기
less filename.txt

# 파일의 처음 10줄 보기
head filename.txt

# 파일의 마지막 10줄 보기
tail filename.txt
```

## 사용법

1. 프로젝트 클론 또는 다운로드
2. 필요한 텍스트 파일들을 `docs/` 또는 `data/` 폴더에 추가
3. Git을 사용하여 버전 관리
4. 필요에 따라 `scripts/commands.txt`에 유용한 명령어 추가

## 라이선스

MIT License
