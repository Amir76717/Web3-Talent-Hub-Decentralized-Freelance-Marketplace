# Web3-Talent-Hub-Decentralized-Freelance-Marketplace
Web3 Talent Hub is an innovative decentralized platform designed to connect freelancers with opportunities in the rapidly growing Web3 space. Built using cutting-edge technologies such as Next.js, Chakra UI, and smart contracts, this platform facilitates a transparent, efficient, and secure marketplace environment.

<p align="center"> <a href="https://gigiblock-social-hour-web3.vercel.app/" target="_blank"><img src="https://github.com/SabeloMkhwanzi/Gigiblock-social-hour-web3/blob/main/public/gigiblock-logo.png" alt="Web3 Talent Hub Logo"/></a> </p>

# Problems We Are Solving
Web3 Talent Hub addresses several critical challenges within the traditional freelance marketplace:

**1. High Fees and Slow Payments:** We eliminate excessive commission charges and expedite the payment process, reducing financial burdens on freelancers and clients.

**2. Limited Project Accessibility:** Unlike traditional platforms that focus on large projects, our platform welcomes a diverse range of project sizes, ensuring opportunities for all skill levels.

**3. Cumbersome Application Processes:** Our system simplifies the application process, allowing freelancers to easily apply without navigating through multiple external sites.

**4. Complex User Interfaces:** We streamline user interactions, providing a clean and intuitive interface that eliminates common annoyances like spam and fraudulent listings.

**5. Inefficient Selection Procedures:** Our platform reduces the time and complexity traditionally involved in hiring and project selection, minimizing service fees and maximizing efficiency.

#### How its work

- We created a smart contract that allows a client to mint opened projects or skilled person to mint their information of career.
- Unstoppable domain to login users or RainbowKit
- That data is minted on the Polygon testnet, and than its store on a decentralized manner using IPFS and Nft.Storage.
- Infomation is visiable to public, no extensive screening proces and Lengthy selection process, we are using the blockchain to pay only for gas fees on Polygon to process application and posted projects.
- We than select our field of intrest or the talent for our project - Using XMTP (Extensible Message Transport Protoco) a open protocol and network for secure and private web3 messaging to connect and get more information on the applicants or the company - by only using you chain address to communicate.

#### Building Stack

- Building Framework: [Nextjs](https://nextjs.org/) -Next.js is an open-source web development framework created by Vercel enabling React-based web applications with server-side rendering and generating static websites
- Frontend: [Chakra-ui](https://chakra-ui.com/) - Create accessible React apps with speed
- Hosting Platform: [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.
- Smart Contract: [hardhats](https://hardhat.org/docs) - Hardhat is a development environment for Ethereum software
- Decentralized Storage: IPFS and NFT.Storage to client occauption matadata info: [IPFS/Filecoin](https://ipfs.io/) - A peer-to-peer hypermedia protocol designed to preserve and grow humanity's knowledge by making the web upgradeable, resilient, and more open.
- Matedata Storage: [NFT.Storage](https://nft.storage/) is a long-term storage service designed for off-chain NFT data (like metadata, images, and other assets) for up to 31GiB in size per individual upload.
- Web3 Messaging: [XMTP](https://xmtp.org/) (Extensible Message Transport Protocol) is an open protocol and network for secure and private web3 messaging.
- Unstoppable domain to login users: [Unstoppable domain](https://docs.unstoppabledomains.com/) - Login with Unstoppable build a universal Web3 login that authenticates your users.

### Project Feature

##### 1. Home Page

![HomePage](https://github.com/SabeloMkhwanzi/Gigiblock-social-hour-web3/blob/main/public/GigiBlock%20updated%20version.png)

#### 2. Find work Page

![FindworkPage](https://github.com/SabeloMkhwanzi/Gigiblock-social-hour-web3/blob/main/public/GigiBlock%20updated%20version2.png)

#### 3. Find Talent Page

![FindTalentPage](https://github.com/SabeloMkhwanzi/Gigiblock-social-hour-web3/blob/main/public/GigiBlock%20updated%20version3.png)

#### Running the app

### Getting Started

First, clone the repo with the following git command:

```bash
git clone https://github.com/SabeloMkhwanzi/Gigiblock-social-hour-web3
```

Second, open a terminal in the root directory of the project and run:

```bash
npm install
```

to install all the package dependencies for the project

Create a .env file in the root folder and populate it with the following variables: Get Api a key from [Nft.Storage](https://nft.storage/) and [Unstoppable domain](https://docs.unstoppabledomains.com/)

```bash
NEXT_PUBLIC_NFTSTORAGE_KEY=
NEXT_PUBLIC_UNSTOPPABLEDOMAIN_CLIENT_ID=

```

Finally, run the development server:

```bash
npm run dev
# or
yarn dev
```

Happy Hacking!😊
