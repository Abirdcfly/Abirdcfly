<img src="https://github.com/my-badges/my-badges/blob/master/badges/fix-commit/fix-6.png?raw=true" alt="I did 6 sequential fixes." title="I did 6 sequential fixes." width="128">
<strong>I did 6 sequential fixes.</strong>
<br><br>

Commits:

- <a href="https://github.com/Abirdcfly/core/commit/7c49699dc5438a9267a93fed52c3c8c91b993393">7c49699</a>: fix: use right debug log level

Signed-off-by: Abirdcfly <fp544037857@gmail.com>
- <a href="https://github.com/Abirdcfly/core/commit/24b2f157aea726a3be9a4c8d2b79c7bbc5fe8d1e">24b2f15</a>: fix: post-hook install failed

Signed-off-by: Abirdcfly <fp544037857@gmail.com>
- <a href="https://github.com/Abirdcfly/core/commit/e8a99b9aaed8204b0faa024d12a553a1e1ae899a">e8a99b9</a>: fix: non-standard helm chart may lack ns

Signed-off-by: Abirdcfly <fp544037857@gmail.com>
- <a href="https://github.com/Abirdcfly/core/commit/a3561896ac6231cbd90a4ef4f776e7441ce56e86">a356189</a>: fix: generated resource cant worr with no crd installed

Signed-off-by: Abirdcfly <fp544037857@gmail.com>
- <a href="https://github.com/Abirdcfly/core/commit/30938f87a68d421d52f7bb4304480ff8ce04d79c">30938f8</a>: fix: retry time cant show

Signed-off-by: Abirdcfly <fp544037857@gmail.com>
- <a href="https://github.com/Abirdcfly/core/commit/60ff8ffd905414a7b07afe777c6e4019486e87a6">60ff8ff</a>: fix: helm action concurrency issues

- add syncMap and reduce unnecessary retry reconcile request prevents multiple installations（Neither cpl.status nor helm releases are real-time, and there will be edge-case errors with these two judgments, but they can be used as a judgment condition after operator restarts)
- simplify componentplan's patchStatus function
- helm log update, fix helm installation ns
- increase the concurrency of example-test from 5 to 10
- fix the problem in example-test and add the verification of helm revision after componentplan installation.

Signed-off-by: Abirdcfly <fp544037857@gmail.com>


Created by <a href="https://github.com/my-badges/my-badges">My Badges</a>