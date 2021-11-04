# 기본
1. {{ ''.__class__.__mro__ }} 를 쳐서 <type 'object'>의 인덱스를 찾음.
2. {{ ''.__class__.__mro__[`인덱스`].__subclasses__() }}

# 파일
1. 위 mro의 subclass 에서 <type 'file'>의 인덱스를 찾는다.
2. {{ ''.__class__.__mro__[`인덱스`].__subclasses__()[`인덱스`].open(`파일 경로`).read() }}
