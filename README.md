# Gitcoin

Welcome to the wonderful world of Gitcoin!

## Overview

The balances are all contained in `LEDGER.txt`. We also have provided
you with a sample Gitcoin mining script in `miner` -- you'll probably
notice it's too slow to use in practice though. Note that for this
level you won't submit any code to us, as you'll be running everything
locally (you're welcome to email us solutions if you think they are
particularly cool, though).

The only commits that can be pushed are ones that:

- Increments an existing ledger entry by 1, or adds a new ledger entry
  with balance: 1; and
- Has a SHA1 lexicographically less than the value in `difficulty.txt`.

To check your solution you can use the following command to add a new remote:

`git remote add solution git@gitcoin.rickre.in:gitcoin.git`

and then

`git push -u solution`

## Catalog

- `difficulty.txt`: A strict upper bound on valid Gitcoin SHA1 values.

- `miner`: A sample Gitcoin mining script.

- `LEDGER.txt`: The current Gitcoin balances.

- `README.md`: This file.
