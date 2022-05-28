# _primaryTerminalOf

:::caution
This page describes v2 contracts used before [a bug was identified](/docs/2022-05-24/). View the latest updates [here](https://juicebox.money/#/v2-bug-updates/).
:::

Contract: [`JBDirectory`](/protocol/api/contracts/jbdirectory/README.md)‌

**The project's primary terminal for a token.**

#### Definition

```
/** 
  @notice 
  The project's primary terminal for a token.

  _projectId The ID of the project to get the primary terminal of.
  _token The token to get the project's primary terminal of.
*/
mapping(uint256 => mapping(address => IJBPaymentTerminal)) private _primaryTerminalOf;
```

* Arguments:
  * `_projectId` is the ID of the project to get the primary terminal of.
  * `_token` is the token to get the project's primary terminal of.
* The resulting view function is private to this contract.
