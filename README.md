I'm a Platform Engineer, tool maker, and OSS contributor. I love Go. Please see [profile](https://suzuki-shunsuke.github.io/profile/) and [resume](https://github.com/suzuki-shunsuke/resume) too.
I'm passionate about the automation and improving the developer experience and security of CI.
Especially, I continue improving the workflow of Terraform for a long time.
I've developed tons of OSS with Go and contributed to a lot of OSS.
I've published a lot of blog posts to share my knowledge and work.

## Tech Stack

- Go, Shell Script
- AWS, Google Cloud
- GitHub Actions, CircleCI, AWS CodeBuild, Google Cloud Build, Drone
- Docker, k8s
- Terraform, Ansible
- Renovate, Conftest, DataDog

## Speaking

date | event | style | presentation title
--- | --- | --- | ---
2021-09-30 | [HashiTalks Japan 2021](https://events.hashicorp.com/hashitalksjapan) ([youtube](https://www.youtube.com/watch?v=Cl9S-uzkuLc)) | Talk (30 min) | [Terraform Platform in Quipper](https://speakerdeck.com/szksh/terraform-platform-in-quipper) ([youtube](https://www.youtube.com/watch?v=KpYwcwxnzbY))
2021-07-07 | [Open Policy Agent Rego Knowledge Sharing Meetup](https://mercari.connpass.com/event/211073/) ([youtube](https://youtu.be/0YpJhrz6L0A)) | LT (5min) | [Quipper における Rego の活用事例](https://gist.github.com/suzuki-shunsuke/9372337aa62a6f8394bb136582ec068e) ([youtube](https://youtu.be/0YpJhrz6L0A?t=870))

## Activity as OSS Collaborator

date | repository
--- | ---
2020-11-29 / now | [kreuzwerker/terraform-provider-docker](https://github.com/kreuzwerker/terraform-provider-docker)
2018-07-12 / 2019-06-25 | [line/line-bot-sdk-go](https://github.com/line/line-bot-sdk-go)

## OSS Contribution

I have contributed various OSS. [Full List](https://suzuki-shunsuke.github.io/profile/oss-contribution)

- [Terraform AWS Provider](https://github.com/hashicorp/terraform-provider-aws/pulls?q=is%3Apr+author%3Asuzuki-shunsuke+is%3Aclosed)
- [Renovate](https://github.com/renovatebot/renovate/pulls?q=is%3Apr+author%3Asuzuki-shunsuke+is%3Aclosed)
- [slsa-verifier](https://github.com/slsa-framework/slsa-verifier/pulls?q=is%3Apr+author%3Asuzuki-shunsuke+is%3Aclosed)
- [go-client-mongodb-atlas](https://github.com/mongodb/go-client-mongodb-atlas/pulls?q=is%3Apr+author%3Asuzuki-shunsuke+is%3Aclosed)

## OSS Development

I have developed various OSS. [Full List](https://suzuki-shunsuke.github.io/profile/oss-development)

- [aqua](https://github.com/aquaproj/aqua) - Declarative CLI Version manager. Support Lazy Install and Sharable configuration mechanism named Registry. Version is switched seamlessly
- [tfcmt](https://github.com/suzuki-shunsuke/tfcmt) - Fork of mercari/tfnotify. tfcmt enhances tfnotify in many ways, including Terraform >= v0.15 support and advanced formatting options
- [tfaction](https://github.com/suzuki-shunsuke/tfaction) - Framework for Monorepo to build high level Terraform Workflows by GitHub Actions
- [github-comment](https://github.com/suzuki-shunsuke/github-comment) - CLI to post and hide GitHub Pull Request Comments with YAML configuration file
- [Graylog API client for Go and terraform provider for Graylog](https://github.com/suzuki-shunsuke/go-graylog)
- [tfmigrator](https://github.com/tfmigrator/cli) - Go library and CLI to migrate Terraform Configuration and State
- [pinact](https://github.com/suzuki-shunsuke/pinact) - Pin GitHub Actions versions
- [tfprovidercheck](https://github.com/suzuki-shunsuke/tfprovidercheck) - CLI to prevent malicious Terraform Providers from being executed. You can define the allow list of Terraform Providers and their versions, and check if disallowed providers aren't used
- [ghalint](https://github.com/suzuki-shunsuke/ghalint) - GitHub Actions Linter
- [flute](https://github.com/suzuki-shunsuke/flute) - Go HTTP client testing framework
- [cmdx](https://github.com/suzuki-shunsuke/cmdx) - Task Runner
- [ci-info](https://github.com/suzuki-shunsuke/ci-info) - CLI tool to get CI related information
- [asciinema-trim](https://github.com/suzuki-shunsuke/asciinema-trim) - Trim and change the playback speed of asciinema's session
- [github-ci-monitor](https://github.com/suzuki-shunsuke/github-ci-monitor) - Monitor GitHub repositories CI statues by DataDog

## Documents

name | description
--- | ---
[oss-contribution-guide](https://github.com/suzuki-shunsuke/oss-contribution-guide) | OSS Contribution Guide
[guide-github-action-renovate](https://suzuki-shunsuke.github.io/guide-github-action-renovate/) | Guide for building nice GitHub Actions Workflows with Renovate

## Blog

I have written many blog posts to share my knowledge.

- English
  - [dev.to](https://dev.to/suzukishunsuke)
  - [Medium](https://medium.com/@suzuki.shunsuke.1989)
- Japanese
  - https://zenn.dev/shunsuke_suzuki
  - https://techblog.szksh.cloud

[Full list of blogs](https://suzuki-shunsuke.github.io/profile/blog)

I picked out some blog posts below.

### Japanese

date | tags | title
--- | --- | ---
2023-10-01 | aqua | [aqua CLI Version Manager 入門](https://zenn.dev/shunsuke_suzuki/books/aqua-handbook)
2023-10-22 | GitHub Actions, security | [pull_request_target で GitHub Actions の改竄を防ぐ](https://zenn.dev/shunsuke_suzuki/articles/secure-github-actions-by-pull-request-target)
2023-05-14 | GitHub Actions, Renovate, security | [GitHub Actions による Renovate の安全自動マージ](https://zenn.dev/shunsuke_suzuki/articles/renovate-auto-merge-github-actions)
2022-02-18 | Renovate, CI | [Renovate の大量の Pull Request を処理する技術](https://blog.studysapuri.jp/entry/2022/02/18/080000)
2022-02-04 | terraform, GitHub Actions | [Terraform の CI を AWS CodeBuild から GitHub Actions + tfaction に移行しました](https://blog.studysapuri.jp/entry/2022/02/04/080000)
2021-08-02 | terraform | [AWS IAM の管理を miam から Terraform に移行した話](https://blog.studysapuri.jp/entry/2021/08/02/080000)
2021-04-01 | terraform, CI | [Terraform リポジトリをマージして CI/CD を改善した話](https://blog.studysapuri.jp/entry/2021/04/01/080000)
2023-11-05 | terraform, security | [tfprovidercheck - 危険な Terraform Provider の実行を防ぐ](https://zenn.dev/shunsuke_suzuki/articles/tfprovidercheck-introduction)
2023-05-01 | GitHub Actions, security | [pinact - GitHub Actions のバージョンを commit hash で固定](https://zenn.dev/shunsuke_suzuki/articles/pinact-pin-github-actions-version)
2023-02-12 | GitHub Actions, security | [GitHub Actions の secrets の公開範囲と permissions を最小限にする](https://zenn.dev/shunsuke_suzuki/articles/github-actions-ghalint)
2023-06-05 | tfaction, terraform | [tfaction による Terraform の Drift Detection](https://zenn.dev/shunsuke_suzuki/articles/tfaction-drift-detection)
2021-12-28 | CI | [github-comment で PR にコメントをして CI の結果を分かりやすくする](https://zenn.dev/shunsuke_suzuki/articles/improve-cicd-with-github-comment)
2021-12-26 | terraform, CI | [tfcmt で Terraform の CI/CD を改善する](https://zenn.dev/shunsuke_suzuki/articles/improve-terraform-cicd-with-tfcmt)

### English

date | tags | title
--- | --- | ---
2023-10-23 | GitHub Actions, security | [Secure GitHub Actions by pull_request_target](https://dev.to/suzukishunsuke/secure-github-actions-by-pullrequesttarget-641)
2023-11-05 | terraform, security, CI | [Prevent malicious Terraform Providers](https://dev.to/suzukishunsuke/prevent-malicious-terraform-providers-m1)
2023-06-06 | terraform, CI | [Terraform's Drift Detection by tfaction](https://dev.to/suzukishunsuke/terraforms-drift-detection-by-tfaction-1dkh)
2022-01-21 | terraform, CI | [tfcmt - Improve Terraform Workflow with PR Comment and Label](https://dev.to/suzukishunsuke/tfcmt-improve-terraform-workflow-with-pr-comment-and-label-1kh7)
2023-02-12 | GitHub Actions, security | [Minimize the scope of secrets and permissions in GitHub Actions](https://dev.to/suzukishunsuke/minimize-the-scope-of-secrets-and-permissions-in-github-actions-444b)
2022-05-29 | terraform, Renovate, CI | [Automate handling a number of Pull Requests by Renovate in Terraform Monorepo](https://devs.quipper.com/2022/03/29/automate-handling-a-number-of-pull-requests-by-renovate-in-terraform-monorepo)
2022-02-25 | terraform, GitHub Actions | [Migrate Terraform CI from AWS CodeBuild to GitHub Actions](https://devs.quipper.com/2022/02/25/terraform-github-actions)
2021-09-26 | Renovate | [Tips about Renovate](https://dev.to/suzukishunsuke/tips-about-renovate-38bd)
