# research-ci-example

black command reformats code. For example, 
```
$ black main.py
```
reformats main.py

lint.yml: lint test을 통과해야 merge 되도록 설정

coverage.yml: coverage test을 통과해야 merge 되도록 설정
example code 
```
coverage run --source=./ -m unittest discover -p "*_test.py"
```