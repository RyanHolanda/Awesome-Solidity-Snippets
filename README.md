# Awesome Solidity Snippets

Awesome Solidity Snippets is a collection of codes commonly used for Smart Contract Development with Solidity. This include imports, Contracts, Libraries and much more.

## Requirements

VSCode `^1.88.0`\
Solidity `^0.8.0`

## Features

• Speeds up development.\
• Eliminates the need of Copy and Paste.\
• Support imports from multiple providers, such as Chainlink and OpenZeppelin.

<img src="images/showcase.gif" alt="drawing" height="350"/>

## Foundry Compatibility

If you are using Foundry, in order to use the import snippets, make sure you have remappings set

## Known Issues

At this time, there are no known issues. If you discover a bug or would like a new snippet, feel free to create a pull request at our GitHub page.

## Snippets

### Chainlink Snippets

#### _General Snippets_

| Shortcut                | Expanded                         | Description                                      |
| ----------------------- | -------------------------------- | ------------------------------------------------ |
| `importFeedRegistryI`   | Import Feed Registry Interface   | Import Feed Registry Interface from @chainlink   |
| `importDenominations`   | Import Denominations             | Import Denominations Library from @chainlink     |
| `feedRegistry`          | Feed Registry                    | Create Feed Registry Contract using @chainlink   |
| `importLinkTokenI`      | Import Link Token Interface      | Import Link Token Interface from @chainlink      |
| `importerc677receiverI` | Import ERC677 Receiver Interface | Import ERC677 Receiver Interface from @chainlink |

#### _Access_

| Shortcut               | Expanded               | Description                                                   |
| ---------------------- | ---------------------- | ------------------------------------------------------------- |
| `importConfirmedOwner` | Import Confirmed Owner | Import Confirmed Owner Contract from @chainlink               |
| `confirmedOwner`       | Confirmed Owner        | Create Confirmed Owner Contract using @chainlink Dependencies |

#### _Automation_

| Shortcut                         | Expanded                                   | Description                                                              |
| -------------------------------- | ------------------------------------------ | ------------------------------------------------------------------------ |
| `importStreamsLookupCompatibleI` | Import Streams Lookup Compatible Interface | Import Streams Lookup Compatible Interface using @chainlink Dependencies |
| `streamsLookupCompatibleI`       | Streams Lookup Compatible Interface        | Create Streams Lookup Compatible Interface using @chainlink Dependencies |
| `importLogAutomationI`           | Import Log Automation Interface            | Import Log Automation Interface from @chainlink                          |
| `importAutomationCompatibleI`    | Import Automation Compatible Interface     | Import Automation Compatible Interface from @chainlink                   |
| `logAutomation`                  | Log Automation                             | Create Log Automation Contract using @chainlink dependencies             |
| `automationCompatible`           | Automation Compatible                      | Create Automation Compatible Contract using @chainlink dependencies      |

#### _CCIP_

| Shortcut               | Expanded                       | Description                                    |
| ---------------------- | ------------------------------ | ---------------------------------------------- |
| `importRouterClientI`  | Import Router Client Interface | Import Router Client Interface from @chainlink |
| `importCCIPReceiver`   | Import CCIP Receiver           | Import CCIP Receiver Contract from @chainlink  |
| `importOwnerIsCreator` | Import OwnerIsCreator          | Import OwnerIsCreator Contract from @chainlink |
| `importClientLibrary`  | Import Client Library          | Import Client Library from @chainlink          |
| `ccipReceiver`         | CCIP Receiver                  | Create CCIP Receiver Contract using @chainlink |

#### _Data Feeds_

| Shortcut                | Expanded                          | Description                                     |
| ----------------------- | --------------------------------- | ----------------------------------------------- |
| `importAggregatorV3I`   | Import Aggregator V3 Interface    | Import AggregatorV3 Interface from @chainlink   |
| `importAggregatorV2V3I` | Import Aggregator V2 V3 Interface | Import AggregatorV2V3 Interface from @chainlink |

#### _Functions_

| Shortcut                     | Expanded                      | Description                                                    |
| ---------------------------- | ----------------------------- | -------------------------------------------------------------- |
| `importFunctionsClient`      | Import Functions Client       | Import Functions Client Contract from @chainlink               |
| `importFunctionsRequest`     | Import Functions Request      | Import Functions Request Library from @chainlink               |
| `functionsRequestForRequest` | Functions Request For Request | Use Functions Request Library for Request type                 |
| `functionsClient`            | Functions Client              | Create Functions Client Contract using @chainlink dependencies |

#### _Data Streams_

| Shortcut                    | Expanded                              | Description                                           |
| --------------------------- | ------------------------------------- | ----------------------------------------------------- |
| `importCommon`              | Import Common                         | Import Common Library from @chainlink                 |
| `importRewardManagerI`      | Import Reward Manager Interface       | Import Reward Manager Interface from @chainlink       |
| `importVerifierFeeManagerI` | Import Verifier Fee Manager Interface | Import Verifier Fee Manager Interface from @chainlink |

#### _Mocks_

| Shortcut                     | Expanded                      | Description                                    |
| ---------------------------- | ----------------------------- | ---------------------------------------------- |
| `importMockVRFCoordinatorV2` | Import Mock VRFCoordinator V2 | Import VRF Coordinator V2 Mock from @chainlink |
| `importMockV3Aggregator`     | Import Mock V3 Aggregator     | Import V3 Aggregator Mock from @chainlink      |
| `importMockLink`             | Import Mock Link              | Import Mock Link Token from @chainlink         |
| `importMockERC20`            | Import Mock ERC20             | Import Mock ERC20 from @chainlink              |

#### _VRF_

