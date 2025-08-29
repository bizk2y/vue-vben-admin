<div align="center">
  <a href="https://github.com/anncwb/vue-vben-admin">
    <img alt="VbenAdmin 로고" width="215" src="https://unpkg.com/@vbenjs/static-source@0.1.7/source/logo-v1.webp">
  </a>
  <br>
  <br>

[![license](https://img.shields.io/github/license/anncwb/vue-vben-admin.svg)](LICENSE)

  <h1>Vue Vben Admin</h1>
</div>

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=vbenjs_vue-vben-admin&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=vbenjs_vue-vben-admin) ![codeql](https://github.com/vbenjs/vue-vben-admin/actions/workflows/codeql.yml/badge.svg) ![build](https://github.com/vbenjs/vue-vben-admin/actions/workflows/build.yml/badge.svg) ![ci](https://github.com/vbenjs/vue-vben-admin/actions/workflows/ci.yml/badge.svg) ![deploy](https://github.com/vbenjs/vue-vben-admin/actions/workflows/deploy.yml/badge.svg)

**[English](./README.md)** | [한국어](./README.ko-KR.md) | [중국어](./README.zh-CN.md) | [일본어](./README.ja-JP.md)

## 소개

Vue Vben Admin은 무료 오픈 소스 중백엔드 템플릿입니다. 최신 `vue3`, `vite`, `TypeScript` 등 주류 기술을 사용하여 개발되었으며, 바로 사용 가능한 중백엔드 프론트엔드 솔루션은 학습 참고용으로도 사용할 수 있습니다.

## 업그레이드 공지

이것은 최신 버전인 5.0이며 이전 버전과 호환되지 않습니다. 새 프로젝트를 시작하는 경우 최신 버전을 사용하는 것이 좋습니다. 이전 버전을 보려면 [v2 브랜치](https://github.com/vbenjs/vue-vben-admin/tree/v2)를 사용하십시오.

## 특징

- **최신 기술 스택**: Vue 3 및 Vite와 같은 최첨단 프론트엔드 기술로 개발되었습니다.
- **TypeScript**: 애플리케이션 규모의 JavaScript를 위한 언어입니다.
- **테마**: 사용자 정의 가능한 옵션과 함께 여러 테마 색상을 사용할 수 있습니다.
- **국제화**: 포괄적인 내장 국제화 지원.
- **권한**: 동적 경로 기반 권한 생성을 위한 내장 솔루션입니다.

## 미리보기

- [Vben Admin](https://vben.pro/) - 전체 버전 중국어 사이트

테스트 계정: vben/123456

<div align="center">
  <img alt="VbenAdmin 로고" width="100%" src="https://anncwb.github.io/anncwb/images/preview1.png">
  <img alt="VbenAdmin 로고" width="100%" src="https://anncwb.github.io/anncwb/images/preview2.png">
  <img alt="VbenAdmin 로고" width="100%" src="https://anncwb.github.io/anncwb/images/preview3.png">
</div>

### Gitpod 사용

Gitpod(GitHub용 무료 온라인 개발 환경)에서 프로젝트를 열고 즉시 코딩을 시작하십시오.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/vbenjs/vue-vben-admin)

## 문서

[문서](https://doc.vben.pro/)

## 설치 및 사용

1. 프로젝트 코드 가져오기

```bash
git clone https://github.com/vbenjs/vue-vben-admin.git
```

2. 종속성 설치

```bash
cd vue-vben-admin
npm i -g corepack
pnpm install
```

3. 실행

```bash
cd coreq
pnpm dev
```

4. 빌드

```bash
pnpm build
```

## 변경 로그

[CHANGELOG](https://github.com/vbenjs/vue-vben-admin/releases)

## 기여 방법

참여를 매우 환영합니다! [문제 제기](https://github.com/anncwb/vue-vben-admin/issues/new/choose) 또는 Pull Request를 제출하십시오.

**Pull Request 프로세스:**

1. 코드 포크
2. 브랜치 생성: `git checkout -b feat/xxxx`
3. 변경 사항 제출: `git commit -am 'feat(function): add xxxxx'`
4. 브랜치 푸시: `git push origin feat/xxxx`
5. `pull request` 제출

## Git 기여 제출 사양

[vue](https://github.com/vuejs/vue/blob/dev/.github/COMMIT_CONVENTION.md) 사양 ([Angular](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-angular)) 참조

- `feat` 새로운 기능 추가
- `fix` 문제/버그 수정
- `style` 코드 스타일 관련, 실행 결과에 영향 없음
- `perf` 최적화/성능 향상
- `refactor` 리팩토링
- `revert` 편집 취소
- `test` 테스트 관련
- `docs` 문서/메모
- `chore` 종속성 업데이트/스캐폴딩 구성 수정 등
- `ci` 지속적인 통합
- `types` 유형 정의 파일 변경

## 브라우저 지원

로컬 개발에는 `Chrome 80+` 브라우저를 권장합니다.

최신 브라우저를 지원하며 IE는 지원하지 않습니다.

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari |
| :-: | :-: | :-: | :-: |
| 마지막 2개 버전 | 마지막 2개 버전 | 마지막 2개 버전 | 마지막 2개 버전 |

## 유지 관리자

[@Vben](https://github.com/anncwb)

## 스타 히스토리

[![Star History Chart](https://api.star-history.com/svg?repos=vbenjs/vue-vben-admin&type=Date)](https://star-history.com/#vbenjs/vue-vben-admin&Date)

## 기부

이 프로젝트가 도움이 되었다고 생각하시면 저자를 위해 커피 한 잔을 사주시는 것으로 지지를 보여주실 수 있습니다!

![donate](https://unpkg.com/@vbenjs/static-source@0.1.7/source/sponsor.png)

<a style="display: block;width: 100px;height: 50px;line-height: 50px; color: #fff;text-align: center; background: #408aee;border-radius: 4px;" href="https://www.paypal.com/paypalme/cvvben">Paypal Me</a>

## 기여자

<a href="https://openomy.app/github/vbenjs/vue-vben-admin" target="_blank" style="display: block; width: 100%;" align="center">
  <img src="https://openomy.app/svg?repo=vbenjs/vue-vben-admin&chart=bubble&latestMonth=3" target="_blank" alt="Contribution Leaderboard" style="display: block; width: 100%;" />
 </a>

<a href="https://github.com/vbenjs/vue-vben-admin/graphs/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=vbenjs/vue-vben-admin" />
</a>

## 디스코드

- [Github 토론](https://github.com/anncwb/vue-vben-admin/discussions)

## 라이선스

[MIT © Vben-2020](./LICENSE)
