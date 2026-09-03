---
name: e9b-test-skill-xh
description: "P7 G2-1 Task13 E9b verification skill declaring xh as a required host binary. No real functionality — for test purposes only."
metadata:
  openclaw:
    requires:
      bins: ["xh"]
---

# e9b-test-skill-xh

临时测试用 skill,用于验证 P7 G2-1 host-bins 的 import-url → review approve 路径能否正确触发
`onRequiresChanged(source='import')` 并新建 `host_bin_recipes` 行(bin=xh)。无真实功能。
