# Change Log

## [1.2.0]

- Added Solhint Snippets:

  | Shortcut                 | Expanded                  | Description                             |
  | ------------------------ | ------------------------- | --------------------------------------- |
  | `solhintDisableNextLine` | Solhint Disable Next Line | Disable solhint linter for next line    |
  | `solhintDisableLine`     | Solhint Disable Line      | Disable solhint linter for current line |
  | `solhintDisable`         | Solhint Disable           | Disable solhint linter for current file |
  | `solhintEnable`          | Solhint Enable            | Enable solhint linter for current file  |

- Added Slither Snippets:

  | Shortcut                 | Expanded                  | Description                                 |
  | ------------------------ | ------------------------- | ------------------------------------------- |
  | `slitherDisableNextLine` | Slither Disable Next Line | Disable slither detector for next line      |
  | `slitherDisableStart`    | Slither Disable Start     | Disable slither detector starting from line |
  | `slitherDisableEnd`      | Slither Disable End       | Disable slither detector until line         |

- Added OpenZeppelin Access Snippets:
  | Shortcut | Expanded | Description |
  | ------------------------ | ------------------------- | ------------------------------------------- |
  | `importAccessControlDefaultAdminRules` | Import Access Control Default Admin Rules | Import Access Control Default Admin Rules Contract from @openzeppelin |
  | `accessControlDefaultAdminRules` | Access Control Default Admin Rules | Create an Access Control Default Admin Rules contract using @openzeppelin dependencies |

- Added OpenZeppelin ERC20 Snippets:
  | Shortcut | Expanded | Description |
  | ------------------------ | ------------------------- | ------------------------------------------- |
  | `importERC20Mock` | Import ERC20 Mock | Import ERC20 Mock contract from @openzeppelin |
  | `erc20Mock` | ERC20 Mock | Create an ERC20 Mock contract using @openzeppelin dependencies |

- Made the ERC20 uppercase in `importSafeErc20`

  ```diff
  - importSafeErc20
  + importSafeERC20
  ```

