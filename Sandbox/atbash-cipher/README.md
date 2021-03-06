# Atbash Cipher

*Atbash Cipher* 로 알려진 중동에서 사용되었던 고대의 암호화 기법이 있다.

*Atbash Cipher* 기법은 다음과 같다.

a 는 첫번째 알파벳이므로 마지막 알파벳인 z 로 바꾼다. b 는 두번째 알파벳이므로 마지막에서 두번째 알파벳인 y 로 바꾼다.
마찬가지 방법으로 어떠한 알파벳을 반대 순서의 다른 알파벳으로 모두 바꿔 준다.

> 원래 문자열 순 : abcdefghijklmnopqrstuvwxyz<br>
암호화 문자열 순 : zyxwvutsrqponmlkjihgfedcba

예를 들어, 아래처럼 암호화 할 수 있다.

> 'test' -> 'gvhg'<br>
'The quick brown fox jumps over the lazy dog.' -> 'gsvjf rxpyi ldmul cqfnk hlevi gsvoz abwlt'

암호화된 정보는 해독하기 어렵도록 원래 문장과는 상관없이 5글자씩 묶어 표시한다.

어떤 문자열이 주어졌을 때, *Atbash Cipher* 기법으로 암호화된 문자열을 반환하는 클래스를 작성하라.

## Structure

Atbash 클래스를 작성한다.

다음 함수를 작성한다.

    class func encode(_ target: String) -> String

주어진 문자열을 *Atbash Cipher* 기법으로 변환하여 반환한다.

## Caution

원래의 문자열에 포함된 문장부호와 특수문자는 모두 무시한다.

## Source

    class Atbash {
        class func encode(_ target: String) -> String {
            var result: String = ""
            /* write your code here */
            return result
        }
    }
