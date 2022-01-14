# 설정한 단축키 설명 (맥 기준)
| 단축키              | 설명                                                                                                                                                                       |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Command + \[        | 직전에 열었던 파일로 이동                                                                                                                                                  |
| Command + \]        | Command + \[의 반대                                                                                                                                                        |
| Command + Backspace | 현재 파일 삭제                                                                                                                                                             |
| Ctrl + Tab          | [Templater 플러그인, 다음 커서로 이동](https://silentvoid13.github.io/Templater/internal-functions/internal-modules/file-module.html#examples) , 링크의 `File Cursor` 참고 |
| Command + T         | 현재 파일에 템플릿 넣기                                                                                                                                                    |
| Command + R         | 현재 파일에서 Find and Replace                                                                                                                                             |
| Command + .         | Live Preview와 Source View 토글                                                                                                                                            |

# Obsidian References
- [Format your notes](https://help.obsidian.md/How+to/Format+your+notes)

# Convnetion
디렉토리와 파일 이름은 소문자와 대쉬를 사용한다. 스페이스바는 사용하지 않는다.

# Plugins
- [Citations](obsidian://show-plugin?id=obsidian-citation-plugin)
    - [bibliography/zotero](./bibliography/zotero) 디렉토리는 Zotero와 Sync를 한다.

# 제텔카스텐 시스템
1. Zotero에는 책 자체에 대한 메타데이터만 담는다.
    1. bibliography/zotero 디렉토리는 Zotero와 Sync가 되어있다.
    2. Citation plugin을 활용해서 literature note를 생성하면 CitationKey를 가진 파일이 생성된다.
    3. CitationKey와 동일한 이름의 디렉토리를 만들어서 note들을 넣는다.
2. [permanents](./permanents) 디렉토리에는 레퍼런스를 통해 얻은 생각들을 내 언어로 적는다. (영구보관메모)
    1. [permanents](./permanents) 디렉토리에는 하위 디렉토리를 넣지 않는다. 모든 파일이 하나의 디렉토리에 있도록.
    2. id를 사용한다
        >그는 논평, 수정, 추가 등 새로운 메모가 기존의 메모와 관련성이 있거나 직접 연관되면, 기존의 메모 바로 뒤에 새 메모를 추가했다. 가령, 기존 메모가 22번이라면, 새 메모는 23번이 되는 식이다. 만약 23번이 이미 존재한다면 새 메모는 22a가 된다. 그는 중간에 사선부호(/)와 쉼표(,)를 넣으면서 숫자와 알파벳을 번갈아 사용하는 방식으로 메모를 통한 생각의 가지들을 마음껏 확장했다. 가령, 인과관계와 시스템 이론에 관한 루만의 메모에는 21/3d7a6번 메모의 뒤를 이어 21/3d7a7이라는 번호가 붙었다.
        >(추측: 1,5 같이 쉼표가 붙어있는 문서는 여러 개의 아이디어를 합쳐서 생각하는 문서인듯.)
        >![[IMG_3058.jpg|600]]
    3. 자식 파일에는 부모 파일의 링크를 걸어 graph에서 명확하게 보이도록 한다.
        1. 예) 22a 메모에는 22번의 링크를 추가한다.
3. [drafts](./drafts) 디렉토리에는 [permanents](./permanents) 디렉토리의 파일들을 모아서 원고를 작성한다.