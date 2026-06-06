# zen-daemonless-io

Publishes the [Zensical](https://zensical.org/) build of the docs to
**[zen.daemonless.io](https://zen.daemonless.io)** (a trial alongside the MkDocs
site at [daemonless.io](https://daemonless.io)).

Deploy-only — no content here. Source lives in
[`daemonless/daemonless-io`](https://github.com/daemonless/daemonless-io); the
workflow checks it out, runs `make build-zen`, and deploys `site-zen/`.

A separate repo is needed because GitHub Pages allows one domain per repo, and
daemonless-io already serves daemonless.io.
