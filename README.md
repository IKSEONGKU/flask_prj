# flask_prj

```python
# 저장위치 수정
    file.save(os.path.join('static/img', filename))
#   file.save(os.path.join('uploads', filename))
```
css, js 저장위치 수정, 이미지 추가
```html
<script src="../static/public/js/main.js"
<link rel="stylesheet" href="../static/public/css/style.css">

<form method="POST" action="/upload" enctype="multipart/form-data">
			<input type="file" name="image">
			<input type="submit" value="Upload">
</form>
<img src="{{url_for('static', filename = filename)}}" alt="아직 업로드된 파일이 없습니다.">
```


