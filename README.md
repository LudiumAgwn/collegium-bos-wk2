# Collegium-BOS-WK2

## 주제: dApp 다뤄보기
이번 주제는 금융 서비스를 Ethereum 네트워크 상에서 제공하는 DeFi 중에 하나인 Liquity 프로토콜을 다룹니다.

## 1. 온라인 에디터 환경 접속하기
1. [nearpad 편집기](https://nearpad.dev/editor) 사이트에 접속해주세요.

## 2. LiquityOpenTrove 컴포넌트 불러오기
1. [LiquityOpenTrove.jsx](assets/code/liquityOpenTroveSepolia.jsx) 파일의 코드를 복사해주세요
2. nearpad 편집기에 붙여넣기 해주세요.

## 3. LiquityOpenTrove 코드 뜯어보기

## 4. 컨트랙트 실행하기
1. openTrove

2. closeTrove

3. Etherscan에서 트랜잭션 확인하기
## Mission
- [ ] `openTrove`가 성공한 지갑은 `closeTrove`가 실행되기 전까지 `이 지갑은 이미 활성화된 트로브가 있습니다.` 메세지를 표시해주세요.
- [ ] `borrowWrapper` 컴포넌트의 스타일을 외부 css파일을 불러와서 적용해보세요.
    - hint 1: fetch API를 사용하세요.
    - hint 2: 이 주소에서 불러와주세요.
- [ ] `openTrove` 기능의 가스 비용을 최적화 하기 위해 NICR이라는 값을 계산해야 합니다. openTrove 함수에 NICR을 계산하는 기능을 추가해주세요.
    - NICR = Ether / LUSD * 100
    - hint 1: `ethers.js` api 기능을 사용해서 계산해주세요