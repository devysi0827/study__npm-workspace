- npm ls (--all) : 의존관계 표현
- npm -y -w `상대경로` : 상대경로에 workspace 생성, `-w`는 workspace를 사용하겠다는 옵션

- 유령의존성 문제 : 현재 workspace의 package.json에 등록되지 않은 패키지를 사용할 수 있다. 하지만, 이는 패키지의 업데이트, 삭제로 인해 예상치 못한 문제를 만들 수 있다. 이는 node_modules의 hosisting으로 인한 근본적인 문제이다.
