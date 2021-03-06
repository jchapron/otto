---
layout: "app_ruby"
page_title: "Customization - Ruby App Type"
sidebar_current: "docs-ruby-customization"
description: |-
  This page documents the [Customizations](/docs/appfile/customization.html)
  that are availabile to change the behavior of Ruby applications with Otto.
---

# Customization

This page documents the [customizations](/docs/appfile/customization.html)
that are availabile to change the behavior of Ruby applications with Otto.

## Type: "ruby"

Example:

```
customization "ruby" {
    ruby_version = "2.1"
}
```

Availabile options:

  * `ruby_version` (string) - The Ruby version to install for development
    and deployment. This defaults to 2.2.
