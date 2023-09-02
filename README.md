# OpenCV_study

## 소개
- OpenCV란?
  - Open Source Computer Vision의 약자로, 영상 처리에 사용할 수 있는 오픈 소스 라이브러리
  - 크로스 플랫폼을 지원하고, 실시간 이미지 프로세싱에 중점을 둔 라이브러리
  - 물체 인식, 안면 인식, 모바일 로보틱스, 제스처 인식 등에 사용되고 있음.
  - C/C++ 언어로 개발되었으며 파이썬, 자바, 매트랩에 바인딩 되어 개발 환경을 지원한다.
- 위의 코드는 OpenCV를 공부하면서 작성되었습니다.
- 주로 jupyter notebook, python 환경에서 작성되었습니다.
- 의존성 충돌을 예방하기 위해 파이썬 내장 모듈인 venv(가상환경)에서 작성하였습니다.

### [환경]
|SW|VERSION|
|:-:|:-:|
|Ubuntu|20.04 LTS|

## 실행
### 가상환경 구축
```bash
mkdir ~/opencv_study  # 워크스페이스 폴더 생성
cd opencv_study  # 워크스페이스 폴더로 이동
python3 -m venv .venv  # 가상환경 설정
source .venv/bin/activate  # 가상환경 활성화
```
### 설치 파일
```bash
sudo apt install jupyter jupyter-core
pip install jupyter pandas matplotlib numpy scikit-learn
# 설치 완료 후 재부팅
```
```bash
pip install opencv-python
code .  # vscode 실행
```
- 주의 : vscode에서 Jupyter notebook으로 작성할 경우 select kernel을 확인할 것!

## 실행 결과
- 올라간 코드 안에서 확인할 수 있음.
  
