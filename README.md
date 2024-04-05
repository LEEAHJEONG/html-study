# HTML

1.1. HTML 구조 파악하기

```html
<!-- 1. 현재 문서가 HTML5 언어로 작성한 웹 문서라는 의미 -->
<!DOCTYPE html>
<!-- 2. <html> 내용 </html> 웹 문서의 시작과 끝을 나타내는 태그 -->
<html lang="ko">
  <!-- 3. <head> 내용 </head> 웹 브라우저가 웹 문서를 해석하는데 필요한 정보를 입력 -->
  <head>
    <!-- 메타정보 : 데이터 관련 -->
    <!-- 한글 인코딩을 위해서 명시하는 태그 -->
    <!-- 웹 사이트의 키워드나 간단한 설명, 제작자 등의 정보를 지정 -->
    <!-- 검색 엔진에서 사이트를 검색할 때 참고한다. -->
    <meta charset="UTF-8" />
    <!-- viewport : 화면을 나타낸다. -->
    <!-- width=device-width 화면에 1:1 비율로 나타냄. 반응형 -->
    <!-- 반응형을 위한 메타 태그 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- 웹 문서의 키워드 -->
    <meta name="keywords" content="html의 구조" />
    <!-- 웹 문서의 설명 -->
    <meta name="description" content="html의 구조를 알아봅시다" />
    <meta name="author" content="이아정" />
    <!-- 타이틀 태그: 웹 문서의 제목, 웹 브라우저의 제목 표시줄에 표시 예) 즐겨찾기,북마크 -->
    <!-- 웹 사이트의 즐겨찾기를 지정할 때도 웹 문서 제목으로 추가됨 -->
    <title>HTML 구조파악하기</title>
  </head>
  <body>
    <div>
        <header>
            <h1>헤더입니다</h1>
        </header>
        <!-- <body> 내용 <body> 실제로 웹 브라우저 화면에 나타나는 내용 -->
            <h1>프론트엔드 웹 개발</h1>
            <!-- 밑줄 -->
            <hr />
            <!-- 단락 -->
            <p>HTML</p>
            <p>CSS</p>
            <p>Javascript</p>
            <p>React</p>
        </main>
        <footer>
            <f3>푸터입니다.</f3>
        </footer>
    </div>
  </body>
</html>
```
