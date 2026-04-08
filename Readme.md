PR Created
   ↓
GitHub Actions
   ↓
Extract Diff
   ↓
Push Job → Queue (Redis / Kafka)
   ↓
Worker Picks Job
   ↓
Processing:
   - Run tests (optional here or in CI)
   - AI Review
   - Static analysis
   ↓
Send Result Back
   ↓
GitHub Status Check Updated
   ↓
Merge Allowed / Blocked
