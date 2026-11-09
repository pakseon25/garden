# garden

Quartz로 만든 개인 위키. `content/`에 Markdown으로 기록하고 `[[문서 제목]]`으로 연결한다.

## 로컬 미리보기

Node.js 22 이상이 필요하다. 처음 실행할 때는 다음 순서로 설정한다.

```sh
npm ci
npx quartz create
npx quartz plugin install --from-config
```

설정이 끝나면 `npx quartz build --serve`를 실행하고 [localhost:8080](http://localhost:8080)을 연다.

[Quartz 공식 문서](https://quartz.jzhao.xyz/)
