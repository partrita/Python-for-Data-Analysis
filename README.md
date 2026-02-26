# 파이썬 데이터 분석 (3판)

Wes McKinney의 "Python for Data Analysis, 3rd Edition" 실습 자료 및 IPython 노트북입니다. 업데이트 및 오타 수정 사항이 포함된 도서 내용은 [저자의 웹사이트][6]에서 무료로 확인할 수 있습니다.

[아마존에서 도서 구매하기][1]

Twitter 팔로우: [![Twitter Follow](https://img.shields.io/twitter/follow/wesmckinn.svg?style=social&label=Follow)](https://twitter.com/wesmckinn)

## 사용 환경 설정

### 옵션 1: uv 사용 (권장)

[uv](https://github.com/astral-sh/uv)는 매우 빠른 파이썬 패키지 설치 및 관리 도구입니다. 시작하려면 다음을 수행하세요:

1. uv가 설치되어 있지 않다면 설치합니다:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. 모든 의존성을 포함하여 Jupyter 노트북을 실행합니다:
```bash
uv run jupyter notebook
```

끝입니다! uv는 `pyproject.toml`을 바탕으로 가상 환경을 자동으로 생성하고 필요한 패키지를 모두 설치합니다.

### 옵션 2: Conda 사용

1. 새로운 conda 환경을 생성합니다:
```bash
conda create -n pydata-book python=3.11
conda activate pydata-book
```

2. 의존성을 설치합니다:
```bash
pip install -r requirements.txt
```

3. Jupyter 노트북을 실행합니다:
```bash
jupyter notebook
```

**참고:** 이 프로젝트는 노트북과의 호환성을 위해 pandas 2.0.3 버전을 사용합니다.

# 2판 독자들을 위한 안내

2017년에 출판된 2판을 읽고 계신다면, [`2nd-edition` 브랜치][5]에서 정리된 자료를 확인해 주세요.

# 1판 독자들을 위한 안내

2012년에 출판된 1판을 읽고 계신다면, [`1st-edition` 브랜치][2]에서 정리된 자료를 확인해 주세요.

## IPython 노트북

* [2장: 파이썬 언어 기본, IPython, Jupyter 노트북](mybook/ch02.ipynb)
* [3장: 내장 데이터 구조, 함수, 파일](mybook/ch03.ipynb)
* [4장: NumPy 기본: 배열과 벡터 연산](mybook/ch04.ipynb)
* [5장: pandas 시작하기](mybook/ch05.ipynb)
* [6장: 데이터 로딩, 저장, 파일 형식](mybook/ch06.ipynb)
* [7장: 데이터 정제 및 준비](mybook/ch07.ipynb)
* [8장: 데이터 준비: 조인, 병합, 변형](mybook/ch08.ipynb)
* [9장: 그래프와 시각화](mybook/ch09.ipynb)
* [10장: 데이터 집계와 그룹 연산](mybook/ch10.ipynb)
* [11장: 시계열](mybook/ch11.ipynb)
* [12장: 파이썬 모델링 라이브러리 소개](mybook/ch12.ipynb)
* [13장: 데이터 분석 예제](mybook/ch13.ipynb)
* [부록 A: 고급 NumPy](mybook/appa.ipynb)
* [부록 B: IPython 시스템에 대하여](mybook/appb.ipynb)

## 라이선스

### 코드

이 리포지토리에 포함된 코드와 노트북의 예제 코드는 [MIT 라이선스](LICENSE-CODE)를 따릅니다. 자세한 내용은 [Open Source Initiative](https://opensource.org/licenses/MIT)를 참조하세요.

[1]: https://amzn.to/3DyLaJc
[2]: https://github.com/wesm/pydata-book/tree/1st-edition
[5]: https://github.com/wesm/pydata-book/tree/2nd-edition
[6]: https://wesmckinney.com/book/