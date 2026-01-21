# 오늘의 서기: 곽수영
# {{TASK_NAME}}

## 오늘의 핵심
- 
- 
- 

## 회고 모음
- {{이름}}: 
- {{이름}}: 
- {{이름}}: 

## 자주 나온 질문
- 




실습 실행 순서

1. cohort12 가상화를 만든다.
   cmd에 conda activate cohort12

2. 포크따온 저장소의 최신 상태를 내 로컬에 다운로드를 한다.
   git fetch upstream
   git merge upstream/main 두 브랜치의 변경사항을 하나로 합친다

3. upstream의 main을 내 로컬 main으로 가져온다.
   git pull upstream main

4. 원격이 잘 잡혀있는지 확인한다.
   git remote -v

5. example.py를 복사해서 day2-llm_augmentations 폴더에 붙여넣고 파일명은 lsy.py로 한다.

6. cohort12 가상환경에 **전역(프로젝트 기준)**으로 설치
   pip install langchain_core langchain-anthropic langgraph

7. lsy.py를 실행한다.
   python lsy.py

