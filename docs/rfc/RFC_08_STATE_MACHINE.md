# RFC-08: Leave Workflow Finite State Machine

- States: SUBMITTED -> HOD_APPROVED -> PRINCIPAL_APPROVED
- Audit Trail: Immutable event log with cryptographic digest
- Rollback: Atomic database transactions on state violation