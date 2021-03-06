# CollateralEth

## Description

**Source:** [contracts/CollateralEth.sol](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol)

## Variables

### `pendingWithdrawals`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L16)</sub>

**Type:** `mapping(address => uint256)`

## Constructor

### `constructor`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L18)</sub>

??? example "Details"

    **Signature**

    `constructor(contract CollateralState _state, address _owner, address _manager, address _resolver, bytes32 _collateralKey, uint256 _minCratio, uint256 _minCollateral)`

    **Visibility**

    `public`

    **State Mutability**

    `undefined`

## External Functions

### `claim`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L70)</sub>

??? example "Details"

    **Signature**

    `claim(uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

    **Requires**

    * [require(..., "Transfer failed")](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L75)

    **Modifiers**

    * [nonReentrant](#nonreentrant)

### `close`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L32)</sub>

??? example "Details"

    **Signature**

    `close(uint256 id)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `deposit`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L38)</sub>

??? example "Details"

    **Signature**

    `deposit(address borrower, uint256 id) payable`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `draw`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L56)</sub>

??? example "Details"

    **Signature**

    `draw(uint256 id, uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `liquidate`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L60)</sub>

??? example "Details"

    **Signature**

    `liquidate(address borrower, uint256 id, uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `open`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L28)</sub>

??? example "Details"

    **Signature**

    `open(uint256 amount, bytes32 currency) payable`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `repay`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L48)</sub>

??? example "Details"

    **Signature**

    `repay(address account, uint256 id, uint256 amount)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`

### `withdraw`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.41.0/contracts/CollateralEth.sol#L42)</sub>

??? example "Details"

    **Signature**

    `withdraw(uint256 id, uint256 withdrawAmount)`

    **Visibility**

    `external`

    **State Mutability**

    `undefined`
