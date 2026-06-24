# 경매 낙찰가 계산기

경매 입찰 전 감정가, 희망 매도가, 대출, 취득비용, 보유비용, 양도비용을 입력해 입찰가율별 세후 순수익과 수익률을 비교하는 정적 웹 계산기입니다.

## 주요 기능

- 사건번호별 저장, 불러오기, 삭제
- 금액 입력 자동 쉼표 표시
- 취득세, 법무비, 양도세, 중개수수료 금액/% 연동
- 세후 순수익 플러스/마이너스 색상 표시
- GitHub Pages 배포 가능

## 파일

- `index.html`: GitHub Pages 기본 진입 파일
- `auction-bid-calculator.html`: 계산기 본문
- `.nojekyll`: GitHub Pages 정적 배포 보조 파일

## 실행

브라우저에서 `index.html` 또는 `auction-bid-calculator.html`을 열면 됩니다. 별도 서버나 설치가 필요 없습니다.

## 저장 기능

사건번호별 저장은 브라우저의 `localStorage`를 사용합니다. 같은 브라우저에서 다시 열면 저장된 사건을 불러올 수 있습니다.

## GitHub Pages 배포

1. 새 GitHub 저장소를 만듭니다.
2. 이 폴더의 파일 전체를 저장소에 올립니다.
3. 저장소의 `Settings > Pages`에서 `Deploy from a branch`를 선택합니다.
4. `Branch`는 `main`, 폴더는 `/ root`로 설정합니다.
5. 저장 후 표시되는 GitHub Pages 주소로 접속합니다.

## 주의

세금, 대출 가능액, 법무비, 중개수수료는 실제 조건에 따라 달라질 수 있습니다. 이 계산기는 입찰 전 빠른 비교용입니다.
