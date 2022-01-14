
```dataview
TABLE authors, title
WHERE file.folder = this.file.folder AND file.name != this.file.name SORT authors ASC
```

Zotero에서 자동으로 생성하는 CitationKey로 파일과 디렉토리 이름이 정해진다.

Citation plugin을 통해 노트를 생성하고(Ctrl + Shift + O), 생성한 파일과 동일한 이름의 디렉토리를 생성해 note를 넣는다.

추후에 책이 너무 많아질 경우 파일의 태그에 십진분류표를 넣어보는 방식을 사용할 수 있다. 아직까지는 필요 없으니...