| Shortcut                         | Expanded                            | Description                                                                |
| -------------------------------- | ----------------------------------- | -------------------------------------------------------------------------- |
| `importVRFConsumerBaseV2`        | Import VRF Consumer Base V2         | Import VRF Consumer Base V2 Contract from @chainlink                       |
| `importVRFCoordinatorV2I`        | Import VRF Coordinator V2 Interface | Import VRF Coordinator V2 Interface from @chainlink                        |
| `importVRFV2Wrapper`             | Import VRF V2 Wrapper               | Import VRF V2 Wrapper Contract from @chainlink                             |
| `importVRFV2WrapperConsumerBase` | Import VRF V2 Wrapper Consumer Base | Import VRF V2 Wrapper Consumer Base Contract from @chainlink               |
| `vrfConsumerBaseV2`              | VRF Consumer Base V2                | Create VRF Consumer Base V2 Contract from @chainlink                       |
| `vrfV2WrapperConsumerBase`       | VRF V2 Wrapper Consumer Base        | Create VRF V2 Wrapper Consumer Base Contract using @chainlink dependencies |

### Echidna

#### _General Snippets_

| Shortcut      | Expanded     | Description                  |
| ------------- | ------------ | ---------------------------- |
| `echidnaTest` | Echidna Test | Create Echidna Test Contract |
| `testEchidna` | Test Echidna | Create Echidna Test Function |

### Foundry

#### _Scripts_

| Shortcut              | Expanded              | Description                                |
| --------------------- | --------------------- | ------------------------------------------ |
| `importFoundryScript` | Import Foundry Script | Import Script contract from Forge          |
| `foundryScript`       | Foundry Script        | Create Script contract using Foundry Tools |

#### _Tests_

| Shortcut                 | Expanded                 | Description                                  |
| ------------------------ | ------------------------ | -------------------------------------------- |
| `importFoundryTest`      | Import Foundry Test      | Import Foundry Test contract from Forge      |
| `importFoundryInvariant` | Import Foundry Invariant | Import Foundry Invariant contract from Forge |
| `foundryTest`            | Foundry Test             | Create Foundry Test contract                 |
| `foundryInvariant`       | Foundry Invariant        | Create Foundry Invariant contract            |
| `foundryInvariantTest`   | Froundry Invariant Test  | Create Foundry Invariant Test contract       |
| `itest`                  | Invariant test           | Create Foundry Invariant Test Function       |
| `test`                   | Test                     | Create Foundry Test Function                 |

### Hardhat

#### _General Snippets_

| Shortcut               | Expanded               | Description                         |
| ---------------------- | ---------------------- | ----------------------------------- |
| `importHardhatConsole` | Import Hardhat Console | Import Hardhat console from Hardhat |

### OpenZeppelin

#### _Access_

| Shortcut                                | Expanded                                            | Description                                                                   |
| --------------------------------------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| `importOwnable`                         | Import Ownable                                      | Import Ownable contract from @openzeppelin                                    |
| `importOwnable2s`                       | Import Ownable 2 Step                               | Import Ownable 2 Step contract from @openzeppelin                             |
| `importAccessControlI`                  | Import Access Control Interface                     | Import Access Control Interface from @openzeppelin                            |
| `importAccessControl`                   | Import Access Control                               | Import Access Control contract from @openzeppelin                             |
| `importAccessControlEnumerableI`        | Import Access Contol Enumerable Interface           | Import Access Control Enumerable Interface from @openzeppelin                 |
| `importAccessControlEnumerable`         | Import Access Control Enumerable                    | Import Access Control Enumerable contract from @openzeppelin                  |
| `importAccessControlDefaultAdminRulesI` | Import Access Control Default Admin Rules Interface | Import Access Control Default Admin Rules Interface from @openzeppelin        |
| `importAuthorityI`                      | Import Authority Interface                          | Import Authority Interface from @openzeppelin                                 |
| `importAccessManagerI`                  | Import Access Manager Interface                     | Import Access Manager Interface from @openzeppelin                            |
| `importAccessManagedI`                  | Import Access Managed Interface                     | Import Access Managed Interface from @openzeppelin                            |
| `importAccessManaged`                   | Import Access Managed                               | Import Access Managed contract from @openzeppelin                             |
| `importAuthorityUtils`                  | Import Authority Utils                              | Import Authority Utils Library from @openzeppelin                             |
| `ownable`                               | Ownable                                             | Create an Ownable contract using @openzeppelin dependencies                   |
| `ownable2Step`                          | Ownable 2 Step                                      | Create an Ownable contract using @openzeppelin dependencies                   |
| `accessControl`                         | Access Control                                      | Create an Access Control contract using @openzeppelin dependencies            |
| `accessControlEnumerable`               | Access Control Enumerable                           | Create an Access Control Enumerable contract using @openzeppelin dependencies |
| `accessManager`                         | AccessManager                                       | Create an Access Manager contract using @openzeppelin dependencies            |
| `accessManaged`                         | Access Managed                                      | Create an Access Managed contract using @openzeppelin dependencies            |

#### _Base 64_

| Shortcut       | Expanded       | Description                              |
| -------------- | -------------- | ---------------------------------------- |
| `importBase64` | Import Base 64 | Import Base64 library from @openzeppelin |

#### _Enumerable Map_

| Shortcut                           | Expanded                               | Description                                       |
| ---------------------------------- | -------------------------------------- | ------------------------------------------------- |
| `importEnumerableMap`              | Import Enumerable Map                  | Import Enumerable Map Library from @openzeppelin  |
| `useEnumerableMapForBytes32`       | Use Enumerable Map For Bytes32         | Use Enumerable Map for Bytes32ToBytes32Map        |
| `useEnumerableMapForUint`          | Use Enumerable Map For Uint            | Use Enumerable Map for UintToUint                 |
| `useEnumerableMapForUintToAddress` | Use Enumerable Map For Uint to Address | Use Enumerable Map for UintToAddress              |
| `useEnumerableMapForAddressToUint` | Use Enumerable Map For Address to Uint | Use Enumerable Map for AddressToUint              |
| `useEnumerableMapForBytes32ToUint` | Use Enumerable Map For Bytes32 to UInt | Use Enumerable Map for Bytes32ToUint              |
| `enumerableMapBytes32`             | Enumerable Map Bytes32                 | Declare Enumerable Map for Bytes32ToBytes32Map    |
| `enumerableMapUint`                | Enumerable Map Uint                    | Declare Enumerable Map for UintToUint variable    |
| `enumerableMapUintAddress`         | Enumerable Map Uint to Address         | Declare Enumerable Map for UintToAddress variable |
| `enumerableMapAddressUint`         | Enumerable Map Address to Uint         | Declare Enumerable Map for AddressToUint variable |
| `enumerableMapBytes32Uint`         | Enumerable Map Bytes32 to Uint         | Declare Enumerable Map for Bytes32ToUint variable |

