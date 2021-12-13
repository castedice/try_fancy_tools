# Fancy Stuff!

Fancy한 도구들을 소개

파워풀한 기능을 최우선으로 하며 너무 마이너한 것은 제외

## Language Version Manager

### [asdf](https://github.com/asdf-vm/asdf)

python 외의 언어도 함께 관리할 수 있다는 점에서 선택

## Dependency Manager

### [poetry](https://github.com/python-poetry/poetry)

[PEP 518](https://www.python.org/dev/peps/pep-0518/)를 따르며, 편리하게 의존성 관리가 가능

## Linter & Formatter

### [wemake](https://github.com/wemake-services/wemake-python-styleguide)

style issues, bugs, complex code 등을 찾아주는 만능 linter

### [black](https://github.com/psf/black)

wemake에서 제공하지 않는 code formatting 기능을 제공

### [blackcellmagic](https://github.com/csurfer/blackcellmagic)

notebook에서도 black으로 가독성을 높이자

## Formatting terminal

### [rich](https://github.com/willmcgugan/rich)

가독성은 생산성을 증진시킨다!!

프린트할 수 있는 거의 모든 것에 적용이 가능함

(log 관리, progress bar, 가독성 높은 변수 등)

## Logging

### [logging](https://docs.python.org/3/library/logging.html)

built-in module의 효과는 굉장했다!

## Visualization

### [plotly](https://github.com/plotly/plotly.py)

interactive한 graph를 얻을 수 있음

jupyter-dash나 dash를 기반으로 웹 앱도 개발 가능

Flask와 연동하는 방법도 있음

## Massive Tabular Data

### [modin](https://github.com/modin-project/modin)

[pandas](https://github.com/pandas-dev/pandas)를 dask나 ray를 이용하여 빠르게 사용할 수 있도록 도와주는 라이브러리

## Parallel Computing

### [ray](https://github.com/ray-project/ray)

사용이 ***비교적*** 간편하며 퍼포먼스까지 좋은 라이브러리

## Cluster Computing

### [dask](https://github.com/dask/dask)

Scale up이 필요할 때 고려할 첫 번째 도구

## Web framework

### [fastAPI](https://github.com/tiangolo/fastapi)

높은 퍼포먼스와 생산성을 갖는 web framework

## High Performance

### [cython](https://github.com/cython/cython)

약간은 다른 문법을 가지고 있지만, 성능 향상을 기대할 수 있으며

C compile 과정에서 코드 유출을 방지할 수 있음

### [numba](https://github.com/numba/numba)

수치 계산에 초점을 맞춘 JIT 컴파일러, 사용도 간편함

### [pypy](https://www.pypy.org)

cpython기반으로 짜여진 라이브러리(numpy 등)과 호환이 되지 않는 문제가 있음

## GUI

### [dearpygui](https://github.com/hoffstadt/DearPyGui)

python으로 gui를 만드는 건 해서는 안될 행위지만 필요하다면

## 추 후 추가할 키워드

### Asynchronous Processing

asyncio, uvloop 등등 [참고](https://pythonrepo.com/repo/timofurrer-awesome-asyncio-python-concurrent-and-parallel-execution)
