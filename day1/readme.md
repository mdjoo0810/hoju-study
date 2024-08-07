# Day1

## 아나콘다 설정하기

### 1. 환경 확인하기
어떤 환경이 구성되어있는지 확인

```sh
conda env list
```

### 2. 환경 생성하기

```sh
# conda create -n 환경이름
# 아래는 예시
conda create -n day1
```

### 3. 가상환경 활성화하기

```sh
# conda activate 환경이름
# 아래는 예시
conda activate day1
```

### 4. 가상환경에 파이썬 패키지 설치하기

```sh
# conda activate 환경이름
# 아래는 예시
conda install python=3.8
```

## 간단한 파이선 프로그래밍

### 1. 변수 설정하기

```py
# 변수명 = "문자열"
# 변수명 = 1234 // 이거는 숫자

stringVar = "문자열"
number = 1234

```

### 2. 콘솔에 출력하기

파이썬 파일에서 print() 사용하기
```py
# 변수명 = "문자열"
# 변수명 = 1234 // 이거는 숫자

stringVar = "문자열"
number = 1234

print(stringVar)
print(number)

```

터미널에서 파이썬 파일을 실행합니다.

```sh
# python 파일명
python day1.py
```

출력 결과를 확인합니다
