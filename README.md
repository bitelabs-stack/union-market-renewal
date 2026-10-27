# 유니온상회 리뉴얼 준비 시안

- 홈: https://bitelabs-stack.github.io/union-market-renewal/
- 유니온 이야기: https://bitelabs-stack.github.io/union-market-renewal/story.html

이번 작업은 운영몰 반영이 아닌 리뉴얼 준비·디자인 검토용입니다.

## 파일 구조
```text
index.html
story.html
favicon.ico
site.webmanifest
assets/
  styles.css / story.css / app.js
  market-logo.png / market-logo-white.png
  logo.png / logo_w.png (UNION SOFT 솔루션 전용)
  식품·기기 사진 / 서체 / 파비콘 이미지
DESIGN_GUIDE.md
ASSET_SOURCES.md
```

## 왜 이전에는 assets 폴더가 없었나요?
첫 배포는 이미지·폰트·CSS·JS를 HTML 내부에 포함한 단일 파일이었습니다. 에셋이 누락된 상태가 아니어서 페이지는 정상 표시됐지만, 파일별 관리와 캐시에는 불리했습니다. 이번 버전은 실제 assets 폴더에 모두 분리하고 상대 경로로 연결했습니다.

## 이번 보강
- 기존 유니온상회 9개 카테고리 보존, 음료·주류 추가 반영
- 별도 유니온 이야기 페이지에 공식 키오스크·유니온오더·스마트오더 소개
- 공식 이미지 로컬 보관과 출처 문서화
- 제공 로고 기반 SVG·ICO·PNG 파비콘 및 manifest

## 범위
홈의 샘플 검색·분류·정렬·찜·상세·장바구니만 작동합니다. 실제 로그인·주문·결제·발주·재고 연동은 없습니다. 식품 사진·가격·규격은 시안 예시이며 기기 기능은 공식 설명과 도입 조건을 확인해야 합니다.

## 문서
- [디자인 가이드](DESIGN_GUIDE.md)
- [이미지·코드·서체 출처](ASSET_SOURCES.md)
- [배포 정보](DEPLOYMENT.md)

로고·사진은 각 권리자의 자료입니다. Pretendard에만 OFL 1.1을 적용하며 assets/FONT-LICENSE.txt를 함께 보관합니다.

## 새단장 안내 이미지
- [520×577 PNG](assets/renewal-popup-520x577.png)
- [팝업 시안 미리보기](popup-preview.html)
- 최종 메인 로고는 사용자가 정정 제공한 UNION MARKET이며 UNION SOFT와 구분합니다.

## 카테고리 아이콘 두 가지 스타일
- [사진형·일러스트형 비교](category-icons.html)
- [전체 에셋 폴더](assets/category-icons/)
- [규격·파일 매핑·제작 출처](CATEGORY_ICONS.md)
- 사진형 9종 PNG, 일러스트형 9종 SVG+PNG를 추가했습니다. 현재 홈 아이콘은 자동 교체하지 않았습니다.
