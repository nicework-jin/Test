### 프로그램 목적

프로그래머스 스터디를 위한 시간/공간 복잡도 파싱 및 통계화 하였음. (json 및 html 파일로 추출)

### 파이썬 버전 / 설치해야 하는 라이브러리

- Python 3.8
- Pandas

### 대상 파일

1. 프로그래머스 풀이 파일

1. 파일 형식: 문제명_이름.py 
- 딕셔너리 빼기_김무천.py
- 딕셔너리 빼기_김아무개.py
- 딕셔너리 빼기_이성진.py

1. 파일 내용: 프로그래머스 결과로 시간/공간 복잡도가 들어간 파일

"""

테스트 27 〉	통과 (0.01ms, 10.2MB)

테스트 28 〉	통과 (0.01ms, 10.2MB)

테스트 28 〉	통과 (0.01ms, 10.2MB)

"""

## parser.py (한 문제씩 파싱하기)

1. [parser.py]가 위치한 폴더로 이동한 후 [cmd]에 2번 또는 3번과 같이 입력합니다.

1. [현재 폴더]에 "딕셔너리 빼기" 문제가 있는 경우
- python parser.py "딕셔너리 빼기"

1. [~/AlgorithmStudy_211124/211130/] 경로의 폴더에 "딕셔너리 빼기"문제가 있는 경우
- python parser.py "딕셔너리 빼기" ~/AlgorithmStudy_211124/211130/

1. 출력 결과는 [parser.py]이 위치한 경로에 두 파일로 저장됩니다.
- "./result/문제명/문제명.html"
- "./result/문제명/문제명.json"

## multiple_parer.py (지정한 경로에 모든 문제 파싱하기)

1. [multiple_parser.py]와 [parser.py]가 위치한 폴더로 이동합니다.

1. cmd에 다음과 같이 입력합니다.
- python multiple_parser.py ~/AlgorithmStudy_211124/211130/

1. 출력 결과는 [multiple_parser.py]가 위치한 경로에 세 폴더로 나뉘어 저장됩니다.
- "./result/문제명01/문제명01.html", "./result/문제명02/문제명02.html" , ...
- "./result/문제명01/문제명01.json", "./result/문제명02/문제명02.json", ...
- "./result/md/연월일.md"
    - 여러 개의 html 파일을 하나로 묶은 마크다운 형식의 파일입니다.
