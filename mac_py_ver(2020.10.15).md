# 맥에서 파이썬 버전 바꾸기

문제점 : 파이썬 3.x 버전을 받아서 설치하고 터미널에서 python --version을 쳐보면 2.x 파이썬이 사용된다. 이 것을 3.x 버전으로 바꾸는 방법이다.

<pre>
sudo vim .bash_profile
여기에서 shift + g를 눌러 내려간다음 o를 눌러 텍스트를 아래의 코드를 적는다.

alias python='python3'
그 후 esc, :wq를 치고 나온다.

source .bash_profile
위 코드로 적용시킨다.

python --version
마지막으로 버전 확인을 한다.
</pre>
