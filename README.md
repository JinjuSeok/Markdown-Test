# 마크다운 정리

```
#h1 테스트
## h2 테스트
###### h6 테스트
```
# h1 테스트
## h2 테스트
###### h6 테스트

****

강조 방법
```
*이탤릭체*
_이것도 이탤릭체_

**볼드체**
__볼드체__

_이탤릭체와 **볼드체**_
```
*이탤릭체*
_이것도 이탤릭체_

**볼드체**
__볼드체__

_이탤릭체와 **볼드체**_


순서 없는 리스트
```
* item 1
* item 2
    * item 2a
    * item 2b
```
* item 1
* item 2
    * item 2a
    * item 2b


순서 있는 리스트
```
1. item 1
1. item 2
1. item 3
    1. item 3a
    1. item 3b
```    
1. item 1
1. item 2
1. item 3
    1. item 3a
    1. item 3b

이미지

```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```
![MyCat](https://avatars0.githubusercontent.com/u/42496890?s=460&v=4)


링크
```
http://github.com - automatic!
[GitHub](http://github.com)
```
http://github.com - automatic!
[GitHub](http://github.com)


인용문
```
진주가 말했다 : 
> 왜 모래밭이라고 나올까,
> 모래밭이기 때문이다.
```
진주가 말했다 : 
> 왜 모래밭이라고 나올까,
> 번역의 한계 때문이다.


인라인 코드

```
이거를 이렇게 감싸보면
`# h1 ` 마크다운 문법으로 표시가 안되고 코드 자체로 표시된다
```
이거를 이렇게 감싸보면
`# h1 ` 마크다운 문법으로 표시가 안되고 코드 자체로 표시된다





문법 하이라이팅을 할 수 있다.
```
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
의 마지막에 ```을 붙이면(..) 아래처럼 하이라이팅이 적용된다.

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

작업 목록
```
- [x] 작업1
- [x] 작업2
- [ ] 작업3
- [x] 작업4
```
- [x] 작업1
- [x] 작업2
- [ ] 작업3
- [x] 작업4


표 만들기
```
코코 | 뚱이
--- | ---
코숏 | 페르시안
기분파 | 바보
```
코코 | 뚱이
--- | ---
코숏 | 페르시안
기분파 | 바보


취소선

```
뚱이는 ~~뚠뚠하다~~ 잘먹는다.
```
뚱이는 ~~뚠뚠하다~~ 잘먹는다.
