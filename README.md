# World Shop

이 플러그인은 단순 고정 가격 상점이 아니라
플레이어 거래량에 따라 가격이 자동으로 조정되는 경제 상점 시스템입니다.

서버 경제 인플레이션을 방지하고, 자원 가치가 자연스럽게 변하도록 설계되었습니다.

주요 기능
------------------------------------------------------
1) GUI 기반 상점

/shop 명령어로 카테고리 메뉴 열기

카테고리별 아이템 목록 GUI 제공

클릭으로 직관적인 거래 진행
------------------------------------------------------
2) 동적 가격 시스템 (핵심 기능)

거래량에 따라 가격이 자동 조정됩니다.

많이 팔릴수록 → 판매 효율 감소 (가격 하락)

많이 사갈수록 → 구매 비용 증가 (가격 상승)

즉, 서버 경제가 자동으로 균형을 맞춥니다.
------------------------------------------------------
3) 카테고리 시스템

관리자가 카테고리 생성 가능

판매 카테고리 (플레이어 → 상점 판매)

구매 카테고리 (상점 → 플레이어 구매)

예:

농작물 판매 카테고리

전투 아이템 구매 카테고리
------------------------------------------------------
4) 관리자 설정 명령어
/shopadmin addcategory
/shopadmin removecategory
/shopadmin additem
/shopadmin removeitem
/shopadmin listcategories
/shopadmin listitems
/shopadmin reload


서버 재시작 없이 상점 데이터 리로드 가능
------------------------------------------------------
5) 데이터 저장

YAML 파일 기반 저장

서버 재시작 후에도 가격 및 거래 상태 유지

특징 요약

고정 가격 상점 ❌

------------------------------------------------------

Detailed description
Overview

This is not a fixed-price shop plugin.

The shop automatically adjusts prices based on player trading activity, creating a self-balancing economy system.

Designed to prevent inflation and maintain item value naturally.

Features
------------------------------------------------------
1) GUI Shop

Open shop with /shop

Category-based menu

Click-to-trade interface
------------------------------------------------------
2) Dynamic Pricing System (Core Feature)

Prices change depending on trading activity:

Items sold frequently → lower selling efficiency

Items bought frequently → higher purchase cost

The server economy balances itself automatically.
------------------------------------------------------
3) Category Types

Admins can create categories:

SELL category (players sell items to shop)

BUY category (players buy items from shop)
------------------------------------------------------
4) Admin Commands
/shopadmin addcategory
/shopadmin removecategory
/shopadmin additem
/shopadmin removeitem
/shopadmin listcategories
/shopadmin listitems
/shopadmin reload


No restart required to update shop data.
------------------------------------------------------
5) Persistent Data

YAML storage

Trading history and price state persist after restart

Summary

Not a static shop
→ Self-balancing economy system


서버 경제 자동 조절 ⭕

경제 인플레이션 방지용 상점