- Added Balancer V2 Interfaces Snippets:

  | Shortcut                                 | Expanded                                             | Description                                                                          |
  | ---------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------ |
  | `importDistributorCallbackI`             | Import Distributor Callback Interface                | Import Distributor Callback Interface from balancer-v2 interfaces                    |
  | `importArbitrumFeeProviderI`             | Import Arbitrum Fee Provider Interface               | Import Arbitrum Fee Provider Interface from balancer-v2 interfaces                   |
  | `importAuthorizerAdaptorI`               | Import Authorizer Adaptor Interface                  | Import Authorizer Adaptor Interface from balancer-v2 interfaces                      |
  | `importAuthorizerAdaptorEntrypointI`     | Import Authorizer Adaptor Entrypoint Interface       | Import Authorizer Adaptor Entrypoint Interface from balancer-v2 interfaces           |
  | `importBalancerMinterI`                  | Import Balancer Minter Interface                     | Import Balancer Minter Interface from balancer-v2 interfaces                         |
  | `importBalancerTokenI`                   | Import Balancer Token Interface                      | Import Balancer Token Interface from balancer-v2 interfaces                          |
  | `importBalancerTokenAdminI`              | Import Balancer Token Admin Interface                | Import Balancer Token Admin Interface from balancer-v2 interfaces                    |
  | `importChildChainGaugeI`                 | Import Child Chain Gauge Interface                   | Import Child Chain Gauge Interface from balancer-v2 interfaces                       |
  | `importChildChainLiquidityGaugeFactoryI` | Import Child Chain Liquidity Gauge Factory Interface | Import Child Chain Liquidity Gauge Factory Interface from balancer-v2 interfaces     |
  | `importChildChainStreamerI`              | Import Child Chain Streamer Interface                | Import Child Chain Streamer Interface from balancer-v2 interfaces                    |
  | `importFeeDistributorI`                  | Import Fee Distributor Interface                     | Import Fee Distributor Interface from balancer-v2 interfaces                         |
  | `importGaugeAdderI`                      | Import Gauge Adder Interface                         | Import Gauge Adder Interface from balancer-v2 interfaces                             |
  | `importGaugeControllerI`                 | Import Gauge Controller Interface                    | Import Gauge Controller Interface from balancer-v2 interfaces                        |
  | `importLMGettersI`                       | Import LM Getters Interface                          | Import LM Getters Interface from balancer-v2 interfaces                              |
  | `importLiquidityGaugeI`                  | Import Liquidity Gauge Interface                     | Import Liquidity Gauge Interface from balancer-v2 interfaces                         |
  | `importLiquidityGaugeFactoryI`           | Import Liquidity Gauge Factory Interface             | Import Liquidity Gauge Factory Interface from balancer-v2 interfaces                 |
  | `importMainnetBalancerMinterI`           | Import Mainnet Balancer Minter Interface             | Import Mainnet Balancer Minter Interface from balancer-v2 interfaces                 |
  | `importOptimismGasLimitProviderI`        | Import Optimism Gas Limit Provider Interface         | Import Optimism Gas Limit Provider Interface from balancer-v2 interfaces             |
  | `importRewardTokenDistributorI`          | Import Reward Token Distributor Interface            | Import Reward Token Distributor Interface from balancer-v2 interfaces                |
  | `importRewardsOnlyGaugeI`                | Import Rewards Only Gauge Interface                  | Import Rewards Only Gauge Interface from balancer-v2 interfaces                      |
  | `importSmartWalletCheckerI`              | Import Smart Wallet Checker Interface                | Import Smart Wallet Checker Interface from balancer-v2 interfaces                    |
  | `importStakelessGaugeI`                  | Import Stakeless Gauge Interface                     | Import Stakeless Gauge Interface from balancer-v2 interfaces                         |
  | `importStakingLiquidityGaugeI`           | Import Staking Liquidity Gauge Interface             | Import Staking Liquidity Gauge Interface from balancer-v2 interfaces                 |
  | `importVeDelegationI`                    | Import ve Delegation Interface                       | Import ve Delegation Interface from balancer-v2 interfaces                           |
  | `importVotingEscrowI`                    | Import Voting Escrow Interface                       | Import Voting Escrow Interface from balancer-v2 interfaces                           |
  | `importLinearPoolI`                      | Import Linear Pool Interface                         | Import Linear Pool Interface from balancer-v2 interfaces                             |
  | `importERC4626I`                         | Import ERC4626 Interface                             | Import ERC4626 Interface from balancer-v2 interfaces                                 |
  | `importComposableStablePoolRatesI`       | Import Composable Stable Pool Interface              | Import Composable Stable Pool Interface from balancer-v2 interfaces                  |
  | `importStablePoolUserData`               | Import Stable Pool User Data                         | Import Stable Pool User Data Library from balancer-v2 interfaces                     |
  | `importBasePoolUserData`                 | Import Base Pool User Data Library                   | Import Base Pool User Data Library from @balancer-labs/v2-interfaces                 |
  | `importBasePoolControllerI`              | Import Base Pool Controller Interface                | Import Base Pool Controller Interface from @balancer-labs/v2-interfaces              |
  | `importBasePoolFactoryI`                 | Import Base Pool Factory Interface                   | Import Base Pool Factory Interface from @balancer-labs/v2-interfaces                 |
  | `importControlledPoolI`                  | Import Controlled Pool Interface                     | Import Controlled Pool Interface from @balancer-labs/v2-interfaces                   |
  | `importFactoryCreatedPoolVersionI`       | Import Factory Created Pool Version Interface        | Import Factory Created Pool Version Interface from @balancer-labs/v2-interfaces      |
  | `importLastCreatedPoolFactoryI`          | Import Last Created Pool Factory Interface           | Import Last Created Pool Factory Interface from @balancer-labs/v2-interfaces         |
  | `importManagedPoolI`                     | Import Managed Pool Interface                        | Import Managed Pool Interface from @balancer-labs/v2-interfaces                      |
  | `importPoolVersionI`                     | Import Pool Version Interface                        | Import Pool Version Interface from @balancer-labs/v2-interfaces                      |
  | `importProtocolFeeCacheI`                | Import Protocol Fee Cache Interface                  | Import Protocol Fee Cache Interface from @balancer-labs/v2-interfaces                |
  | `importRateProviderI`                    | Import Rate Provider Interface                       | Import Rate Provider Interface from @balancer-labs/v2-interfaces                     |
  | `importRateProviderPoolI`                | Import Rate Provider Pool Interface                  | Import Rate Provider Pool Interface from @balancer-labs/v2-interfaces                |
  | `importRecoveryModeI`                    | Import Recovery Mode Interface                       | Import Recovery Mode Interface from @balancer-labs/v2-interfaces                     |
  | `importRecoveryModeHelperI`              | Import Recovery Mode Helper Interface                | Import Recovery Mode Helper Interface from @balancer-labs/v2-interfaces              |
  | `importVersionI`                         | Import Version Interface                             | Import Version Interface from @balancer-labs/v2-interfaces                           |
  | `importExternalWeightedMathI`            | Import External Weighted Math Interface              | Import External Weighted Math Interface from balancer-v2 interfaces                  |
  | `importWeightedPoolUserData`             | Import Weighted Pool User Data                       | Import Weighted Pool User Data Library from balancer-v2 interfaces                   |
  | `importATokenI`                          | Import A Token Interface                             | Import A Token Interface from @balancer-labs/v2-interfaces                           |
  | `importBALTokenHolderI`                  | Import BAL Token Holder Interface                    | Import BAL Token Holder Interface from @balancer-labs/v2-interfaces                  |
  | `importBALTokenHolderFactoryI`           | Import BAL Token Holder Factory Interface            | Import BAL Token Holder Factory Interface from @balancer-labs/v2-interfaces          |
  | `importBalancerQueriesI`                 | Import Balancer Queries Interface                    | Import Balancer Queries Interface from @balancer-labs/v2-interfaces                  |
  | `importBalancerRelayerI`                 | Import Balancer Relayer Interface                    | Import Balancer Relayer Interface from @balancer-labs/v2-interfaces                  |
  | `importButtonWrapperI`                   | Import Button Wrapper Interface                      | Import Button Wrapper Interface from @balancer-labs/v2-interfaces                    |
  | `importCTokenI`                          | Import C Token Interface                             | Import C Token Interface from @balancer-labs/v2-interfaces                           |
  | `importEulerTokenI`                      | Import Euler Token Interface                         | Import Euler Token Interface from @balancer-labs/v2-interfaces                       |
  | `importGearboxDieselTokenI`              | Import Gearbox Diesel Token Interface                | Import Gearbox Diesel Token Interface from @balancer-labs/v2-interfaces              |
  | `importProtocolFeePercentagesProviderI`  | Import Protocol Fee Percentages Provider Interface   | Import Protocol Fee Percentages Provider Interface from @balancer-labs/v2-interfaces |
  | `importProtocolFeeSplitterI`             | Import Protocol Fee Splitter Interface               | Import Protocol Fee Splitter Interface from @balancer-labs/v2-interfaces             |
  | `importProtocolFeesWithdrawerI`          | Import Protocol Fees Withdrawer Interface            | Import Protocol Fees Withdrawer Interface from @balancer-labs/v2-interfaces          |
  | `importProtocolIdRegistryI`              | Import Protocol ID Registry Interface                | Import Protocol ID Registry Interface from @balancer-labs/v2-interfaces              |
  | `importReaperTokenVaultI`                | Import Reaper Token Vault Interface                  | Import Reaper Token Vault Interface from @balancer-labs/v2-interfaces                |
  | `importShareTokenI`                      | Import Share Token Interface                         | Import Share Token Interface from @balancer-labs/v2-interfaces                       |
  | `importSiloI`                            | Import Silo Interface                                | Import Silo Interface from @balancer-labs/v2-interfaces                              |
  | `importStaticATokenLMI`                  | Import Static A Token LM Interface                   | Import Static A Token LM Interface from @balancer-labs/v2-interfaces                 |
  | `importTetuSmartVaultI`                  | Import Tetu Smart Vault Interface                    | Import Tetu Smart Vault Interface from @balancer-labs/v2-interfaces                  |
  | `importTetuStrategyI`                    | Import Tetu Strategy Interface                       | Import Tetu Strategy Interface from @balancer-labs/v2-interfaces                     |
  | `importUnbuttonTokenI`                   | Import Unbutton Token Interface                      | Import Unbutton Token Interface from @balancer-labs/v2-interfaces                    |
  | `importYearnTokenVaultI`                 | Import Yearn Token Vault Interface                   | Import Yearn Token Vault Interface from @balancer-labs/v2-interfaces                 |
  | `importstETHI`                           | Import stETH Interface                               | Import stETH Interface from @balancer-labs/v2-interfaces                             |
  | `importwstETHI`                          | Import wstETH Interface                              | Import wstETH Interface from @balancer-labs/v2-interfaces                            |
  | `importAssetI`                           | Import Asset Interface                               | Import Asset Interface from @balancer-labs/v2-interfaces                             |
  | `importAuthorizerI`                      | Import Authorizer Interface                          | Import Authorizer Interface from @balancer-labs/v2-interfaces                        |
  | `importBasePoolI`                        | Import Base Pool Interface                           | Import Base Pool Interface from @balancer-labs/v2-interfaces                         |
  | `importBasicAuthorizerI`                 | Import Basic Authorizer Interface                    | Import Basic Authorizer Interface from @balancer-labs/v2-interfaces                  |
  | `importFlashLoanRecipientI`              | Import Flash Loan Recipient Interface                | Import Flash Loan Recipient Interface from @balancer-labs/v2-interfaces              |
  | `importGeneralPoolI`                     | Import General Pool Interface                        | Import General Pool Interface from @balancer-labs/v2-interfaces                      |
  | `importMinimalSwapInfoPoolI`             | Import Minimal Swap Info Pool Interface              | Import Minimal Swap Info Pool Interface from @balancer-labs/v2-interfaces            |
  | `importPoolSwapStructsI`                 | Import Pool Swap Structs Interface                   | Import Pool Swap Structs Interface from @balancer-labs/v2-interfaces                 |
  | `importProtocolFeesCollectorI`           | Import Protocol Fees Collector Interface             | Import Protocol Fees Collector Interface from @balancer-labs/v2-interfaces           |
  | `importVaultI`                           | Import Vault Interface                               | Import Vault Interface from @balancer-labs/v2-interfaces                             |

