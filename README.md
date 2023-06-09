# 소하고등학교 '정보' 부교재 

해당 소스는 CodeUp에서 제공되는 문제집 중

문제집 : Python 기초 100제
(정보컴퓨터 교사 연구회/카페에서 만든 Python 기초 100제 입니다. 초급자 코스로 추천합니다.)

에 대한 정답입니다. 
https://codeup.kr/problemsetsol.php?psid=33


<br>
<hr>
<h2>*주의*</h2>
<ol>
<li>98문제에 대한 풀이가 적혀져존재합니다. 99문제 중 1문제는 업다운 숫자 맞추기입니다.</li>
<li>해당 문제 풀이는 98문제 총 98분동안 스피드런으로 푼 문제들입니다. 어떤 코드는 에러가 발생할 수 있습니다.</li>
<li>위와 같은 이유로 필자 혼자 알아볼 수 있는 코드 그리고 한줄로 작성된 코드가 다수 존재합니다</li>
<li>평가시에 사용함으로써 생긴 불이익은 책임지지 않습니다.</li>
</ol>


<br>
<hr>
<h2>해설</h2>
저작권법에 의하여 문제에서 사용된 아이디어, 문제내용을 해설에 첨부할 수 없기에 <<a href="https://codeup.kr/problemsetsol.php?psid=33">코드업</a>>에 실려있는 문제를 직접 확인 후에 해설을 참고하시길 바랍니다. 해설 코드는 98문제 전부 <a href="https://github.com/acb0808/imformatics/blob/main/main.py">main.py</a>에 실려있습니다. 함수 하나당 문제 하나를 의미하며, 함수이름은 

```Python
def q50():
    print("return")
```
위 같이 q(문항번호)로 작명 되어 있습니다.
<br>
<br>
<br>

### 짤막코드해설

19번문제 - [::-1]은 리스트를 뒤집어 주는 역활입니다.
```py
print(' '.join(input().split()[::-1]))
```
34번문제 - map함수는 리스트의 원소 모두 함수의 반환값으로 치환해주는 함수입니다. 아래는 입력값을 띄어쓰기 단위로 나누고 각 값을 정수형태로 저장하는 기능을합니다
```py
list(map(int,input().split()))
```
54번문제 - lambda는 익명 함수로, 간단한 함수를 표현합니다. map함수와 같이 사용했습니다
```py
list(map(lambda x:bool(int(x)), input().split()))
```

<br>
<hr>
<h2>제보</h2>

깃허브 이슈탭을 이용하여 제보해주시거나, 본교 2학년8반 >**이석현**에게 제보해주세요 ^o^



---
## 개발환경
|이름|값|
|:---|:---:|
|파이썬버전|Python 3.7.4|
|아나콘다|X|
|pip사용|X|
