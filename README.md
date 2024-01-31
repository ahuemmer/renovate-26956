###### [Renovate Discussion #26956](https://github.com/renovatebot/renovate/discussions/26956)

The behavior in the discussion can be seen in this repository. Both `k8s-works.yml` and `k8s-doesntwork.yml` contain a reference to an out-of-date docker image.

However, an update PR ist just created for `k8s-works.yml` and not for `k8s-doesntwork.yml`. The only difference between both files is the line break using `>-` (which is fully allowed in YAML).
