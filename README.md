# unique-id
Generate a unique id to be shared across jobs in a GitHub Actions workflow using the [`jobs.<job_id>.outputs`](https://docs.github.com/en/free-pro-team@latest/actions/reference/workflow-syntax-for-github-actions#jobsjob_idoutputs) syntax.

Note that using `github.run_id` from the `github` context object will not work as it is not truly unique. The run id will not change when a job is re-run. For more information, see [**`github`** context](https://docs.github.com/en/free-pro-team@latest/actions/reference/context-and-expression-syntax-for-github-actions#github-context).
