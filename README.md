# Resilient queue worker

This repository tracks the queue worker and its dated release checks.
The test command verifies the small embedded recovery index.

The October release raised the recovery batch size to 32.

## Recovery index check

Run `git -C bare status --short` from the repository root. Empty output means
the embedded recovery index is clean.
