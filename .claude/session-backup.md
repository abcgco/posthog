2026-03-29 12:46:21
# Session Backup (pre-compaction)

## Git State
master
cfaed59dd1 fix: restart: always for db, redis7, zookeeper, kafka, clickhouse
0e6dc1e35c fix: enable ZooKeeper autopurge to prevent disk exhaustion
97d629c29e fix: remove build_posthog CI stage, image built in pre-commit
826c5026f2 fix: restore pre-commit Docker image build
b46c55efad fix: remove upstream PostHog GitHub Actions workflows
87389a918c feat: add build_posthog CI stage, disable local image build in pre-commit
ed9c2f3a4f feat: enable Django admin portal on deploy
349d5ca31e feat: add ENABLE_WEB_EXPERIMENTS env var for self-hosted web experiments
9c73872bc5 fix: use SITE_URL for toolbar apiURL instead of request scheme
4d69fd341c feat: custom deployment config with env vars

## Modified Files

