# searcher-minter - Análise Detalhada

## 📋 Informações Gerais
| Campo | Valor |
|-------|-------|
| **Repositório** | searcher-minter |
| **Tipo** | Bot / Automação |
| **Visibilidade** | Privado 🔒 |

---

## 🎯 Descrição do Projeto

This repository contains a very simple demo application of [Flashbots](https://docs.flashbots.net), which allows arbitrary submission of a single transaction to Flashbots. This could be used for many simple purposes, but in the demonstration, the goal was to mint an NFT.

---

## 🛠️ Stack Tecnológica

### Linguagens Detectadas
- **JSON**: 37.5% (3 arquivos)
- **Markdown**: 25.0% (2 arquivos)
- **Solidity**: 25.0% (2 arquivos)
- **TypeScript**: 12.5% (1 arquivos)


### Frameworks e Bibliotecas
- Nenhum framework específico detectado

### Dependências (package.json)
- `@flashbots/ethers-provider-bundle`
- `ethers`

---

## 📁 Estrutura do Projeto

```
📄 ANALYSIS.md
📁 contracts/
📄 package-lock.json
📄 package.json
📄 README.md
📁 src/
📄 tsconfig.json
```

---

## 📖 README Original

# Flashbots searcher-minter

This repository contains a very simple demo application of [Flashbots](https://docs.flashbots.net), which allows arbitrary submission of a single transaction to Flashbots. This could be used for many simple purposes, but in the demonstration, the goal was to mint an NFT.

# Video Live Coding Demo

You can find a walkthrough of Flashbots and the creation of this NFT minting bot here:

[YouTube - Using Flashbots to Mint NFTs on Ethereum - Part 1](https://www.youtube.com/watch?v=1ve1YIpDs_I)

# How to run

Get some [Goerli](https://goerli.etherscan.io/) ETH on a wallet (you'll need a [faucet](https://faucet.goerli.mudit.blog/)). Extract that Goerli wallet's private key (in MetaMask `Account Details -> Export Private Key`), use that value below for `WALLET_PRIVATE_KEY`.

### Note:  It is EXTREMELY dangerous to deal with private keys in this manner, but bots require access to these keys to function. Be careful when using raw private keys that own mainnet ETH or other valuable assets. Keep as little value in these "hot" accounts as possible.

```shell
npm install
WALLET_PRIVATE_KEY=0x1d9af4................ npx ts-node src/index.ts
```

# Goerli Contract Addresses

* WasteGas: `0x957B500673A4919C9394349E6bbD1A66Dc7E5939`
* FakeArtMinter: `0x20EE855E43A7af19E407E39E5110c2C1Ee41F64D`

# Where can I learn more?

Check out [docs.flashbots.net](https://docs.flashbots.net).


---

## 🔗 Links

- **Repositório**: https://github.com/pedromello99/searcher-minter
- **Clone**: `git clone https://github.com/pedromello99/searcher-minter.git`

---

*Análise gerada automaticamente em 14/01/2026*
