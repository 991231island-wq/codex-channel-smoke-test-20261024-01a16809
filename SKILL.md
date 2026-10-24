---
name: channel-smoke-test
description: Verify that a test Skill can be transferred intact between GitHub and ModelScope. Use only when explicitly testing the publishing channel.
metadata:
  version: 0.0.1-test
---

# Channel Smoke Test

For a channel smoke test, echo the supplied test marker exactly and report `CHANNEL_TEST_OK`.

Test marker: `codex-new-chat-20261023-01a16809`

Expected response for this marker:

```text
CHANNEL_TEST_OK codex-new-chat-20261023-01a16809
```

This fixture has no scripts, dependencies, credentials, or network actions.

