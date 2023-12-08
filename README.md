# mac_setting

1. 로제타 2 설치
- sudo softwareupdate --install-rosetta --agree-to-license

2. Update your path
- export PATH="$PATH:[PATH_OF_FLUTTER_GIT_DIRECTORY]/bin"

3. Flutter 경로지정
- export PATH="$PATH:$HOME/flutter/bin"

4. Command Line Tools 설치
- xcode-select --install

5. Homebrew 설치
- /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

6. rbenv 설치
- brew install rbenv

7. rbenv 관련 설정을 ~/.zshrc에 추가
- 첫 번째 명령어
- export PATH="$HOME/.rbenv/bin:$PATH"

- 두 번째 명령어
- eval "$(rbenv init - zsh)"

8.루비 버전 검색
- rbenv install -l

9. 루비 설치 명령어
- rbenv install 3.2.2

10. nano 에디터 실행
- nano ~/.zshrc

11. nano 에디터 환경변수 설명 명령어
- eval "$(rbenv init -)"

12. .zshrc 파일 새로고침
- source ~/.zshrc

13. CocoaPods 설치
- sudo gem install cocoapods

14. ActiveSupport를 삭제
- sudo gem uninstall activesupport

15. 낮은 버전의 ActiveSupport를 설치
- sudo gem install activesupport -v 7.0.8
