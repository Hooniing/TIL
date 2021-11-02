# VBA 기초

## Contents

- [함수](#함수)
  - [formula]
- [팁](#팁)
- [Code Snippet](#Code Snippet)
- [공부할 것](#공부해야할 것)

---



## 함수

VBA 함수에 대한 내용

- formula 함수
- 

 

## 팁

엑셀 A1스타일로 Range에 활용하여 셀에 접근하는 방식

``` VBA
Private Sub Worksheet_Change(ByVal Target As Range)
    If Not Intersect(Range("B3:H16"), Target) Is Nothing Then
        Range("I" & Target.Row).Value = Format(Now, "hh:mm:ss")
    End If
End Sub
```

출처 : [셀 내용이 바뀔 때 바뀐 날짜가 기록되게 하기](https://www.oppadu.com/question/?mod=document&uid=1433)



``` VBA

```



## Code Snippet

사용하면 유용한 코드 및 함수들 모음





## 공부할 것

- [엑셀 VBA 셀 참조하는 여러가지 방법 5min](https://mainia.tistory.com/3168)
- [Value, Text, Formula 속성으로 값 지정하기](https://mainia.tistory.com/1280)
- 



출처 : [제목](링크)