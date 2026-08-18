# TCG코리아 (프로토타입)

포켓몬 카드·피규어 거래 플랫폼 프로토타입입니다. 단일 HTML 파일로 동작하며 외부 요청이 없습니다.

- 데모: https://pispherelab-admin.github.io/tcg-korea/
- 화면: 홈 / 마켓 / 상품 상세 / 시세표 / 내 도감 / 판매 등록 / 장바구니 / 마이페이지

## 데이터 출처

**최저 매물가는 실측값입니다.** 24개 품목의 가격을 2026-08-19에 SNKRDUNK 공개 상품 페이지에서 수집했습니다.
robots.txt가 Disallow 로 지정한 내부 API(`/en/v1/*`)는 사용하지 않았고, 사이트맵에 공개된 상품 페이지만 조회했습니다.

마켓가·기간 변동률·추이 그래프는 체결 로그 연동 전까지 **추정치**이며, 화면에도 `추정` 배지로 표시됩니다.
피규어는 SNKRDUNK 취급 품목이 아니라 샘플 데이터입니다.

글꼴은 [Pretendard](https://github.com/orioncactus/pretendard) (SIL OFL 1.1) 를 내장했습니다.
