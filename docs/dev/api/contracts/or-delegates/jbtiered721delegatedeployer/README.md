# JBTiered721DelegateDeployer

*Deploys a tier delegate.*

#### Code

https://github.com/jbx-protocol/juice-nft-rewards/blob/main/contracts/JBTiered721DelegateDeployer.sol

#### Addresses

Ethereum Mainnet: *Not deployed*

Goerli Testnet: *Not deployed*

#### Interfaces

|Name|Description|
|-|-|
|[**`IJBTiered721DelegateDeployer`**](/dev/api/interfaces/ijbtiered721delegatedeployer)|General interface for the methods in this contract that interact with the blockchain's state according to the protocol's rules.|

#### Constructor

```
constructor(
  JB721GlobalGovernance _globalGovernance,
  JB721TieredGovernance _tieredGovernance,
  JBTiered721Delegate _noGovernance
) {
  globalGovernance = _globalGovernance;
  tieredGovernance = _tieredGovernance;
  noGovernance = _noGovernance;
}
```

#### Properties

|Name|Definition|
|-|-|
|[**`globalGovernance`**](properties/globalgovernance)|**Traits**<ul><li>`immutable`</li></ul>**Returns**<ul><li>[`JB721GlobalGovernance `](/dev/api/contracts/or-delegates/jb721globalgovernance/)</li></ul>|
|[**`tieredGovernance`**](properties/tieredgovernance)|**Traits**<ul><li>`immutable`</li></ul>**Returns**<ul><li>[`JB721TieredGovernance `](/dev/api/contracts/or-delegates/jb721tieredgovernance/)</li></ul>|
|[**`noGovernance`**](properties/nogovernance)|**Traits**<ul><li>`immutable`</li></ul>**Returns**<ul><li>[`JBTiered721Delegate `](/dev/api/contracts/or-delegates/jbtiered721delegate/)</li></ul>|

#### Events

|Name|Data|
|-|-|
|[`DelegateDeployed`](events/delegatedeployed)|<ul><li>`uint256 indexed projectId`</li><li>[`IJBTiered721Delegate`](/dev/api/interfaces/ijbtiered721delegate) `newDelegate`</li></ul>|

#### Write

|Function|Definition|
|-|-|
|[**`deployDelegateFor`**](write/deploydelegatefor)|**Params**<ul><li>`uint256 _projectId`</li><li>[`JBDeployTiered721DelegateData`](/dev/api/data-structures/jbdeploytiered721delegatedata) `memory _deployTiered721DelegateData`</li></ul>**Returns**<ul><li>[`IJBTiered721Delegate`](/dev/api/interfaces/ijbtiered721delegate)</li></ul>|
