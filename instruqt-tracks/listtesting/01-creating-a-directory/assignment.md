---
slug: creating-a-directory
id: atmtxvy9xm9e
type: challenge
title: Creating a directory
teaser: testing teaser challenge level
notes:
- type: text
  contents: <h2 style="color:red;margin-left:40px;">These are the Test notes </h2>
tabs:
- title: Shell
  type: terminal
  hostname: container
difficulty: ""
timelimit: 600
---

`sudo su`

```
# control-repo/manifests/site.pp
node default {
  include "role::${trusted['extensions']['pp_role']}"
}
```



