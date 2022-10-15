# Flutter Basic
## 🛼 Why Flutter?
- 크로스 플랫폼 앱(Cross Platform App): 하나의 프로그래밍 언어와 소스코드로 Android와 iOS를 모두 개발<br/>
- 구글에서 출시한 오픈 소스 모바일 애플리케이션 프레임 워크
- 높은 생산성과 React-native보다 뛰어난 성능
- [Flutter 공식 문서](https://docs.flutter.dev/)
<br/>

## 📋 How To Start (for MAC)
### 설치 필요 프로그램 
- Flutter : Android와 iOS 앱을 하나의 코드로 구현할 수 있도록 도와주는 프레임워크<br/>
- VSCode : 코드를 작성할 때 사용하는 에디터<br/>
- Android Studio : Android 앱을 개발하기 위해 필요한 IDE. 에뮬레이터 포함<br/>
- Xcode : iOS 앱을 개발하기 위해 필요한 IDE. 에뮬레이터 포함<br/>
<br/>

1. Flutter 설치
```
$ echo 'export PATH="$PATH:$HOME/development/flutter/bin"' >> ~/.zshrc && source ~/.zshrc
$ flutter --version
$ flutter doctor
```

2. VSCode Extension 설치<br/>
- Extension 탭에서 Flutter (Dart) 설치
<br/>

3. Android Studio License 설정
```
$ flutter doctor --android-licenses
```

4. Xcode License 설정
```
$ sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
$ sudo xcodebuild -runFirstLaunch
```

### 새 프로젝트 생성
- View → Command Palette (Cmd + Shift + P)
- Flutter: New Project → Application
