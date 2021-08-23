## Daily_Study

### HTML 문서의 기본 구조
 ```
 <html>는 웹 문서의 시작을 알리는 html 태그
 <head>는 웹 브라우저에 문서 정보를 알려주는 태그
 <title>는 문서 제목을 나타내는 태그
 ```
 
### HTML 목록 실습
```
<!DOCTYPE html>
<html lang="ko">
<body>
    <ol>
        <li>입춘맞이 : 1/27(월) ~ 1/31(금)</li>
        <li>낭쉐코사 : 2/1(토)</li>
        <li>거리굿 : 2/2(일)</li>
        <li>열림굿 : 2/3(월)</li>
        <li>입춘굿 : 2/4(화)</li>
      </ol>
</body>
</html>
```

### 실행결과

<!DOCTYPE html>
<html lang="ko">
<body>
    <ol>
        <li>입춘맞이 : 1/27(월) ~ 1/31(금)</li>
        <li>낭쉐코사 : 2/1(토)</li>
        <li>거리굿 : 2/2(일)</li>
        <li>열림굿 : 2/3(월)</li>
        <li>입춘굿 : 2/4(화)</li>
      </ol>
</body>
</html>

***&lt;ol&gt;과 &lt;li&gt;는 순서있는 목록을 입력하군!***

### HTML 표 만들기
```
 표의 시작과 끝을 알려주는 <table>과 </table> 태그를 표시하고
 표에 제목을 붙이고 싶다면 <table> 태그 바로 아랫줄에 <caption> 태그를 사용한다.
 <tr> 태그는 행을 만들고 <td> 태그는 행안에 셀을 만든다
```



### HTML에 이미지를 삽입하는 &lt;img&gt;태그
```
<img src="이미지 파일 경로" alt="대체용 텍스트">
2. 여기서 알아야 할 속성은 src와 alt이다
src속성은 이미지 파일의 경로를 지정하여 웹 브라우저에 알려주는 역할을 한다
alt속성에는 화면 낭독기 등에서 이미지를 대신해서 읽어 줄 텍스트를 입력한다
```

### HTML에 이미지 삽입 실습
```
<img scr="images/tangerines.jpg" alt="레드향">
<h1>레드향<h1>
```

***이미지 파일의 경로를 정확하게 입력하지 않으면 이미지가 화면에 나타나지 않는다!***

### HTML 이미지 크기 조절하는 width, height 속성
```
width는 이미지의 너비를, height는 이미지의 높이를 정한다
width, height 속성에서 사용할 수 있는 단위는 퍼센트(%)와 픽셀(px)가 있다
이미지 크기의 값을 퍼센트(%)로 지정하면 현재 웹 브라우저 창의 너비와 높이를 기준으로 이미지 크기를 결정한다
이미지 크기의 값을 픽셀(px)로 지정하면 이미지의 너비나 높이를 해당 픽셀 크기만큼 표시한다
```

### HTML에 폼을 만드는 &lt;form&gt; 태그
```
method : 사용자가 입력한 내용을 서버쪽 프로그램으로 어떻게 넘겨줄 것인지 지정한다
name : 자바스크립트로 폼을 제어할 때 사용할 폼의 이름을 지정한다
action : <form> 태그 안의 내용으 처리해 줄 서버 프로그램을 지정한다
target : action 속성에서 지정한 스크립트 파일을 현재 창이 아닌 다른 위치에서 열도록 한다
```

### HTML 폼 만들기
```
<form action="">
    <fieldset>
      <legend>상품 선택</legend>
      
    </fieldset>
    <fieldset>
      <legend>배송 정보</legend>
      
    </fieldset>      
  </form>
```
