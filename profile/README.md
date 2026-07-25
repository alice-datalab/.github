<div align="center">

# Alice

Shared infrastructure for practical software.

</div>

## About

**Alice**는 여러 제품에서 공통으로 사용하는 비공개 소프트웨어 기반입니다.

Cloudflare Workers 환경에서 인증, 세션, 조직과 멤버십, 권한 판정, 알림과 서비스 간 계약을 일관된 방식으로 제공합니다.

## Architecture

Alice는 기능별로 분리된 독립 서비스와 공통 계약으로 구성됩니다.

- Identity and session management
- Organizations, memberships and invitations
- Product roles and permission checks
- Transactional notifications
- Gateway and service integration
- Shared runtime schemas and RPC contracts

각 구성 요소는 독립적으로 배포되며, 명시적인 계약을 통해 연결됩니다.

## Status

Under active development. Most repositories are private.

## Tech

`Cloudflare Workers` · `D1` · `TypeScript` · `React`
