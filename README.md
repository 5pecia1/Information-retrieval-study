정보검색 공부를 위한 저장소 입니다.

## Running

1. 현재 실행시킬 html, python 파일이 있는 폴더로 이동합니다.

2. 다음  명령어를 실행시킵니다.

  **winodws**
  ```bash
  $ docker run -dit --name my-ir-app -p 8080:80 -v "%cd%":/usr/local/apache2/htdocs/ 5pecia1/ir:1.0
  ```
  
  **others**
  ```bash
  $ docker run -dit --name my-ir-app -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ 5pecia1/ir:1.0
  ```

3. `localhost:8080`으로 접속합니다.
