---
date: 2018-07-26T17:19:24Z
title: "jx delete addon cloudbees"
slug: jx_delete_addon_cloudbees
url: /commands/jx_delete_addon_cloudbees/
---
## jx delete addon cloudbees

Deletes the CloudBees app for Kubernetes addon

### Synopsis

Deletes the CloudBees addon

```
jx delete addon cloudbees [flags]
```

### Examples

```
  # Deletes the CloudBees addon
  jx delete addon cloudbees
```

### Options

```
  -h, --help             help for cloudbees
  -p, --purge            Removes the release name from helm so it can be reused again (default true)
  -r, --release string   The chart release name (default "cb")
```

### SEE ALSO

* [jx delete addon](/commands/jx_delete_addon/)	 - Deletes one or many addons

###### Auto generated by spf13/cobra on 26-Jul-2018
