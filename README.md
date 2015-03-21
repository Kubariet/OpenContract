# openContract

### Overview

### Model for Metacoins
```
/*
 * to:
 * User the contract is being sent to
 * from:
 * User the contract is being sent from
 * hash:
 * SHA-256 hash of contract pdf/plain text to verify contract integrity
 * status:
 * Pending request=0, Contract Signed=1, Contract Rejected=2
 */
{
  to: $user_contract_sent_to,
  from: $user_contract_from,
  hash: $contract_hash,
  status: [0, 1, 2]
}
```
