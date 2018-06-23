#juuninis WYSIWYG Editor
----------------------------

코드 하이라이터를 넣고싶어서 직접 만든 개발자용 위지윅 에디터입니다.<br>
highlight.js를 이용했고, 테이블 추가 기능이나 기타 기능들은 추후에 업데이트 할 예정입니다.<br>

## 사용법
------------------------------

```
<link rel="stylesheet" href="highlight.css">
<link rel="stylesheet" href="juuninisEditor.css">

<script src="highlight.js">
<script src="juuninisEditor.js">

<juuninis-editor></juuninis-editor>

<script>
    var editor = new juuninisEditor();
    editor.ImageUpload("/img", 1024, "/img/");
    // editor.ImageUpload(postURL, 제한KB, 이미지 URI prefix);
</script>
```

첨부해놓은 highlight.js와 highlight.css를 쓰셔도 되고, atom-one-dark 테마가 마음에 안드시면 다른 테마의 highlight.css로 바꿔서 써주시기 바랍니다.
