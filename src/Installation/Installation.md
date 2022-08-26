# 설치 방법  
원문 : [https://www.pycryptodome.org/src/installation](https://www.pycryptodome.org/src/installation)  
설치 방법은 라이브러리를 설치할 패키지에 따라 다릅니다. PyCryptodome은 다음과 같이 설치할 수 있습니다:  
### 1. 이전에 설치되어 있던 PyCryto 라이브러리를 바꾸면서 설치하는 방법은 다음과 같습니다.  
<pre><code>
pip install pycryptodome
</code></pre>  
이 경우 모든 모듈은 Crypto 패키지에 설치됩니다. 다음을 사용하여 설치되었는지 테스트할 수 있습니다.  
<pre><code>
pip install pycryptodome-test-vectors
python -m Crypto.SelfTest
</code></pre>  
서로 간섭하기 때문에 PyCrypto와 PyCryptodome을 동시에 설치하면 안됩니다. 따라서 이 방법은 전체 어플리케이션이 독립적인 가상환경(virtualenv)에 있다고 확신하는 경우에만 권장합니다.  
### 2. 이전에 설치된 PyCrypto가 라이브러리와 나누어져 있을 때, 다음과 같이 설치할 수 있습니다.  
<pre><code>
pip install pycryptodomex
</code></pre>  
다음을 사용하여 설치되었는지 테스트할 수 있습니다.  
<pre><code>
pip install pycryptodome-test-vectors
python -m Cryptodome.SelfTest
</code></pre>  
이 경우, 모든 모듈은 Cryptodome 패키지에 설치됩니다. 이전에 설치되어 있던 PyCrypto와 PyCryptodome가 서로 간섭하지 않습니다.  

!주의  
Windows에서 Python 2.7과 함께 PyCryptodome을 실행하려면, 먼저 [Microsoft Visual C++ 2015 재배포 가능 패키지](https://www.microsoft.com/ko-kr/download/details.aspx?id=48145)를 설치해야 합니다. Python 3을 사용하는 경우에는 필요하지 않습니다.  

다양한 OS에서 C extension을 컴파일하기 위한 환경을 설정하는 방법과 GMP 라이브러리를 설치하는 방법은 아래에서 자세히 설명합니다.  

[자몽티](https://github.com/jamongti)  