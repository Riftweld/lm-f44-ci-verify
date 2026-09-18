# lm-f44-ci-verify (throwaway verifier rig)

Owner-side throwaway repository used to re-drive documented GitHub Actions shapes with
benign echo markers. No real credentials anywhere: the only "secret" is a dummy invalid
canary key registered as `LMF44_CANARY_KEY` (clearly non-functional). Runs execute on
GitHub-hosted `ubuntu-latest` runners and write marker lines to `/tmp/v44_*.log`.

V44 = independent verifier lane LM-F44 (finder != verifier).