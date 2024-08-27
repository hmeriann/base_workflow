This repo is an experiment to understand how to properly reuse workflows.

This Repo contains three workflows:
- base_workflow.yml
- fuzz.yml
- runs_using_base_wf.yml

`runs_using_base_wf` uses two other workflows to complete its jobs. There is also [`reuse_external_workflow`](https://github.com/hmeriann/test_/blob/main/.github/workflows/reuse_external_workflow.yml) which also reuses the same workflows, but from the outer repository.
