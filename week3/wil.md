# 1. margin과 padding
margin과 padding은 웹 페이지의 요소 주변에 여백을 만드는 데 사용되는 속성이다.
웹의 모든 요소는 사각형의 박스 형태를 띠며, 중심부터 바깥쪽 순으로 **content->padding->border->margin**으로 구성된다.

## padding: 본문(content)과 테두리(border) 사이 여백을 조절한다.
### css 작성법
- 개별지정
```javascript
p {
    padding-top:5px;
    padding-right:5px;
    padding-bottom:5px;
    padding-left:5px;
}
```
- 통합지정
```javascript
p{
    padding:5px; //4면 전체
    padding:5px 7px 6px 2px; //위, 오른쪽, 아래, 왼쪽
    padding:5px; 7px //위 아래, 오른쪽 왼쪽
}
```

## margin: 현재 요소와 다른 요소 사이의 간격 조절한다.
### css 작성법 
- 개별지정
```javascript
m{
    margin-top:5px;
    margin-right:5px;
    margin-bottom:5px;
    margin-left:5px;
}
```
- 통합지정
    :padding 방식과 동일

2.참고자료
[padding](https://aboooks.tistory.com/81)
[margin](https://aboooks.tistory.com/78)
