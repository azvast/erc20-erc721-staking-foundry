# Modern ERC20 & ERC721 Staking Foundry

This project is a set of modern, gas optimized staking pool contracts including ERC20 and ERC721.

## Features

-   Support for both ERC20 staking and ERC721 staking.
-   Can start new reward period after the current one is over.
-   Minimized error in reward computation (<10^-8) by using higher precision.
-   Well commented with NatSpec comments.
-   Fuzz tests powered by [Foundry](https://github.com/gakonst/foundry).
-   Gas optimized.
-   Cheap deployment using `ClonesWithCallData` (~81.7k gas).

## Development

This project uses [Foundry](https://github.com/gakonst/foundry) as the development framework.

### Dependencies

```
forge install
```

### Compilation

```
forge build
```

### Testing

```
forge test
```
