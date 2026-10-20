# Roadmap

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