# OpenSea-Seaport
![openSea-seaport-image](https://github.com/cyberlawd/OpenSea-SeaPort/blob/main/Seaport.jpeg)

# Full OpenSea-Seaport implementation
## Frontend and Backend Development
### If you have questions or need any help, Message me here: [@cyber_lawd](https://t.me/cyber_lawd) 

[OpenSea-Seaport](https://github.com/cyberlawd/OpenSea-SeaPort) is a brand new, open-source, web 3.0 marketplace protocol that enables buying and selling of NFTs safely and efficiently . Launched first on Ethereum, Seaport has helped create a better, more feature-rich experience for our community, while lowering the cost to use web 3.0 marketplaces, like OpenSea. So this is the full implementation of the framework for educational purpose only.

This framework is written using Python [Django](https://github.com/encode/django-rest-framework) [Typescript](https://github.com/microsoft/TypeScript) and uses [Next.js](https://github.com/vercel/next.js) as framework. The packages that are being used include [Hardhat](https://github.com/NomicFoundation/hardhat) (Ethereum dev environment), [Vanilla-extract](https://github.com/seek-oss/vanilla-extract) (styling), [Zustand](https://github.com/pmndrs/zustand) (global state management), [SWR](https://github.com/vercel/swr) (database fetching) and [Wagmi](https://github.com/wagmi-dev/wagmi) (blockchain fetching). To simplify writable nested serializers package [drf-writable-nested](https://github.com/beda-software/drf-writable-nested) was used also.

### Installation

1. Install Docker

2. Install a web3-provider, Just like [MetaMask](https://github.com/MetaMask/metamask-extension).

3. Open a [(CLI) Command Line Interface](https://en.wikipedia.org/wiki/Command-line_interface) and clone this repository:

```bash
git clone https://github.com/cyberlawd/OpenSea-SeaPort.git
```

4. Inside the repository, execute the following command to install the dependencies:

```bash
yarn install
```

### Getting Started

1. Inside the repository, run the following command to make the docker image and run the container:

```bash
docker-compose up
```

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
