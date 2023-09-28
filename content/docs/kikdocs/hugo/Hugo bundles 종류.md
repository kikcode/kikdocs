# Hugo bundles 종류

- 브렌치 번들 : 공통의 첫머리를 공유하는 페이지 세트.
  브랜치 번들은 \_index.md를 템플릿으로 사용하여 각각의 컨텐츠 리프 페이지를 대표한다.
  예 : blog
  특정 주제에 대한 블로그 게시물이나 문서처럼 여러 개의 유사한 페이지 집합이 필요한 경우를 일커른다
- 리프 번들 : 단일 페이지. 단일 페이지는 머리글과 컨텐츠로 구성된 index.md
- index.md : 여러 리프 페이지의 분기를 형성하는 폴더(예 : menu폴더의 index.md)에 단일 페이지로 사용된다.

```bash
# 브렌치 번들에서 새 리프 페이지 생성
hugo new post-1.md
```

### index.md와 \_index.md의 차이점

\_index.md : 같은 폴더 아래에 여러 페이지가 있는 경우 사용됨.(폴더를 클릭 했을 때 어떤 페이지를 보여주어야할 지 hugo가 판단하기 어렵다. 보통 폴더의 소개글을 \_index.md에 나타낸다.)

또는 분류 용어에 대한 메타데이터를 추가 하려는 경우 사용됨.

참고 사이트

[Hugo index.md vs \_index.md | Tangent Technologies](https://tangenttechnologies.ca/blog/hugo-indexmd-vs-_indexmd/)

---

번들 : 웹 페이지를 만들기 위해 함께 가져온 파일들의 모음
