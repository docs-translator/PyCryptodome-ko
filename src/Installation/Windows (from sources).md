#Windows(소스 코드에서 컴파일하는 방법)  

원문 : [https://www.pycryptodome.org/src/installation#windows-from-sources](https://www.pycryptodome.org/src/installation#windows-from-sources)  

!주의  
Crypto 패키지에 설치하려면, pycryptodomex를 pycryptodome으로 바꾸십시오.  

Windows는 대부분의 Unix 시스템과 같은 C 컴파일러와 함께 제공되지 않습니다. 소스 코드에서 PyCryptodome extensions을 컴파일하는 가장 간단한 방법은 Microsoft에서 무료로 제공하는 Visual Studio를 최소한으로 설치하는 것입니다.  

1. 처음에만 Visual Studio 2019용 빌드 도구를 다운로드합니다. 그리고, 설치 프로그램에서 C++ 빌드 도구와 Windows 10 SDK 및 최신 버전의 MSVC v142 x64/x86 빌드 도구를 선택합니다.  

2. PyCryptodome를 설치하고, 컴파일하기:  
<pre><code>
> pip install pycryptodomex --no-binary :all:
</code></pre>  

3. 모든 것이 정상작동하는지 확인하기위해, test하세요.  
<pre><code>
> pip install pycryptodome-test-vectors
> python -m Cryptodome.SelfTest
</code></pre>  

[자몽티](https://github.com/jamongti)  
