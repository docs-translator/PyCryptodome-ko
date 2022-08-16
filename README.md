# PyCryptodome-ko

---

본 저장소는 [PyCryptodome](https://www.pycryptodome.org/)의 공식 문서를 한국어로 번역하여, pycryptodome에 더 쉽게 접근할 수 있도록 도와주는 것이 목적입니다.

따라서 번역을 하실 때에는 영어 본래의 뜻을 그대로 옮기는 것이 아니라, 본래의 뜻을 해치지 않는 선 안에서 사람이 더 쉽게 이해할 수 있는 방향으로 번역을 해주시면 감사하겠습니다.

만약, 번역한 글을 PyCryptodome을 처음 접해보는 사람이 읽었을 때에 이해하기 힘들다고 생각하는 부분이 있다면, 추가적으로 자유롭게 설명을 달아주셔도 됩니다.

번역하기 전에는 아래의 항목을 확인해주세요.

1. 본 글을 확인하여, 자신이 번역하려고 하는 문서를 이미 다른 사람이 번역하고 있지는 않은지 확인해주세요.
2. 만약 없다면, 번역 전에 꼭 이슈를 등록해주세요. 추후 충돌을 방지하기 위함입니다!
3. 해당 리포지토리를 포크한 뒤에, 포크한 리포지토리에서 작업한 후, main 브랜치로 PR을 보내주시면 됩니다.
4. 새로운 문서를 만드는 경우는, 이슈를 등록하고 확인하여 본 이슈에 등록되는 시점부터 총 3주 동안 번역이 가능합니다. 3주 동안 번역이 완료되지 않으면, 이슈가 취소되고 다른 사람에게 해당 문서 번역이 넘어가게 됩니다.

번역을 하실 때에는 아래의 점을 지켜주세요.

1. main 브랜치에 바로 푸시하지 않기.
2. 그 외에 대부분의 타인이 들었을 때에 기분이 나빠질 수 있는 언행 하지 않기.
3. 번역 후에 원문을 제외하고, 자신의 글만 읽었을 때에 알아볼 수 있는지, 잘못된 문장은 없는지 다시 한 번 확인하기.

번역을 하실 때에는 아래의 형식을 지켜주세요.

1. 맨 처음의 타이틀은 가장 큰 제목(#)으로 해주세요.
2. 그 외의 소제목들은 모두 중간 크기의 제목(###)으로 해주세요.
3. 소제목 바로 윗줄은 빈 줄로 만들어주세요.
4. 문서 내에서는 모두 높임말로 작성해주세요.
5. 중간에 들어가는 코드들은 모두 를 사용해서 코드 블럭으로 만들어주세요.
6. 라이브러리 이름, 클래스 이름, 메서드 등 코드 내에서 사용되었던 것을 글에서 사용할 때에는 이렇게 묶어주세요.
7. 문서 맨 마지막에는 한 줄 띄워주세요. [참고](https://velog.io/@doondoony/posix-eol)
8. 문서의 가장 큰 제목 바로 아래에 한 칸 띄우고 원문 링크를 추가해주세요. 아래는 Controllers 페이지의 예시입니다.

```
# Features
(개행)
원문 : [https://www.pycryptodome.org/src/features](https://www.pycryptodome.org/src/features)
(개행)
...
```

번역을 마치셨다면, 기여자 항목에 자신을 추가해주세요!

1. 만약 새로운 문서를 만들었다면, 맨 아래에 문서 기여자 항목을 아래의 형식으로 추가해주세요.

```
    ### 문서 기여자

    - [자신의 닉네임](자신의 깃허브 링크)

    (예시)
    - [코코조용](https://github.com/easycastle)
```

2. 새로운 문서를 만든 것이 아니라, 기존의 문서를 수정한 것이라면 아래의 형식을 문서 기여자 항목에 추가해주세요. 아주 작은 수정이라도 괜찮습니다!

```
    ### 문서 기여자
    ...
    - [자신의 닉네임](자신의 깃허브 링크)
```

커밋하실 때, PR 올리실 때에는 아래의 항목들을 지켜주세요.

1. 커밋 메세지는 자유롭게 하시되, 접두사 형식은 지켜주세요.

```
    [접두사]: [...]
```

- 새 문서를 만들었을 때의 접두사: feat
- 번역을 개선했을 때의 접두사: refactor
- 잘못된 번역을 고쳤을 때의 접두사: fix

2. PR 템플릿에 맞춰서 PR 내용을 작성해주세요.
3. PR 제목은 자신의 작업물을 한 눈에 알아볼 수 있게만 하면 됩니다.

타인의 PR을 리뷰하실 때에는 아래의 항목들을 지켜주세요.

1. 다른 사람의 번역에 대해 이유 없이 맹목적으로 비난하지 않기.
2. 그 외에 대부분의 타인이 들었을 때에 기분이 나빠질 수 있는 언행 하지 않기.
3. 잘 한 점은 칭찬해주기!
   읽어주셔서 감사합니다. :)

### 변역 현황

---

- [ ] PyCryptodome

- [ ] Features

- [ ] Installation

  - [ ] Compiling in Linux Ubuntu
  - [ ] Compiling in Linux Fedora
  - [ ] Windows (from sources)
  - [ ] Documentation
  - [ ] PGP verification

- [ ] Compatibility with PyCrypto

- [ ] API documentation

  - [ ] `Crypto.Cipher` package
    - [ ] Introduction
    - [ ] API principles
    - [ ] Symmetric cihpers
      - [ ] Classic modes of operation
        - [ ] ECB mode
        - [ ] CBC mode
        - [ ] CTR mode
        - [ ] CFB mode
        - [ ] OFB mode
        - [ ] OpenPGP mode
      - [ ] Modern modes of operation
        - [ ] CCM mode
        - [ ] EAX mode
        - [ ] GCM mode
        - [ ] SIV mode
        - [ ] OCB mode
    - [ ] Legacy ciphers
  - [ ] `Crypto.Signature` package
    - [ ] Signing a message
    - [ ] Verifying a signature
    - [ ] Available mechanisms
  - [ ] `Crypto.Hash` package
    - [ ] API principles
    - [ ] Attributes of hash objects
    - [ ] Modern hash algorithms
    - [ ] Extensible-Output Functions (XOF)
    - [ ] Message Authentication Code (MAC) algorithms
    - [ ] Historic hash algorithms
  - [ ] `Crypto.PublicKey` package
    - [ ] API principles
    - [ ] Available key types
      - [ ] RSA
      - [ ] DSA
      - [ ] ECC
    - [ ] Obsolete key type
      - [ ] El Gamal
        - [ ] Signature algorithm
        - [ ] Encryption algorithm
        - [ ] Domain parameters
        - [ ] Security
        - [ ] Functionality
  - [ ] `Crypto.Protocol` package
    - [ ] Key Derivation Functions
      - [ ] PBKDF2
      - [ ] scrypt
      - [ ] bcrypt
      - [ ] HKDF
      - [ ] PBKDF1
    - [ ] Secret Sharing Schemes
  - [ ] `Crypto.IO` package
    - [ ] PEM
    - [ ] PKCS#8
  - [ ] `Crypto.Random` package
    - [ ] `Crypto.Random.random` module
  - [ ] `Crypto.Util` package
    - [ ] `Crypto.Util.asn1` module
    - [ ] `Crypto.Util.Padding` module
    - [ ] `Crypto.Util.RFC1751` module
    - [ ] `Crypto.Util.strxor` module
    - [ ] `Crypto.Util.Counter` module
    - [ ] `Crypto.Util.number` module

- [ ] Examples

  - [ ] Encrypt data with AES
  - [ ] Generate an RSA key
  - [ ] Generate public key and private key
  - [ ] Encrypt data with RSA

- [ ] Frequently Asked Questions

  - [ ] Is CTR cipher mode compatible with Java?
  - [ ] Are RSASSA-PSS signatures compatible with Java or OpenSSL?
  - [ ] Why do I get the error `No module named Crypto` on Windows?
  - [ ] Why does `strxor` raise `TypeError: argument 2 must be bytes, not bytearray`?
  - [ ] Why do I get a `translation_unit_or_empty undefined` error with `pycparser`?

- [ ] Contribute and support

- [ ] Future plans
