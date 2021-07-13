======================================
### Download decployed contracts
======================================
Ethereum blockchain explorer: https://etherscan.io/
Blockchain ---> Verified Contracts

Usr: VerificationTester01
Pw: daxie-shandonghao-yangli-#

======================================
### Compiler versions
======================================
"MAJOR.MINOR.PATCH" - Book P235

Solidity treats:
  - MINOR: backward-incompatible changes
  - PATCH: backward-compatible features

===================================================================
### Using script to download verified contracts
===================================================================
Existing tools

  python3 download_verified_contract_from_etherscan.py
  python3 -m pip install pyquery
  python3 -m pip install xlrd
  python3 -m pip install xlwt

issue: Crawler does not work due to Cloudfare's security

===================================================================
### TODO: Snowballing - look into recent
===================================================================
forward snowballing - look into recent evaluation approaches

===================================================================
### Manually download all source code (Just Solidity, No Vyper)
===================================================================
Estimate: 4hr (not enough time to write a crawler)

# Contracts with Inheritance or multiple files (libraries, interface .etc):

https://etherscan.io/address/0xf7e40af830a2ecbfe72c5210c1ca272e3aa7ca1b#code
https://etherscan.io/address/0x4D06623610b6B784205881c1da326C663DDE874B#code
https://etherscan.io/address/0xD2A1C50601df0E0a37F2f915608098022d12EB92#code
https://etherscan.io/address/0x41965fE0A1c1FC70a81fcf50978621d0F3911CD9#code
https://etherscan.io/address/0x20FB5615b93d3dD78A4e6F02DbEE5764A4CbA354#code
https://etherscan.io/address/0x8aE465461F1f8BE1B316458352492D7113Ab7eDe#code
https://etherscan.io/address/0xd4d2779418671D8b305c3DBc25683E64489952D2#code
https://etherscan.io/address/0x278fD47a2121b63AB30f9FAbb41f056b7f8Ca709#code
https://etherscan.io/address/0x8aE465461F1f8BE1B316458352492D7113Ab7eDe#code
https://etherscan.io/address/0xb4747De7cc2F0A5f80A692D98A2b5e9089A485c8#code
https://etherscan.io/address/0x4e01E928f95BabaD1a6A19eD50635723b881363b#code   [42 files - Name: Helper]
https://etherscan.io/address/0x7fA6b601649771FCE4EBdF7C08570e7211e81823#code   [42 files - Name: Helper]
https://etherscan.io/address/0xD74054b66465166D01b0184191b729F2241D9FeB#code   [42 files - Name: Helper]
https://etherscan.io/address/0xf5F30EaF55Fd9fFc70651b13b791410aAd663846#code   [40 files]
https://etherscan.io/address/0x033524b1BA83CEABD8452C08dCAFe71966b9b3F6#code   [10 files]
https://etherscan.io/address/0x3546A3C5c5D2b11B74E3EE7CAD1d6b2ca8743587#code   [8 files]
https://etherscan.io/address/0x01b40EcC562395A479db214Ac559a4faCf147cDb#code   [10 files]
https://etherscan.io/address/0x3546A3C5c5D2b11B74E3EE7CAD1d6b2ca8743587#code   [8 files]
https://etherscan.io/address/0xe2fddf90052813e7f00e7ed2fc9271a31b7d5f24#code   [8 files]
https://etherscan.io/address/0xB6A54c66e25ca43c16eC589e8f8f34686436FCEd#code   [16 files]
https://etherscan.io/address/0x6c57F51f88b1898967734d8117c854C15810fF40#code   [40 files!]
https://etherscan.io/address/0x3fd1d77982ffce0703ef87e107d982647c7704e2#code   [15 files]
https://etherscan.io/address/0x4625c7049636da335df0f812ecfc8b0e3268d6f3#code   [19 files]
https://etherscan.io/address/0xBE9abbC5E86C0F2774Dc0D4d2d6d682dE90587f0#code   [9 files]
https://etherscan.io/address/0xce16E7ed7654a3453E8FaF748f2c82E57069278f#code   [28 files]
https://etherscan.io/address/0x94046274B5aA816aB236A9Eab42b5563B56E1931#code   [7 files]
https://etherscan.io/address/0x26941C63F4587796aBE199348ecd3d7C44F9aE0C#code   [10 files]
https://etherscan.io/address/0xB3295e739380BD68de96802F7c4Dba4e54477206#code   [8 files]
https://etherscan.io/address/0x404d396fc42e20d14585A1a10Cd64BDdC6C6574A#code   [8 files]
https://etherscan.io/address/0x7b4E77aa7062cE6b8a8A75514F6D2aD987c0d854#code   [17 files]
https://etherscan.io/address/0x9C3440F4aACA3312b632bE4A07C0f97B15c31c8b#code   [17 files]
https://etherscan.io/address/0xBcbD94007425001E9e2AEc764D799f83a257f050#code   [17 files]
https://etherscan.io/address/0x7e992d8f57223661106c29e519e22a2a9a7bcefb#code   [5 files]
https://etherscan.io/address/0x1Fb8638Dc4d1a26D5B53D14D92CB824a9e249f0A#code   [9 files]
https://etherscan.io/address/0x37d299eF5548BF19503Cb72C085799e331F9097d#code   [16 files]
https://etherscan.io/address/0x1Fb8638Dc4d1a26D5B53D14D92CB824a9e249f0A#code   [9 files]
https://etherscan.io/address/0xe634160eeb1e5667621b4fe328e89d9cb905235e#code   [5 files]
https://etherscan.io/address/0x72fCDDff1707f19d4d6a34833275ccafbaAf9724#code   [35 files]
https://etherscan.io/address/0xf7D0649139D8b14729E35c580c4c4236Ad3669c2#code   [6 files]
https://etherscan.io/address/0xf8317BD5F48B6fE608a52B48C856D3367540B73B#code   [23 files]
https://etherscan.io/address/0x9504b4ab8cd743b06074757d3B1bE3a3aF9cea10#code   [28 files]
https://etherscan.io/address/0x8c9d0e9d27fB15a96Cd8Ad714929502F4f1995Bf#code   [10 files]
https://etherscan.io/address/0x52E60e859fe0e1a36F3d4cbaE1e2d6953f4b83B3#code   [10 files]
https://etherscan.io/address/0x4F490F4835B3693A8874aee87D7CC242c25DCCAf#code   [8 files]
https://etherscan.io/address/0x7CAB80B6FaCD52A0F3e044D8bfC43d0ad6D258F4#code   [6 files]
https://etherscan.io/address/0x1Cd90FE6C072bA9bF9e4Ed3599a47a913A24d336#code   [5 files]
https://etherscan.io/address/0x038b104e914a8B64d9D704cAbb9C05C0dcF99a4c#code   [8 files]
https://etherscan.io/address/0x518B7df876F08d1848390cf5D54d99f29c170e50#code   [12 files]
https://etherscan.io/address/0x7828a0Ebf09B068c6B6aDA0F739bD1b961205157#code   [19 files]
https://etherscan.io/address/0x975a7574713E77E5f7Ea990Cee1f2941440A5619#code   [12 files]
https://etherscan.io/address/0xe7B0D6A9943bB8CD8cd323368450AD74474bB1b7#code   [10 files]
https://etherscan.io/address/0xC43767F4592DF265B4a9F1a398B97fF24F38C6A6#code   [21 files]
https://etherscan.io/address/0x33d25049B38cE24D5E515FDCb090055C61a120C6#code   [4 files]
https://etherscan.io/address/0x8d513E6552aae771CaBD6b2Bf8875A8A2e38f19f#code   [20 files]
https://etherscan.io/address/0x57A0B07dcD834cAbB844BEc8E7903A3B2faE6245#code   [11 files]
https://etherscan.io/address/0x827f6cBfe9230A7Daa000057CDb5a26DcdE77Bec#code   [23 files]
https://etherscan.io/address/0xea58e5c9DbF9232C18E8c5124674d1888d3aE725#code   [17 files]
https://etherscan.io/address/0x3fa10a0c0c943ca0262e5364004afa489727eeb7#code   [27 files]
https://etherscan.io/address/0xa1D1f9Da6e031Da44f7f695B974d67C93fD31A63#code   [13 files]
https://etherscan.io/address/0x115c27f8F166C7Ce8a7495c1f5d77CDf1a1884BD#code   [13 files]
https://etherscan.io/address/0xacDcB03E219F7227c2074FBBd9b7e7e1C7d18e20#code   [19 files]
https://etherscan.io/address/0x31C893843685f1255A26502eaB5379A3518Aa5a9#code   [28 files]
https://etherscan.io/address/0x759704b23a25bC8cdb90859D9D99Fe45a58031A4#code   [40 files]
https://etherscan.io/address/0x48531836E57BC28D6FEe33840F43826b889AA2fc#code   [22 files]
https://etherscan.io/address/0x5E4700C6610113077ea0413b48fC35f7cC953618#code   [9 files]
https://etherscan.io/address/0x987BE6b46b13bab33EE55C0ff9bB2aF0A13F01CF#code   [13 files]
https://etherscan.io/address/0x75224b0f245fe51d5bf47a898dbb6720d4150ba7#code   [15 files]
https://etherscan.io/address/0x990732be7287eaa06d382a0da5daaeb3657bf502#code   [10 files]
https://etherscan.io/address/0x35678f38d34ab2f1d2ef10b853c1254024d604d9#code   [10 files]
https://etherscan.io/address/0x1EaDB459de4d1Ba737255FE51cCBb996a738d2C9#code   [10 files]
https://etherscan.io/address/0x8bF4326936cDaa71015e7d73fB1B1d7A0Db4A37e#code   [9 files]
https://etherscan.io/address/0xc2667F0e7529ca8b3Dfb8f4f19ef1E28eD71F15D#code   [18 files]
https://etherscan.io/address/0x6E6490F3Fb3F312F2B68A8Aac84d4d2034517b00#code   [18 files]
https://etherscan.io/address/0x339b20136282a9De3A6fc448b5bA9534116b3B08#code   [10 files]
https://etherscan.io/address/0xCC91c91f9539dA6b1637653Cda1b5Cc50Cc7696B#code   [26 files]
https://etherscan.io/address/0x8fea3153C5fCD9fA8626aD71888E97A03d4411B7#code   [7 files]
https://etherscan.io/address/0xA51AcF8416bd0F8B5ef5f0f94CAF7aD9A332a6eD#code   [14 files]
https://etherscan.io/address/0xfe97FC5D8cF529dFB8eC557dA68651D7adC45601#code   [10 files]
https://etherscan.io/address/0xACd3CF818EFe8ddce84C585ddCB147c4C844D3b3#code   [15 files]
https://etherscan.io/address/0xb55088e553ddeb711a914b4c698e9582cd6d3ac3#code   [6 files]
https://etherscan.io/address/0x8826E104f4c23Ee98714d64EBF9769410e5776FA#code   [8 files]
https://etherscan.io/address/0xaf1da175cf30d036b53d1e94c3173a78a5a59e7f#code   [18 files]
https://etherscan.io/address/0x7f509465c38b66bdecec2cfdc842e11809cc8357#code   [18 files]
https://etherscan.io/address/0xfEd73093CB583c8593719C28285e62422f1C4bAd#code   [5 files]
https://etherscan.io/address/0x00f0fEED50926c27261dF37f7bCcC519d87525D0#code   [2 files]
https://etherscan.io/address/0x13df7973eA203868Af66fCffd86FE8cB63EDd378#code   [15 files]
https://etherscan.io/address/0x00F0FeEd50354E22370F3523897081E3D994DAe6#code   [5 files]
https://etherscan.io/address/0x8f496D935A356077fAA40417881826939bCD5632#code   [16 files]
https://etherscan.io/address/0xeE99cc7b1914b50F04CB5db8Cf3523A1C55e8A52#code   [23 files]
https://etherscan.io/address/0xaBC64889601F01e7B26277Ef8756250d6ABf8c18#code   [10 files]
https://etherscan.io/address/0x83e031005ecb771b7ff900b3c7b0bdde7f521c08#code   [19 files]
https://etherscan.io/address/0x863ad391091ae0e87b850c2bb7bfc7597c79c93f#code   [19 files]
https://etherscan.io/address/0xEe8Ec5D6e709CDaE62D3859e759fa779a689D9Fe#code   [13 files]
https://etherscan.io/address/0x17D6E670eE8eF8464caFc098bF20668987012330#code   [7 files]
https://etherscan.io/address/0xCc1D4dD8704f83d48c450c4709Fe9D7F013F2B37#code   [13 files]
https://etherscan.io/address/0x54B197d7F326AC5C9DBc848A01e1f1A16eC94A19#code   [2 files]
https://etherscan.io/address/0x684bA90127cEBDe04EB65fE7cb2B03f346e6e35f#code   [3 files]
https://etherscan.io/address/0x9217c19e72e4ab9e1015ebe9098285a6ef1761c3#code   [12 files]
https://etherscan.io/address/0x9fd8Ef3251dB005a232E1D087fd0aB68e94858Fe#code   [18 files]
https://etherscan.io/address/0x7C621229fB0293ef8A4f5cAa79a8bB4D60BF5ca4#code   [7 files]
https://etherscan.io/address/0xD144A77C1Eec8c8f3719fc681e60c903fc75EC47#code   [12 files]
https://etherscan.io/address/0x57eA7178505F7d33C2bdB4450E041561513dBD9B#code   [23 files]



