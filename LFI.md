# PHP Wrapper
## expect://
system command를 실행.

## php://filter
문서 열람과 동시에 encode 또는 decode.
### base64
#### encode
php://filter/convert.base64-encode/resource=`경로`
#### decode
php://filter/convert.base64-decode/resource=`경로`

## zip://
zip파일의 압축을 풀고 압축을 푼 파일안에 있는 코드를 실행.

zip://`압축 파일`#`내부 파일`
