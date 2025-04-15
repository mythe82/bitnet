# 1. 시스템 요구 사항 확인
## 요구 사항
- 64비트 CPU: AMD 또는 인텔 CPU를 사용한 64비트 환경
- 운영체제: Ubuntu, CentOS와 같은 리눅스 기반 운영체제 또는 macOS 환경
- Clang 18 또는 GCC: C++ 컴파일러로 Clang이나 GCC가 필요
- Python 3.9 이상: BitNet CPP는 Python 인터페이스를 지원
- Git: 소스 코드를 다운로드하기 위해 필요

# 2. 필수 소프트웨어 설치
## 2.1 Python 설치
Python 3.9 이상 버전이 필요합니다. 만약 Python이 설치되어 있지 않다면, 다음과 같이 설치합니다.
```bash
sudo apt install -y python3 python3-pip
```
설치된 Python 버전을 확인하려면 다음 명령어를 입력하세요.
```bash
python3 --version
```

## 2.2 conda 설치
```bash
curl --output anaconda.sh https://repo.anaconda.com/archive/Anaconda3-2022.10-Linux-x86_64.sh
bash anaconda.sh
[enter]
[yes]
[enter]
[yes]
```

## 2.3 conda 명령어 환경변수 추가
```bash
sudo vi ~/.bashrc
export PATH=~/anaconda3/bin:~/anaconda3/condabin:$PATH

source ~/.bashrc
conda -V
```

# 3. Automatic installation script
```bash
sudo bash -c "$(wget -O - https://apt.llvm.org/llvm.sh)"
```

# 4. Build from source
## 4.1 Clone the repo
```bash
git clone --recursive https://github.com/microsoft/BitNet.git
cd BitNet
```

## 4.2 Install the dependencies
```bash
conda create -n bitnet-cpp python=3.9
conda activate bitnet-cpp
[y]
pip install -r requirements.txt
```




