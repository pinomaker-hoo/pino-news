# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**pino-news**는 한국어 기반 개발/기술 리소스를 큐레이션하는 마크다운 문서 저장소입니다. 빌드 시스템, 테스트, 린트 등은 없으며 순수 마크다운 파일로만 구성됩니다.

## Content Structure

- `websites/dev.md` — 개발/기술 일반 웹사이트 (리포트, 포털 등)
- `websites/dev-utils.md` — 설치 없이 웹에서 사용 가능한 개발 유틸리티 도구

향후 `repositories/`, `blogs/`, `communities/`, `education/`, `etc/` 디렉토리가 추가될 수 있음.

## Entry Format

각 리소스 항목은 다음 형식을 따름:

```markdown
- [이름](링크)
  - **설명**: 1-2줄 설명
  - **분류**: 카테고리
  - **레벨**: 입문 / 초급 / 중급 / 고급 / 전 레벨 공통
  - **비고**: (선택) 부가 정보
```

## Conventions

- **언어**: 모든 콘텐츠는 한국어로 작성
- **포함 기준**: 한국어 기반이거나 한국어 지원이 우수한 리소스만 포함
- **중복 금지**: 기존 항목과 중복되는 리소스 추가 불가
- **커밋 메시지**: `feat : 설명` 형식 (콜론 앞 공백 포함)
- **브랜치 네이밍**: `feat/<feature-name>`
- **PR 템플릿**: `.github/pull_request_template.md` 참조
