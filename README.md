# 동대문 발주 & 입고 리스트 웹페이지

엑셀 `동대문 발주&입고 리스트.xlsx` 데이터를 보기 편하게 정리한 GitHub Pages용 정적 웹페이지입니다.

## 파일 구성

- `index.html` : 화면/디자인/검색/필터 기능
- `data.js` : 엑셀에서 추출한 발주·입고 데이터

## GitHub Pages 공유 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더 안의 `index.html`, `data.js`, `README.md`를 저장소 루트에 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment**에서 `Deploy from a branch` 선택
5. Branch는 `main`, 폴더는 `/root` 선택 후 저장합니다.
6. 잠시 후 표시되는 GitHub Pages 주소로 공유하면 됩니다.

## 현재 데이터 요약

- 총 발주수량: 79
- 총 입고수량: 0
- 총 미입고수량: 79
- 업체수: 11
- 상품수: 16
- 데이터 생성: 2026-07-02 11:30:54 KST

## 이후 엑셀 데이터가 바뀔 때

현재 버전은 `data.js`에 데이터가 들어가 있습니다. 엑셀을 다시 반영하려면 새 데이터로 `data.js`만 교체하면 됩니다.