## [1.1.0]

- Added OpenZeppelin Upgradable snippets:

  | Shortcut                       | Expanded                        | Description                                                                  |
  | ------------------------------ | ------------------------------- | ---------------------------------------------------------------------------- |
  | `importOwnableUpgradeable`     | Import Ownable Upgradeable      | Import Ownable Upgradeable contract from @openzeppelin                       |
  | `ownableUpgradeable`           | Ownable Upgradeable             | Create an Ownable Upgradeable contract using @openzeppelin dependencies      |
  | `importERC20Upgradeable`       | Import ERC20 Upgradeable        | Import ERC20 Upgradeable contract from @openzeppelin                         |
  | `erc20Upgradeable`             | ERC20 Upgradeable               | Create an ERC20 Upgradeable contract using @openzeppelin dependencies        |
  | `importERC20PermitUpgradeable` | Import ERC20 Permit Upgradeable | Import ERC20 Permit Upgradeable contract from @openzeppelin                  |
  | `erc20PermitUpgradeable`       | ERC20 Permit Upgradeable        | Create an ERC20 Permit Upgradeable contract using @openzeppelin dependencies |

- Added 2 more using {lib} for {type}:
  | Shortcut | Expanded | Description |
  | ------------------------ | ------------------------- | ----------------------------------------------------- |
  | `useStringsForAddress` | Use Strings For Address | Use Strings Library For Address type |
  | `useStringsForUint256` | Use Strings For Uint256 | Use Strings Library For Uint256 type |

## [1.0.1]

- Added Profile Picture and Adjusted Package.json

## [1.0.0]

- Initial release
