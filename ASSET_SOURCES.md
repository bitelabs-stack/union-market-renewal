# 에셋 출처 및 사용 범위

확인일: 2026-10-27. 리뉴얼 준비용 공개 시안의 파일 목록입니다. 외부 공개 이미지라는 사실만으로 별도 재사용 라이선스가 확인되는 것은 아닙니다. 운영 전환 전 권한·브랜드 관계·최신 제품 화면을 확인해야 합니다.

## 사용자 제공 원본
| 파일 | 출처 | 처리 |
|---|---|---|
| assets/market-logo.png | 최종 사용자 정정 첨부 image.png | 원본 그대로, 홈·이야기 헤더 및 홈 푸터 |
| assets/market-logo-white.png | 위 원본의 파생본 | 글자 흰색·빨간 O 유지, 이야기 어두운 푸터 |
| assets/logo.png | 앞서 첨부된 UNION SOFT 로고 | 유니온소프트 솔루션 소개에만 사용 |
| assets/logo_w.png | 사용자 첨부 UNION SOFT 흰색 로고 | 솔루션 브랜드 원본 보관 |
| assets/kiosk_01.jpg | 사용자 첨부 kiosk_01.jpg | 홈 솔루션 제안 카드에서 크롭 |

## 유니온소프트 공식 이미지
| 로컬 파일 | 원본 이미지 URL | 공식 설명 페이지 |
|---|---|---|
| assets/union-kiosk.jpg | https://www.unionpos.co.kr/default/img/hblock/content/vision3/img/kiosk_01.jpg | https://www.unionpos.co.kr/default/business/business_1.php?tit=02&sub=01 |
| assets/union-order.jpg | https://www.unionpos.co.kr/default/img/hblock/content/vision3/img/order_01.jpg | https://www.unionpos.co.kr/default/product/product_1.php?tit=03&sub=01 |
| assets/union-smart-order.png | https://www.unionpos.co.kr/default/img/hblock/content/vision3/img/tag_01.png | https://www.unionpos.co.kr/default/tag/tag.php?tit=04&sub=01 |

- 원본 각 1200×680px. 사진 속 화면·가격은 원본에 포함된 예시로 현재 계약 조건을 의미하지 않습니다.
- 파일 자체의 내용은 재생성하지 않았고 페이지 프레임에 맞춰 표시합니다. 썸네일 일부에서 CSS 크롭이 있을 수 있습니다.
- user 요청에 따라 원사이트 이미지를 리뉴얼 시안에 참고·사용했습니다. 별도 라이선스·사용 승낙 문서는 확인하지 않았습니다.
- 외부 서버 핫링크가 아니라 로컬 assets 파일을 제공합니다.

## AI 생성 컨셉 이미지
| 파일 | 제작 방식 | 사용상 주의 |
|---|---|---|
| assets/hero.jpg | openai-codex / chatgpt-image-generation으로 생성한 원본의 JPEG 파생본 | 실제 상품·납품 구성 보증 아님 |
| assets/product-vegetables.jpg | 같은 모델로 생성한 2×2 식품 이미지의 첫 사분면 | 샘플 신선농산 연출 |
| assets/product-pork.jpg | 위 원본의 둘째 사분면 | 실물 외관·원산지·규격 보증 아님 |
| assets/product-noodles.jpg | 위 원본의 셋째 사분면 | 샘플 면류 연출 |
| assets/product-tteokbokki.jpg | 위 원본의 넷째 사분면 | 실제 납품 구성을 뜻하지 않음 |

## 코드·파비콘·서체
- index.html, story.html, assets/styles.css, assets/story.css, assets/app.js: AI가 HTML/CSS/JS로 구현한 편집 가능한 코드.
- assets/favicon.svg, favicon.ico, assets/favicon-16.png, favicon-32.png, favicon-48.png, apple-touch-icon.png, icon-192.png, icon-512.png: 최종 제공 UNION MARKET 로고의 빨간 O 형상에서 파생, 아이보리 둥근 타일+빨간 O로 코드 제작. 새 로고 디자인이나 AI 이미지 생성물이 아닙니다.
- SVG의 O는 원형 경로로 재구성하고 PNG는 원본 빨간 O 크롭에서 제작했습니다. 작은 아이콘용 파생본으로 메인 로고 원본과 구분합니다.
- assets/font-400.woff2, font-600.woff2, font-800.woff2: Pretendard Regular/SemiBold/ExtraBold, Copyright 2021 Kil Hyung-jin. SIL Open Font License 1.1. assets/FONT-LICENSE.txt 참고.
- Pretendard 원본 CSS: https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.css
- FONT-LICENSE는 서체에 관한 라이선스이며 로고·사진·사이트 전체를 같은 라이선스로 재허락한다는 의미가 아닙니다.

## 문구 검증과 운영 전 경계
- 현행 공식 사이트의 솔루션 기능을 참고했습니다. 구사이트 회사 연혁·대표 정보는 현재 상태로 인용하지 않았습니다.
- 자동 발주·재고 API·유니온상회와 POS 직접 통합, 절감률·점유율·무료 설치·보증 조건을 주장하지 않습니다.
- 실제 판매 데이터·회원 정보·인증정보·서버 소스·결제 정보는 이 공개 시안에 포함하지 않습니다.

## 520×577 팝업 공지
- assets/renewal-popup-520x577.png: HTML/CSS 텍스트·최종 첨부 로고·기존 AI 식품 사진을 코드로 합성한 공지용 이미지입니다.
- 실제 개편 완료나 런칭일을 뜻하지 않으며 리뉴얼 준비 안내용입니다.

## 카테고리 아이콘 두 세트
- assets/category-icons/*-photo.png 9종: openai-codex / chatgpt-image-generation의 1254×1254 원본(photo-atlas.png)에서 크롭·여백·배경 가장자리 정돈 후 512px PNG로 내보냈습니다. 실제 촬영본이 아닙니다.
- assets/category-icons/*-illustration.svg 9종: SVG 코드 도형으로 제작, 동일 이름의 PNG 9종은 브라우저 캔버스로 512px 렌더링했습니다.
- photo-set.png, illustration-set.png는 글자 라벨이 포함된 1024px 전체 세트 미리보기입니다. 사진·일러스트 개별 파일에는 글자가 없습니다.
- 자세한 매핑과 사용 기준은 CATEGORY_ICONS.md를 참고하세요.