#### _Enumerable Set_

| Shortcut                     | Expanded                               | Description                                      |
| ---------------------------- | -------------------------------------- | ------------------------------------------------ |
| `importEnumerableSet`        | Import Enumerable Set                  | Import Enumerable Set Library from @openzeppelin |
| `useEnumerableSetForUint`    | Use Enumerable Set For Uint            | Use Enumerable Set Library for Uint Set          |
| `useEnumerableSetForBytes`   | Use Enumerable Set For Bytes           | Use Enumerable Set Library for Bytes32 Set       |
| `useEnumerableSetForAddress` | Use Enumerable Set For Uint to Address | Use Enumerable Set Library for Address Set       |
| `useEnumerableSetForSet`     | Use Enumerable Set For Set             | Use Enumerable Set Library for Set               |
| `enumerableSetUint`          | Enumerable Set Uint                    | Declare Enumerable Set for Uint variable         |
| `enumerableSetBytes32`       | Enumerable Set Bytes32                 | Declare Enumerable Set for Bytes32 variable      |
| `enumerableSetAddress`       | Enumerable Set Address                 | Declare Enumerable Set for Address variable      |
| `enumerableSetSet`           | Enumerable Set Set                     | Declare Enumerable Set for Set variable          |

#### _ERC20_

| Shortcut               | Expanded                        | Description                                                         |
| ---------------------- | ------------------------------- | ------------------------------------------------------------------- |
| `importSafeERC20`      | Import Safe ERC20               | Import SafeERC20 library from @openzeppelin                         |
| `importERC20`          | Import ERC20                    | Import ERC20 contract from @openzeppelin                            |
| `importERC20I`         | Import ERC20 Interface          | Import ERC20 Interface from @openzeppelin                           |
| `importERC20Permit`    | Import ERC20 Permit             | Import ERC20 Permit contract from @openzeppelin                     |
| `importERC20Votes`     | Import ERC20 Votes              | Import ERC20 Votes contract from @openzeppelin                      |
| `importERC20Wrapper`   | Import ERC20 Wrapper            | Import ERC20 Wrapper contract from @openzeppelin                    |
| `importERC20Burnable`  | Import ERC20 Burnable           | Import ERC20 Burnable contract from @openzeppelin                   |
| `importERC20Capped`    | Import ERC20 Capped             | Import ERC20 Capped contract from @openzeppelin                     |
| `importERC20FlashMint` | Import ERC20 Flash Mint         | Import ERC20 Flash Mint contract from @openzeppelin                 |
| `importERC20MetadataI` | Import ERC20 Metadata Interface | Import ERC20 Metadata Interface from @openzeppelin                  |
| `importERC20PermitI`   | Import ERC20 Permit Interface   | Import ERC20 Permit Interface from @openzeppelin                    |
| `erc20`                | ERC20                           | Create an ERC20 contract using @openzeppelin dependencies           |
| `erc20Permit`          | ERC20 Permit                    | Create an ERC20 Permit contract using @openzeppelin dependencies    |
| `erc20Votes`           | ERC20 Votes                     | Create an ERC20 Votes contract using @openzeppelin dependencies     |
| `erc20Wrapper`         | ER20 Wrapper                    | Create an ERC20 Wrapper contract using @openzeppelin dependencies   |
| `erc20Burnable`        | ERC20 Burnable                  | Create an ERC20 Burnable contract using @openzeppelin dependencies  |
| `erc20Capped`          | ERC20 Capped                    | Create a ERC20 Capped contract using @openzeppelin dependencies     |
| `erc20FlashMint`       | ERC20 Flash Mint                | Create a ERC20 Flash Mint contract using @openzeppelin dependencies |

#### _ERC165_

| Shortcut              | Expanded                | Description                                             |
| --------------------- | ----------------------- | ------------------------------------------------------- |
| `importERC165`        | Import ERC165           | Import ERC165 Contract from @openzeppelin               |
| `importERC165I`       | Import ERC165 Interface | Import ERC165 Interface from @openzeppelin              |
| `importERC165Checker` | Import ERC165 Checker   | Import ERC165 Checker Library from @openzeppelin        |
| `erc165`              | ERC165                  | Create ERC165 Contract using @openzeppelin dependencies |

### _ERC721_

