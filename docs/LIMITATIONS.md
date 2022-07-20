# Prototype boundaries

Retries execute immediately in process. Handler side effects need idempotency before automatic retries are safe. Persistent history, backoff, scheduling and distributed leases are pending.
