<img width="1317" alt="image" src="https://github.com/user-attachments/assets/d72ba1af-9ca6-4e66-8e03-2cf5da7ad398">



<h3> 🎨 NFT minitng 서비스, NFTLIX-NFT-MINT </h3>   

- metadata 기반 nft minting API


## 🪄 Usage
### 1. root directory에 .env 파일 생성
```bash
API_URL=your-sepolia-api-url
PRIVATE_KEY=your-metamask-private-key
PUBLIC_KEY=your-metamask-public-key
```

### 2. NFT mint
```bash
npm install
node /scripts/mint-nft.js https://your-metadata-url.com
```

## 🚨 유의사항
현재 테스트 metamask 지갑으로 nft가 minting되도록 설정되어 있습니다.   
다른 metamask 지갑을 사용하려면 `scripts/mint-nft.js`의 `contractAddress`를 수정하면 됩니다.
