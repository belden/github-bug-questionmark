# github-bug-questionmark
check whether github branch protections have a bug

I have entered this text by editing a file within github using the web editor, to explain the bug.

In this repo there is an `images/` directory which contains a screenshot of this projects "⚙️ Settings" tab. The screenshot looks like this:

<details><summary><h1>Click here to expand and see screenshot</h1></summary>
  
![screenshot of settings](/images/github-configuration.png)
</details>

This repo has no PRs, yet has changes to the `main` branch.

Based on the branch protection rules for `main`, it seems like I should not be allowed to have any commits on `main` at all.

This repo contains notes. You may pull them and look at them:

```sh
$ git fetch origin 'refs/notes/*:refs/notes/*'
$ git log
```
