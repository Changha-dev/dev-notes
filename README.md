<div align="center">

# dev-notes

공부한 것을 내 말로 다시 쓰는 곳

![notes](https://img.shields.io/badge/notes-1-2a55c9?style=flat-square)
![lang](https://img.shields.io/badge/lang-한국어-555?style=flat-square)
![diagrams](https://img.shields.io/badge/diagrams-Mermaid-ff3670?style=flat-square&logo=mermaid&logoColor=white)

</div>

## 노트

### 주제별 정리 · `topics/`

강의 밖에서 일하다 부딪혀 파고든 것들.

| 분야 | 노트 | 키워드 |
|---|---|---|
| 네트워크 | [Tailscale로 밖에서 Orca 쓰기](topics/networking/tailscale-orca-remote.md) · [HTML](https://changha-dev.github.io/dev-notes/topics/networking/tailscale-orca-remote.html) | WireGuard, NAT 홀펀칭, CGNAT 대역, TUN 인터페이스 |

### 강의 정리 · `courses/`

| 강의 | 상태 |
|---|---|
| _아직 없음_ | |

## 구조

```
dev-notes/
├── courses/<강의-슬러그>/   # 강의 하나 = 폴더 하나 (README 목차 + 섹션별 노트)
└── topics/<분야>/           # 강의와 무관한 주제 노트
```

## 규칙

- 평서체(~다)로 쓴다.
- 흐름·구조 그림은 Mermaid로 그려 GitHub에서 바로 보이게 한다.
- 파일명은 영문 kebab-case, 제목은 한국어.
- 도식이 많은 노트는 같은 이름의 `.html`을 옆에 두고 GitHub Pages 링크로 연다. GitHub은 `.html`을 소스로만 보여 준다.
- 실제 IP·토큰 같은 개인 정보는 예시 값으로 바꿔 올린다.
