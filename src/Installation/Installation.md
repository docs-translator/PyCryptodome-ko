# 설치

원문 : [https://www.pycryptodome.org/src/installation](https://www.pycryptodome.org/src/installation)

설치 방법은 라이브러리를 포함할 패키지에 따라 다릅니다. PyCryptodome은 다음과 같이 설치할 수 있습니다:

### 1. 이전에 설치되어 있던 PyCryto 라이브러리를 즉시 교체하여 설치하는 방법은 다음과 같습니다.

'''
pip install pycryptodome
'''

이 경우 모든 모듈은 **Crypto** 패키지에 설치됩니다. 다음을 사용하여 올바르게 설치되었는지 테스트할 수 있습니다.

'''
pip install pycryptodome-test-vectors
python -m Crypto.SelfTest
'''

서로 간섭하기 때문에 PyCrypto와 PyCryptodome을 동시에 설치는 것은 피해야합니다. 따라서 이 옵션은 전체 애플리케이션이 **virtualenv**에 있다고 확신하는 경우에만 권장합니다.

[자몽티](https://github.com/jamongti)