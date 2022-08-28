# Linux Fedora에서 컴파일하는 방법  

원문 : [https://www.pycryptodome.org/src/installation#compiling-in-linux-fedora](https://www.pycryptodome.org/src/installation#compiling-in-linux-fedora)

!주의
Crypto 패키지에 설치하려면, pycryptodomex를 pycryptodome으로 바꾸십시오.  

### Python 2.x버전인 경우:  

<pre><code>
$ sudo yum install gcc gmp python-devel
$ pip install pycryptodomex
$ pip install pycryptodome-test-vectors
$ python -m Cryptodome.SelfTest
</code></pre>  

### Python 3.x버전인 경우:  

<pre><code>
$ sudo yum install gcc gmp python3-devel
$ pip install pycryptodomex
$ pip install pycryptodome-test-vectors
$ python3 -m Cryptodome.SelfTest
</code></pre>  

### PyPy인 경우:  

<pre><code>  
$ sudo yum install gcc gmp python3-devel
$ pip install pycryptodomex
$ pip install pycryptodome-test-vectors
$ python3 -m Cryptodome.SelfTest
</code></pre>  

[자몽티](https://github.com/jamongti)  