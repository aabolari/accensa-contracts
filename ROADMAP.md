# Roadmap

## Issue #780: rustdoc for ShardStats's 5 exported fields

- [x] Document the struct's 5 public fields (#780)
  - `contracts/receipt-shard/src/diagnostics.rs` — doc comments only, field/type/order/derives unchanged

## Issue #708: refund-vault coupon and liquidity test coverage

- [x] Add refund-vault coupon and liquidity test coverage (#708)

## Issue #709: refund-vault integration test coverage

- [x] Cover NFT transfers, emergency yield exit, and yield distribution (#709)

## Issue #443: stACC liquid staking derivative minting

- [x] Implement stACC liquid staking derivative minting (#443)
  - New `liquid_staking` module in `contracts/governance/src/liquid_staking.rs`
  - 1:1 mint/burn of stACC against locked underlying tokens
  - Exchange rate progression and lock-epoch-based redemption
  - CHANGELOG.md entry added

## Issue #707: test refund-vault effective_fee_bps, reg_vdf_policy, nft_owner

- [x] Add tests for `effective_fee_bps`, `reg_vdf_policy`, and `nft_owner` in `contracts/refund-vault/src/tier_tests.rs`

## Issue #706: test refund-vault resolve_ceiling, split_amount, reg_time_policy

- [x] Add tests for `resolve_ceiling`, `split_amount`, and `reg_time_policy` in `contracts/refund-vault/src/settlement_test.rs`

## Issue #705: test refund-vault set_active, set_recipient, recall_principal

- [x] Add tests for `set_active`, `set_recipient`, and `recall_principal` in `contracts/refund-vault/src/reentrancy_tests.rs`

## Issue #704: test refund-vault median_price, evaluate_policy, is_approved

- [x] Add tests for `median_price`, `evaluate_policy`, and `is_approved` in `contracts/refund-vault/src/oracle_tests.rs`
