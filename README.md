# 나만의 문제은행

문제·답·해설(사진 포함)을 등록해 두고 랜덤으로 풀어보는 사이트입니다.

- 누구나 사이트 주소로 접속해서 문제를 풀 수 있어요. (컴퓨터, 휴대폰 모두)
- 문제 추가·수정·삭제는 **관리** 탭에서 GitHub 토큰으로 로그인한 사람만 할 수 있어요.
- 문제는 `data/questions.json`, 해설 사진은 `data/img/` 에 저장돼요.
- ‘이후로 안 보기’는 각자 기기에만 적용돼요.

## 사이트 켜기 (GitHub Pages)

1. 저장소 → **Settings → Pages**
2. Source: **Deploy from a branch**, Branch: **main** / **(root)** → Save
3. 1~2분 뒤 `https://<아이디>.github.io/<저장소이름>/` 에서 열려요.

Vercel을 쓰고 싶다면 vercel.com → Add New → Project → 이 저장소 선택 → Deploy.

## 관리자 토큰 만들기

1. GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate new token
2. Repository access: **Only select repositories** → 이 저장소만 선택
3. Repository permissions → **Contents: Read and write**
4. 만든 토큰을 사이트의 **관리** 탭에 붙여넣고 로그인

토큰은 로그인한 기기의 브라우저에만 저장됩니다. 공용 컴퓨터에서는 쓰고 나서 로그아웃하세요.
