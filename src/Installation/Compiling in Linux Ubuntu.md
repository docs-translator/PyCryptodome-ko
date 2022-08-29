# Linux Ubuntu에서 컴파일하는 방법  

원문 : [https://www.pycryptodome.org/src/installation#compiling-in-linux-ubuntu](https://www.pycryptodome.org/src/installation#compiling-in-linux-ubuntu)

!주의  
Crypto 패키지에 설치하려면, pycryptodomex를 pycryptodome으로 바꾸십시오.  

### Python 2.x버전인 경우:  

<pre><code>
$ sudo apt-get install build-essential python-dev  
$ pip install pycryptodomex  
$ pip install pycryptodome-test-vectors  
$ python -m Cryptodome.SelfTest  
</code></pre>  

### Python 3.x버전인 경우:  

<pre><code>
$ sudo apt-get install build-essential python3-dev  
$ pip install pycryptodomex  
$ pip install pycryptodome-test-vectors  
$ python3 -m Cryptodome.SelfTest  
</code></pre>  

### PyPy인 경우:  

<pre><code>  
$ sudo apt-get install build-essential pypy-dev  
$ pip install pycryptodomex  
$ pip install pycryptodome-test-vectors  
$ pypy -m Cryptodome.SelfTest  
</code></pre>  

[자몽티](https://github.com/jamongti)  