| Shortcut                  | Expanded                           | Description                                                            |
| ------------------------- | ---------------------------------- | ---------------------------------------------------------------------- |
| `importERC721`            | Import ERC721                      | Import ERC721 contract from @openzeppelin                              |
| `importERC721I`           | Import ERC721 Interface            | Import ERC721 Interface from @openzeppelin                             |
| `importERC721ErrorsI`     | Import ERC721 Errors Interface     | Import ERC721 Errors Interface from @openzeppelin                      |
| `importERC721MetadataI`   | Import ERC721 Metadata Interface   | Import ERC721 Metadata Interface from @openzeppelin                    |
| `importERC721EnumerableI` | Import ERC721 Enumerable Interface | Import ERC721 Enumerable Interface from @openzeppelin                  |
| `importERC721ReceiverI`   | Import ERC721 Receiver Interface   | Import ERC721 Receiver Interface from @openzeppelin                    |
| `importERC721Pausable`    | Import ERC721 Pausable             | Import ERC721 Pausable contract from @openzeppelin                     |
| `importERC721Burnable`    | Import ERC721 Burnable             | Import ERC721 Burnable contract from @openzeppelin                     |
| `importERC721Consecutive` | Import ERC721 Consecutive          | Import ERC721 Consecutive contract from @openzeppelin                  |
| `importERC721Votes`       | Import ERC721 Votes                | Import ERC721 Votes contract from @openzeppelin                        |
| `importERC721Royalty`     | Import ERC721 Royalty              | Import ERC721 Royalty contract from @openzeppelin                      |
| `importERC721Wrapper`     | Import ERC721 Wrapper              | Import ERC721 Wrapper contract from @openzeppelin                      |
| `importERC721Holder`      | Import ERC721 Holder               | Import ERC721 Holder contract from @openzeppelin                       |
| `importERC721Enumerable`  | Import ERC721 Enumerable           | Import ERC721 Enumerable contract from @openzeppelin                   |
| `importERC721UriStorage`  | Import ERC721 Uri Storage          | Import ERC721 URI Storage contract from @openzeppelin                  |
| `erc721`                  | ERC721                             | Create an ERC721 contract using @openzeppelin dependencies             |
| `erc721Pausable`          | ERC721 Pausable                    | Create an ERC721 Pausable contract using @openzeppelin dependencies    |
| `erc721Burnable`          | ERC721 Burnable                    | Create an ERC721 Burnable contract using @openzeppelin dependencies    |
| `erc721Consecutive`       | ERC721 Consecutive                 | Create an ERC721 Consecutive contract using @openzeppelin dependencies |
| `erc721Votes`             | ERC721 Votes                       | Create an ERC721 Votes contract using @openzeppelin dependencies       |
| `erc721Royalty`           | ERC721 Royalty                     | Create an ERC721 Royalty contract using @openzeppelin dependencies     |
| `erc721Wrapper`           | ERC721 Wrapper                     | Create an ERC721 Wrapper contract using @openzeppelin dependencies     |
| `erc721Holder`            | ERC721 Holder                      | Create an ERC721 Holder contract using @openzeppelin dependencies      |
| `erc721Enumerable`        | ERC721 Enumerable                  | Create an ERC721 Enumerable contract using @openzeppelin dependencies  |
| `erc721UriStorage`        | ERC721 URI Storage                 | Create an ERC721 URI Storage contract using @openzeppelin dependencies |

#### _ERC1155_

| Shortcut                    | Expanded                              | Description                                                          |
| --------------------------- | ------------------------------------- | -------------------------------------------------------------------- |
| `importERC1155`             | Import ERC1155                        | Import ERC1155 contract from @openzeppelin                           |
| `importERC1155Pausable`     | Import ERC1155 Pausable               | Import ERC1155 Pausable contract from @openzeppelin                  |
| `importERC1155Burnable`     | Import ERC1155 Burnable               | Import ERC1155 Burnable contract from @openzeppelin                  |
| `importERC1155Supply`       | Import ERC1155 Supply                 | Import ERC1155 Supply contract from @openzeppelin                    |
| `importERC1155UriStorage`   | Import ERC1155 Uri Storage            | Import ERC1155 URI Storage contract from @openzeppelin               |
| `importERC1155Holder`       | Import ERC1155 Holder                 | Import ERC1155 Holder contract from @openzeppelin                    |
| `importERC1155I`            | Import ERC1155 Interface              | Import ERC115 Interface from @openzeppelin                           |
| `importERC1155MetadataUriI` | Import ERC1155 Metadata URI Interface | Import ERC1155 Metadata URI Interface from @openzeppelin             |
| `importERC1155ErrorsI`      | Import ERC1155 Errors Interface       | Import ERC1155 Errors Interface from @openzeppelin                   |
| `importERC1155ReceiverI`    | Import ERC1155 Receiver Interface     | Import ERC1155 Receiver Interface from @openzeppelin                 |
| `erc1155`                   | ERC1155                               | Create ERC1155 contract using @openzeppelin dependencies             |
| `erc1155Pausable`           | ERC1155 Pausable                      | Create ERC1155 Pausable contract using @openzeppelin dependencies    |
| `erc1155Burnable`           | ERC1155 Burnable                      | Create ERC1155 Burnable contract using @openzeppelin dependencies    |
| `erc1155Supply`             | ERC1155 Supply                        | Create ERC1155 Supply contract using @openzeppelin dependencies      |
| `erc1155UriStorage`         | ERC1155 URI Storage                   | Create ERC1155 URI Storage contract using @openzeppelin dependencies |
| `erc1155Holder`             | ERC1155 Holder                        | Create ERC1155 Holder contract using @openzeppelin dependencies      |

#### _ERC1271_

| Shortcut         | Expanded                 | Description                                 |
| ---------------- | ------------------------ | ------------------------------------------- |
| `importERC1271I` | Import ERC1271 Interface | Import ERC1271 Interface from @openzeppelin |

#### _ERC1363_

| Shortcut                 | Expanded                          | Description                                          |
| ------------------------ | --------------------------------- | ---------------------------------------------------- |
| `importERC1363I`         | Import ERC1363 Interface          | Import ERC1363 Interface from @openzeppelin          |
| `importERC1363ReceiverI` | Import ERC1363 Receiver Interface | Import ERC1363 Receiver Interface from @openzeppelin |
| `importERC1363SpenderI`  | Import ERC1363 Spender Interface  | Import ERC1363 Spender Interface from @openzeppelin  |

#### _ERC1820_

| Shortcut                    | Expanded                             | Description                                             |
| --------------------------- | ------------------------------------ | ------------------------------------------------------- |
| `importERC1820ImplementerI` | Import ERC1820 Implementer Interface | Import ERC1820 Implementer Interface from @openzeppelin |
| `importERC1820RegistryI`    | Import ERC1820 Registry Interface    | Import ERC1820 Registry Interface from @openzeppelin    |

#### _ERC1822_

| Shortcut                  | Expanded                           | Description                                           |
| ------------------------- | ---------------------------------- | ----------------------------------------------------- |
| `importERC1822ProxiableI` | Import ERC1822 Proxiable Interface | Import ERC1822 Proxiable Interface from @openzeppelin |

#### _ERC1967_