# Contracts with duplicate names:

"HelloERC20" https://etherscan.io/searchcontractlist?q=HelloERC20&a=all&ps=10&p=1
"BOFA"       https://etherscan.io/searchcontractlist?q=BOFA&a=all
"Address"    https://etherscan.io/searchcontractlist?q=Address&a=all
"CloneRewarderTime" https://etherscan.io/searchcontractlist?q=CloneRewarderTime&a=all
"PassiveStrategy"   https://etherscan.io/searchcontractlist?q=PassiveStrategy&a=all
"EthereumLondon"    https://etherscan.io/searchcontractlist?a=all&q=EthereumLondon   [2 contracts]
"PaymentSplitter"   https://etherscan.io/searchcontractlist?q=PaymentSplitter&a=all  [>= 10 contracts]
"TokenDistributor"  https://etherscan.io/searchcontractlist?a=all&q=TokenDistributor
"Astroape"          https://etherscan.io/searchcontractlist?q=Astroape&a=all
"Takita"            https://etherscan.io/searchcontractlist?q=Takita&a=all   [2 contracts]
"PriceOracle"       https://etherscan.io/searchcontractlist?q=PriceOracle&a=all
"Operator"          https://etherscan.io/searchcontractlist?q=Operator&a=all
"RestrictedToken"   https://etherscan.io/searchcontractlist?q=RestrictedToken&a=all
"UniswapExchange"   https://etherscan.io/searchcontractlist?q=UniswapExchange&a=all&ps=10&p=1
"INVENToken"        https://etherscan.io/searchcontractlist?q=INVENToken&a=all
"CBOR"              https://etherscan.io/searchcontractlist?q=CBOR&a=all        [>= 100 contracts]
"Strategy"          https://etherscan.io/searchcontractlist?q=Strategy&a=all    [>= 100 contracts]
"SimpleERC20"       https://etherscan.io/searchcontractlist?q=SimpleERC20&a=all [>= 100 contracts]
"CommonERC20"       https://etherscan.io/searchcontractlist?q=CommonERC20&a=all [>= 10 contracts]
"StrategyCompLevUsdc"  https://etherscan.io/searchcontractlist?q=StrategyCompLevUsdc&a=all  [>= 5 contracts]
"NFTXStakingZap"       https://etherscan.io/searchcontractlist?q=NFTXStakingZap&a=all       [2 contracts]
"NFTXVaultUpgradeable" https://etherscan.io/searchcontractlist?q=NFTXVaultUpgradeable&a=all [5 contracts]
"CrowdfundEditions"    https://etherscan.io/searchcontractlist?q=CrowdfundEditions&a=all    [2 contracts]
"PassiveStrategy"      https://etherscan.io/searchcontractlist?q=PassiveStrategy&a=all      [8 contracts]

# Contracts written in Vyper:

"Vyper_contract" https://etherscan.io/address/0x9582C4ADACB3BCE56Fea3e590F05c3ca2fb9C477#code
"Vyper_contract" https://etherscan.io/address/0x8a90faDe80feadCDD595c4f3611eB1886c924b61#code
"Vyper_contract" https://etherscan.io/address/0x09f15F979Bf1b0CC8c8a19ed2E2feFF8EdE60e54#code
"Vyper_contract" https://etherscan.io/address/0x7F129B99d81e5ac772B24BFb6af2f71309851F4C#code
"Vyper_contract" https://etherscan.io/address/0x55Ece7dC08f1950245102aD92968bDaE1b359A0a#code
"Vyper_contract" https://etherscan.io/address/0xffd51A24C65CC6981F3A543320fDadaf57ffFD7A#code
