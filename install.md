# 1. 시스템 요구 사항 확인
## 요구 사항

- 64비트 CPU: AMD 또는 인텔 CPU를 사용한 64비트 환경
- 운영체제: Ubuntu, CentOS와 같은 리눅스 기반 운영체제 또는 macOS 환경
- CMake 3.22 이상: CMake는 빌드 시스템을 설정하는 도구
- Clang 18 또는 GCC: C++ 컴파일러로 Clang이나 GCC가 필요
- Python 3.9 이상: BitNet CPP는 Python 인터페이스를 지원
- Git: 소스 코드를 다운로드하기 위해 필요

# 2. 필수 소프트웨어 설치
## 2.1 CMake 설치
```bash
sudo apt update
sudo apt install -y cmake
```

## 2.2 Clang 설치
Clang을 설치하기 위해 다음 명령어를 입력합니다.
```bash
sudo apt install -y clang
```

## 2.3 Python 설치
Python 3.9 이상 버전이 필요합니다. 만약 Python이 설치되어 있지 않다면, 다음과 같이 설치합니다.
```bash
sudo apt install -y python3 python3-pip
```

설치된 Python 버전을 확인하려면 다음 명령어를 입력하세요.
```bash
python3 --version
```

## 2.4 Git 설치
BitNet CPP의 소스 코드를 클론하기 위해 Git을 설치합니다.
```bash
sudo apt install -y git
```
