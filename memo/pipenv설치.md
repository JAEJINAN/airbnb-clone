# 초기 설정 - pipenv 가상화

1. pipenv 설치

   ```
   pip install --user pipenv
   ```

2. pipenv python 설치 - (bubble 생성)

   가상환경을 만들고자 하는 디렉토리(폴더)로 가서 다음과같은 명령을 하면 `Pipfile`이 생성된다.

   3.7에 해당하는 파이썬이 설치되어 있어야 명령이 먹는다. (3.10을 깔고싶으면 일단 파이썬 3.10이 필요)

   ```
   pipenv --python 3.7
   ```

3. vscode 실행 (bubble 속으로)

   vscode로 해당 폴더를 열어 실행하자. vscode 터미널에서 다음을 실행하자. 가상환경으로 접속하게 해준다.

   ```
   pipenv shell
   ```

   ```
   PS C:\Users\Jay\Desktop\New_git\airbnb-clone-with-django> pipenv shell
   Launching subshell in virtual environment...
   Windows PowerShell
   Copyright (C) Microsoft Corporation. All rights reserved.  
   ```

   

4. Django 설치하기

   shell로 들어간후 Django를 설치해주자.

   ```
   pipenv install Django==2.2.5
   ```

   