| Shortcut             | Expanded             | Description                                                    |
| -------------------- | -------------------- | -------------------------------------------------------------- |
| `importERC1967Proxy` | Import ERC1967 Proxy | Import ERC1967 Proxy contract from @openzeppelin               |
| `importERC1967Utils` | Import ERC1967 Utils | Import ERC1967 Utils Library from @openzeppelin                |
| `erc1967Proxy`       | Import ERC1967 Proxy | Create ERC1967 Proxy contract using @openzeppelin dependencies |

#### _ERC2612_

| Shortcut         | Expanded                 | Description                                 |
| ---------------- | ------------------------ | ------------------------------------------- |
| `importERC2612I` | Import ERC2612 Interface | Import ERC2612 Interface from @openzeppelin |

#### _ERC2771_

| Shortcut                | Expanded                 | Description                                                        |
| ----------------------- | ------------------------ | ------------------------------------------------------------------ |
| `importERC2771Context`  | Import ERC2771 Context   | Import ERC2771 Context Contract from @openzeppelin                 |
| `importERC2771Forwader` | Import ERC2771 Forwarder | Import ERC2771 Forwarder Contract from @openzeppelin               |
| `erc2771Context`        | ERC2771 Context          | Create ERC2771 Context Contract using @openzeppelin dependencies   |
| `erc2771Forwarder`      | ERC2771 Forwarder        | Create ERC2771 Forwarder Contract using @openzeppelin dependencies |

#### _ERC2981_

| Shortcut         | Expanded                 | Description                                 |
| ---------------- | ------------------------ | ------------------------------------------- |
| `importERC2981`  | Import ERC2981           | Import ERC2981 contract from @openzeppelin  |
| `importERC2981I` | Import ERC2981 Interface | Import ERC2981 Interface from @openzeppelin |

#### _ERC3156_

| Shortcut                      | Expanded                                | Description                                                |
| ----------------------------- | --------------------------------------- | ---------------------------------------------------------- |
| `importERC3156FlashLenderI`   | Import ERC3156 Flash Lender Interface   | Import ERC3156 Flash Lender Interface from @openzeppelin   |
| `importERC3156FlashBorrowerI` | Import ERC3156 Flash Borrower Interface | Import ERC3156 Flash Borrower Interface from @openzeppelin |

#### _ERC4626_

| Shortcut         | Expanded                 | Description                                              |
| ---------------- | ------------------------ | -------------------------------------------------------- |
| `importERC4626`  | Import ERC4626           | Import ERC4626 contract from @openzeppelin               |
| `importERC4626I` | Import ERC4626 Interface | Import ERC4626 Interface from @openzeppelin              |
| `erc4626`        | ERC4626                  | Create ERC4626 contract using @openzeppelin dependencies |

#### _ERC5267_

| Shortcut         | Expanded                 | Description                                 |
| ---------------- | ------------------------ | ------------------------------------------- |
| `importERC5267I` | Import ERC5267 Interface | Import ERC5267 Interface from @openzeppelin |

#### _ERC5313_

| Shortcut         | Expanded                 | Description                                 |
| ---------------- | ------------------------ | ------------------------------------------- |
| `importERC5313I` | Import ERC5313 Interface | Import ERC5313 Interface from @openzeppelin |

#### _ERC6372_

| Shortcut         | Expanded                 | Description                                 |
| ---------------- | ------------------------ | ------------------------------------------- |
| `importERC6372I` | Import ERC6372 Interface | Import ERC6372 Interface from @openzeppelin |

#### _Finance_

| Shortcut              | Expanded              | Description                                                     |
| --------------------- | --------------------- | --------------------------------------------------------------- |
| `importVestingWallet` | Import Vesting Wallet | Import Vesting Wallet contract from @openzeppelin               |
| `vestingWallet`       | Vesting Wallet        | Create Vesting Wallet contract using @openzeppelin dependencies |

#### _Governance_

| Shortcut                            | Expanded                              | Description                                                                   |
| ----------------------------------- | ------------------------------------- | ----------------------------------------------------------------------------- |
| `importGovernor`                    | Import Governor                       | Import Governor contract from @openzeppelin                                   |
| `importGovernorI`                   | Import Governor Interface             | Import Governor Interface from @openzeppelin                                  |
| `importGovernorCountingSimple`      | Import Governor Counting Simple       | Import Governor Counting Simple contract from @openzeppelin                   |
| `importGovernorVotes`               | Import Governor Votes                 | Import Governor Votes contract from @openzeppelin                             |
| `importGovernorVotesQuorumFraction` | Import Governor Votes Quorum Fraction | Import Governor Votes Quorum Fraction contract from @openzeppelin             |
| `importGovernorTimelockControl`     | Import Governor Timelock Control      | Import Governor Timelock Control contract from @openzeppelin                  |
| `importGovernorTimelockCompound`    | Import Governor Timelock Compound     | Import Governor Timelock Compound contract from @openzeppelin                 |
| `importGovernorSettings`            | Import Governor Settings              | Import Governor Settings contract from @openzeppelin                          |
| `importGovernorPreventLateQuorum`   | Import Governor Prevent Late Quorum   | Import Governor Prevent Late Quorum contract from @openzeppelin               |
| `importGovernorStorage`             | Import Governor Storage               | Import Governor Storage contract from @openzeppelin                           |
| `importTimelockController`          | Import TimeLock Controller            | Import Timelock Controller contract from @openzeppelin                        |
| `importVotes`                       | Import Votes                          | Import Votes contract from @openzeppelin                                      |
| `importVotesI`                      | Import Votes Interface                | Import Votes Interface from @openzeppelin                                     |
| `governor`                          | Governor                              | Create Governor contract using @openzeppelin dependencies                     |
| `governorCountingSimple`            | Governor Counting Simple              | Create Governor Counting Simple contract using @openzeppelin dependencies     |
| `governorVotes`                     | Governor Votes                        | Create Votes contract using @openzeppelin dependencies                        |
| `governorVotesQuorumFraction`       | Governor Votes Quorum Fraction        | Create Votes Quorum Fraction contract using @openzeppelin dependencies        |
| `governorTimelockControl`           | Governor Timelock Control             | Create Governor Timelock Control contract using @openzeppelin dependencies    |
| `governorTimelockCompound`          | Governor Timelock Compound            | Create Governor Timelock Compound contract using @openzeppelin dependencies   |
| `governorSettings`                  | Governor Settings                     | Create Governor Settings contract using @openzeppelin dependencies            |
| `governorPreventLateQuorum`         | Governor Prevent Late Quorum          | Create Governor Prevent Late Quorum contract using @openzeppelin dependencies |
| `governorStorage`                   | Governor Storage                      | Create Governor Storage contract using @openzeppelin dependencies             |
| `timelockController`                | Timelock Controller                   | Create Timelock Controller contract using @openzeppelin dependencies          |
| `votes`                             | Votes                                 | Create Votes contract using @openzeppelin dependencies                        |

