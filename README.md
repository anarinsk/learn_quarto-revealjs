# learn_quarto-revealjs
 
## Purpose 

- Quarto-Revealjs를 통해서 Revealjs 기반 PT를 생성한다. 
- [자매 리포](https://github.com/anarinsk/project_quarto-rjs-advanced)도 참고하시라. 

## How 

### Tools 
- [Quarto CLI](https://github.com/quarto-dev/quarto-cli)(Linux-64, macos-arm64)
- [VS Code의 Quarto 플러그인](https://quarto.org/docs/tools/vscode.html)

### Source 
- 문서 소스:
  - [old] `main.qmd`
  - [current] `main_v2-0.qmd`, `main_v2-0_larger.qmd`

## What 

- 구현물은 [Completely useless presentation](https://anarinsk.github.io/learn_quarto-revealjs/#/title-slide)을 참고하라. 

## Infos 

- 폰트는 SUIT, SUITE, D2Coding을 웹폰트로 활용합니다. 자세한 내용은 `index.css` 파일을 참고.

## Major Updates 

-  🔗[경북대 취업특강](https://knu-techjobs.anari.dev/)을 통해 테스트한 내용을 본문에 반영

## Miscellenous Updates 

- 폰트가 적용되지 않는 문제
    - `theme`으로 css를 로딩 
- math 폰트 조절 
    - mathjax를 별도로 로딩하고 css에서 `STIX Two Text` 로딩
- revealjs 옵션
    - github pages를 쓰기 위해서는 `embed-resources: true`를 반드시 포함해야 한다.
    - `_quarto.yml`을 포함하여 출력물 폴더는 `docs`로 설정한 후 pages 옵션에서 퍼블리시 하는 게 제일 편하다.
    - https://quarto.org/docs/publishing/github-pages.html 첫번째 옵션 참고 

