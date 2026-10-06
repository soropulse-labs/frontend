# API compatibility

- Backend inspected: `soropulse-labs/backend` at commit `d913d696743c5b2663e441adfb305830c21c674c` (default branch at inspection time).
- Contracts repository: `soropulse-labs/contracts` (no live deployment manifest was available during frontend setup).

The frontend is currently demo-first. Its overview and explorer use deterministic local fixtures. Live authentication and mutations are intentionally not enabled until the backend handoff schemas and deployment origin are verified. The backend documentation describes auth, events, deliveries, endpoints, subscriptions, consumers, receipts, replay, and failure-lab routes, but several request/response models and live readiness guarantees remain incomplete. No unsupported endpoint is called by this build.