#### _Multicall_

| Shortcut          | Expanded         | Description                                                |
| ----------------- | ---------------- | ---------------------------------------------------------- |
| `importMulticall` | Import Multicall | Import Multicall contract from @openzeppelin               |
| `multicall`       | Multicall        | Create Multicall contract using @openzeppelin dependencies |

#### _Proxy_

| Shortcut                            | Expanded                             | Description                                                                    |
| ----------------------------------- | ------------------------------------ | ------------------------------------------------------------------------------ |
| `importProxy`                       | Import Proxy                         | Import Proxy contract from @openzeppelin                                       |
| `importTransparentUpgradeableProxy` | Import Transparent Upgradeable Proxy | Import Transparent Upgradeable Proxy contract from @openzeppelin               |
| `importProxyAdmin`                  | Import Proxy Admin                   | Import Proxy Admin contract from @openzeppelin                                 |
| `importBeaconProxy`                 | Import Beacon Proxy                  | Import Beacon Proxy contract from @openzeppelin                                |
| `importUpgradeableBeacon`           | Import Upgradeable Beacon            | Import Upgradeable Beacon contract from @openzeppelin                          |
| `importInitializable`               | Import Initializable                 | Import Initializable contract from @openzeppelin                               |
| `importUUPSUpgradeable`             | Import Transparent UUPS Upgradeable  | Import UUPS Upgradeable contract from @openzeppelin                            |
| `importBeaconI`                     | Import Beacon Interface              | Import Beacon Interface from @openzeppelin                                     |
| `importClones`                      | Import Clones                        | Import Clones Library from @openzeppelin                                       |
| `proxy`                             | Proxy                                | Create Proxy contract using @openzeppelin dependencies                         |
| `transparentUpgradeableProxy`       | Transparent Upgradeable Proxy        | Create Transparent Upgradeable Proxy contract using @openzeppelin dependencies |
| `proxyAdmin`                        | Proxy Admin                          | Create Proxy Admin contract using @openzeppelin dependencies                   |
| `beaconProxy`                       | Beacon Proxy                         | Create Beacon Proxy contract using @openzeppelin dependencies                  |
| `upgradeableBeaconProxy`            | Upgradeable Beacon Proxy             | Create Upgradeable Beacon Proxy contract using @openzeppelin dependencies      |
| `uupsUpgradeableProxy`              | UUPS Upgradeable Proxy               | Create UUPS Upgradeable Proxy contract using @openzeppelin dependencies        |

#### _Reentracy Guard_

| Shortcut                | Expanded                | Description                                                       |
| ----------------------- | ----------------------- | ----------------------------------------------------------------- |
| `importReentrancyGuard` | Import Reentrancy Guard | Import Reentrancy Guard contract from @openzeppelin               |
| `reentrancyGuard`       | Reentrancy Guard        | Create Reentrancy Guard contract using @openzeppelin dependencies |

#### _Utils_

| Shortcut                 | Expanded                  | Description                                           |
| ------------------------ | ------------------------- | ----------------------------------------------------- |
| `importMath`             | Import Math               | Import Math Library from @openzeppelin                |
| `importSignedMath`       | Import Signed Math        | Import Signed Math Library from @openzeppelin         |
| `importSafeCast`         | Import Safe Cast          | Import Safe Cast Library from @openzeppelin           |
| `importStrings`          | Import Strings            | Import String utils library from @openzeppelin        |
| `importECDSA`            | Import ECDSA              | Import ECDSA Library from @openzeppelin               |
| `importMessageHash`      | Import Message Hash       | Import Message Hash Utils Library from @openzeppelin  |
| `importSignatureChecker` | Import Signature Checker  | Import Signature Checker Library from @openzeppelin   |
| `importMerkleProof`      | Import Merkle Proof       | Import Merkle Proof Library from @openzeppelin        |
| `importEIP712`           | Import EIP712             | Import EIP712 Contract from @openzeppelin             |
| `importPausable`         | Import Pausable           | Import Pausable Contract from @openzeppelin           |
| `importNonces`           | Import Nonces             | Import Nonces Contract from @openzeppelin             |
| `importDoubleEndedQueue` | Import Double Ended Queue | Import Doubled Ended Queue Library from @openzeppelin |
| `importCheckpoints`      | Import Checkpoints        | Import Checkpoints Library from @openzeppelin         |
| `importCreate2`          | Import Create 2           | Import Create2 Library from @openzeppelin             |
| `importAddress`          | Import Address            | Import Address Library from @openzeppelin             |
| `importArrays`           | Import Array              | Import Arrays Library from @openzeppelin              |
| `importShortStrings`     | Import Short Strings      | Import Short Strings Library from @openzeppelin       |
| `importStorageSlot`      | Import Storage Slot       | Import Storage Slot Library from @openzeppelin        |
| `importContext`          | Import Context            | Import Context Library from @openzeppelin"            |

### Solmate

#### _Auth_

| Shortcut      | Expanded     | Description                                      |
| ------------- | ------------ | ------------------------------------------------ |
| `importAuth`  | Import Auth  | Import Auth Contract from solmate                |
| `importOwned` | Import Owned | Import Owned Contract from solmate               |
| `auth`        | Auth         | Create Auth Contract using solmate dependencies  |
| `owned`       | Owned        | Create Owned Contract using solmate dependencies |

