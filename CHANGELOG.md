All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [v0.11.0](https://github.com/nervosnetwork/ckb-sdk-ruby/compare/v0.10.0...v0.11.0) (2019-05-14)


### Features

* add RPC `get_block_by_number` ([c410ec3](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/c410ec3))


### BREAKING CHANGES

* rename variables ([a59158b](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/a59158b))
  * rename OutPoint `hash` to `tx_hash`
  * rename Script `binary_hash` to `code_hash`
  * rename Input `valid_since` to `since`
  * rename Block `commit_transactions` to `transactions`
* update test of `get_transaction` for structure changes ([3b8c637](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/3b8c637))
* use shannon as capacity unit ([9a013ae](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/9a013ae))


# [v0.10.0](https://github.com/nervosnetwork/ckb-sdk-ruby/compare/v0.9.0...v0.10.0) (2019-05-06)

### Bug Fixes

* capacity in RPC interface changed to string ([d8d3d05](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/d8d3d05))
* remove version from script ([9348185](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/9348185))


### Features

* use 0x-prefix hex string represent block assembler args ([171e08e](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/171e08e))



# [v0.9.0](https://github.com/nervosnetwork/ckb-sdk-ruby/compare/v0.8.0...v0.9.0) (2019-04-22)

### Bug Fixes

* fix code per CKB's latest changes ([7505edf](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/7505edf))
* fix segwit logic ([460caab](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/460caab))
* Fix tests ([0afc5bc](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/0afc5bc))
* fix the bug in transaction generation ([ca33aa7](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/ca33aa7))
* Fix the bug that shared lock gets modified when sending tx ([21092de](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/21092de))
* fix witnesses format ([d87d9d8](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/d87d9d8))
* remove duplicated lock in wallet ([e814920](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/e814920))


### Features

* Address format implementation ([4c543bf](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/4c543bf))
* support segwit ([6959395](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/6959395))
* Upgrade SDK with latest CKB changes ([ae5c1c5](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/ae5c1c5))



# [v0.8.0](https://github.com/nervosnetwork/ckb-sdk-ruby/compare/v0.7.0...v0.8.0) (2019-04-08)

### Bug Fixes

* fix tx rpc tests logic



# [v0.7.0](https://github.com/nervosnetwork/ckb-sdk-ruby/tree/v0.7.0) (2019-03-22)


### Features

* add basic wallet ([2e14b49](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/2e14b49))
* add rpc interface ([a4b1f47](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/a4b1f47))
* init project ([1cb5623](https://github.com/nervosnetwork/ckb-sdk-ruby/commit/1cb5623))
* extract from ([ckb-demo-ruby](https://github.com/nervosnetwork/ckb-demo-ruby))