#### _Authorities_

| Shortcut                    | Expanded                     | Description                                                      |
| --------------------------- | ---------------------------- | ---------------------------------------------------------------- |
| `importRolesAuthority`      | Import Roles Authority       | Import Roles Authority Contract from solmate                     |
| `importMultiRolesAuthority` | Import Multi Roles Authority | Import Multi Roles Authority Contract from solmate               |
| `rolesAuthority`            | Roles Authority              | Create Roles Authority Contract using solmate dependencies       |
| `multiRolesAuthority`       | Multi Roles Authority        | Create Multi Roles Authority Contract using solmate dependencies |

#### _Utils_

| Shortcut                  | Expanded                    | Description                                   |
| ------------------------- | --------------------------- | --------------------------------------------- |
| `importSSTORE2`           | Import SSTORE2              | Import SSTORE2 library from solmate           |
| `importCREATE3`           | Import CREATE3              | Import CREATE3 library from solmate           |
| `importLibString`         | Import LibString            | Import LibString library from solmate         |
| `importSignedWadMath`     | Import Signed Wad Math      | Import SignedWadMath library from solmate     |
| `importMerkleProofLib`    | Import Merkle Proof Lib     | Import MerkleProofLib library from solmate    |
| `importFixedPointMathLib` | Import Fixed Point Math Lib | Import FixedPointMathLib library from solmate |
| `importBytes32AddressLib` | Import Bytes32 Address Lib  | Import Bytes32AddressLib library from solmate |
| `importSafeTransferLib`   | Import Safe Transfer Lib    | Import SafeTransferLib library from solmate   |

#### _WETH_

| Shortcut     | Expanded    | Description                       |
| ------------ | ----------- | --------------------------------- |
| `importWETH` | Import WETH | Import WETH Contract from solmate |

### Solidity

### _Variables_

#### _Bytes_

| Shortcut                   | Expanded                   | Description                                  |
| -------------------------- | -------------------------- | -------------------------------------------- |
| `bytes*Private`            | Bytes\* Private            | Create a bytes\* private variable            |
| `bytes*PrivateConstant`    | Bytes\* Private Constant   | Create a bytes\* private constant variable   |
| `bytes*Public`             | Bytes\* Public             | Create a bytes\* public variable             |
| `bytes*PublicConstant`     | Bytes\* Public Constant    | Create a bytes\* public constant variable    |
| `bytes*Internal`           | Bytes\* Internal           | Create a bytes\* internal variable           |
| `bytes*InternalConstant`   | Bytes\* Internal Constant  | Create a bytes\* internal constant variable  |
| `bytes*PrivateImmutable*`  | Bytes\* Private Immutable  | Create a bytes\* private immutable variable  |
| `bytes*PublicImmutable*`   | Bytes\* Public Immutable   | Create a bytes\* public immutable variable   |
| `bytes*InternalImmutable*` | Bytes\* Internal Immutable | Create a bytes\* internal immutable variable |

#### _Address_

| Shortcut                    | Expanded                   | Description                                   |
| --------------------------- | -------------------------- | --------------------------------------------- |
| `addressPrivate`            | Address Private            | Create an address private variable            |
| `addressPrivateConstant`    | Address Private Constant   | Create an address private constant variable   |
| `addressPublic`             | Address Public             | Create an address public variable             |
| `addressPublicConstant`     | Address Public Constant    | Create an address public constant variable    |
| `addressInternal`           | Address Internal           | Create an address internal variable           |
| `addressInternalConstant`   | Address Internal Constant  | Create an address internal constant variable  |
| `addressPrivateImmutable*`  | Address Private Immutable  | Create an address private immutable variable  |
| `addressPublicImmutable*`   | Address Public Immutable   | Create an address public immutable variable   |
| `addressInternalImmutable*` | Address Internal Immutable | Create an address internal immutable variable |

#### _String_

| Shortcut                 | Expanded                 | Description                                |
| ------------------------ | ------------------------ | ------------------------------------------ |
| `stringPrivate`          | String Private           | Create a string private variable           |
| `stringPrivateConstant`  | String Private Constant  | Create a string private constant variable  |
| `stringPublic`           | String Public            | Create a string public variable            |
| `stringPublicConstant`   | String Public Constant   | Create a string public constant variable   |
| `stringInternal`         | String Internal          | Create a string internal variable          |
| `stringInternalConstant` | String Internal Constant | Create a string internal constant variable |

#### _Bool_

| Shortcut                | Expanded                | Description                               |
| ----------------------- | ----------------------- | ----------------------------------------- |
| `boolPrivate`           | Bool Private            | Create a bool private variable            |
| `boolPrivateConstant`   | Bool Private Constant   | Create a bool private constant variable   |
| `boolPrivateImmutable`  | Bool Private Immutable  | Create a bool private immutable variable  |
| `boolPublic`            | Bool Public             | Create a bool public variable             |
| `boolPublicImmutable`   | Bool Public Immutable   | Create a bool public immutable variable   |
| `boolPublicConstant`    | Bool Public Constant    | Create a bool public constant variable    |
| `boolInternal`          | Bool Internal           | Create a bool internal variable           |
| `boolInternalConstant`  | Bool Internal Constant  | Create a bool internal constant variable  |
| `boolInternalImmutable` | Bool Internal Immutable | Create a bool internal immutable variable |

#### _Uint_

| Shortcut                 | Expanded                  | Description                                  |
| ------------------------ | ------------------------- | -------------------------------------------- |
| `uint*Private`           | Uint\* Private            | Create an uint\* private variable            |
| `uint*PrivateConstant`   | Uint\* Private Constant   | Create an uint\* private constant variable   |
| `uint*PrivateImmutable`  | Uint\* Private Immutable  | Create an uint\* private immutable variable  |
| `uint*Public`            | Uint\* Public             | Create an uint\* public variable             |
| `uint*PublicConstant`    | Uint\* Public Constant    | Create an uint\* public constant variable    |
| `uint*PublicImmutable`   | Uint\* Public Immutable   | Create an uint\* public immutable variable   |
| `uint*Internal`          | Uint\* Internal           | Create an uint\* internal variable           |
| `uint*InternalConstant`  | Uint\* Internal Constant  | Create an uint\* internal constant variable  |
| `uint*InternalImmutable` | Uint\* Internal Immutable | Create an uint\* internal immutable variable |

#### _Int_

| Shortcut                | Expanded                 | Description                                 |
| ----------------------- | ------------------------ | ------------------------------------------- |
| `int*Private`           | Int\* Private            | Create an int\* private variable            |
| `int*PrivateConstant`   | Int\* Private Constant   | Create an int\* private constant variable   |
| `int*PrivateImmutable`  | Int\* Private Immutable  | Create an int\* private immutable variable  |
| `int*Public`            | Int\* Public             | Create an int\* public variable             |
| `int*PublicConstant`    | Int\* Public Constant    | Create an int\* public constant variable    |
| `int*PublicImmutable`   | Int\* Public Immutable   | Create an int\* public immutable variable   |
| `int*Internal`          | Int\* Internal           | Create an int\* internal variable           |
| `int*InternalConstant`  | Int\* Internal Constant  | Create an int\* internal constant variable  |
| `int*InternalImmutable` | Int\* Internal Immutable | Create an int\* internal immutable variable |

#### _Mapping_

| Shortcut          | Expanded         | Description                         |
| ----------------- | ---------------- | ----------------------------------- |
| `mappingPrivate`  | Mapping Private  | Create an mapping private variable  |
| `mappingPublic`   | Mapping Public   | Create an mapping public variable   |
| `mappingInternal` | Mapping Internal | Create an mapping internal variable |

#### _Arrays_

| Shortcut                                                       | Expanded                                                      | Description                                                                     |
| -------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| `{bytes, address, string, bool, uint, int, mapping}[]Private`  | {bytes, address, string, bool, uint, int, mapping}[] Private  | Create a {bytes, address, string, bool, uint, int, mapping}[] private variable  |
| `{bytes, address, string, bool, uint, int, mapping}[]Public`   | {bytes, address, string, bool, uint, int, mapping}[] Public   | Create a {bytes, address, string, bool, uint, int, mapping}[] public variable   |
| `{bytes, address, string, bool, uint, int, mapping}[]Internal` | {bytes, address, string, bool, uint, int, mapping}[] Internal | Create a {bytes, address, string, bool, uint, int, mapping}[] internal variable |

### Functions

| Shortcut                     | Expanded                      | Description                                  |
| ---------------------------- | ----------------------------- | -------------------------------------------- |
| `externalFunctionViewReturn` | External Function View Return | Create an external view function with return |
| `externalFunctionPureReturn` | External Function Pure Return | Create an external pure function with return |
| `externalFunctionReturn`     | External Function Return      | Create an external function with return      |
| `externalFunction`           | External Function             | Create an external function without return   |
| `publicFunctionViewReturn`   | Public Function View Return   | Create an public view function with return   |
| `publicFunctionPureReturn`   | Public Function Pure Return   | Create an public pure function with return   |
| `publicFunctionReturn`       | Public Function Return        | Create an public function with return        |
| `publicFunction`             | Public Function               | Create an public function without return     |
| `internalFunctionViewReturn` | Internal Function View Return | Create an internal view function with return |
| `internalFunctionPureReturn` | Internal Function Pure Return | Create an internal pure function with return |
| `internalFunctionReturn`     | Internal Function Return      | Create an internal function with return      |
| `internalFunction`           | Internal Function             | Create an internal function without return   |
| `privateFunctionViewReturn`  | Private Function View Return  | Create an private view function with return  |
| `privateFunctionPureReturn`  | Private Function Pure Return  | Create an private pure function with return  |
| `privateFunctionReturn`      | Private Function Return       | Create an private function with return       |
| `privateFunction`            | Private Function              | Create an private function without return    |

### Licenses

| Shortcut            | Expanded             | Description                 |
| ------------------- | -------------------- | --------------------------- |
| `unlicensedLicense` | Unlicensed License   | Create Unlicensed License   |
| `mitLicense`        | MIT License          | Create MIT License          |
| `busl1.1License`    | BUSL-1.1 License     | Create BUSL-1.1 License     |
| `gplv3License`      | GPLv3 License        | Create GPLv3 License        |
| `apacheLicense2`    | Apache 2.0 License   | Create Apache 2.0 License   |
| `bsd3ClauseLicense` | BSD 3-Clause License | Create BSD 3-Clause License |
| `bsd2ClauseLicense` | BSD 2-Clause License | Create BSD 2-Clause License |
| `iscLicense`        | ISC License          | Create ISC License          |
| `cc0License`        | CC0 License          | Create CC0 1.0 License      |
| `agpl3License`      | AGPL-3.0 License     | Create AGPL-3.0 License     |

### NatSpec

| Shortcut      | Expanded    | Description               |
| ------------- | ----------- | ------------------------- |
| `@notice`     | @notice     | Create natspec notice     |
| `@dev`        | @dev        | Create natspec dev        |
| `@title`      | @title      | Create natspec title      |
| `@custom`     | @custom     | Create natspec custom     |
| `@author`     | @author     | Create natspec author     |
| `@inheritdoc` | @inheritdoc | Create natspec inheritdoc |
| `@return`     | @return     | Create natspec return     |
| `@param`      | @param      | Create natspec param      |

### General Snippets

| Shortcut      | Expanded    | Description              |
| ------------- | ----------- | ------------------------ |
| `using`       | Using       | Use X Library for Y Type |
| `constructor` | Constructor | Create Constructor       |
| `event`       | Event       | Create Event             |
| `maxUint256`  | Max Uint256 | Create maxUint256        |
| `unchecked`   | Unchecked   | Create unchecked Block   |
| `modifier`    | Modifier    | Create Modifier          |
| `error`       | Error       | Create Error             |

## Release Notes

### 1.0.0

Initial release of Awesome Solidity

### 1.0.1

Added Profile Picture and Adjusted Package.json
