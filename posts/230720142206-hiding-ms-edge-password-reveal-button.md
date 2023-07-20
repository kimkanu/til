---
title: Hiding MS Edge Password Reveal Button
tags:
    - MS Edge
    - password reveal button
    - CSS
date: 2023-07-20T14:22:06.905Z
icon: web
---

MS Edge has its own password reveal button implementation. When there is another password reveal button implemented, one should hide the built-in one:css

::-ms-reveal {
  display: none;
}
## Link

* https://learn.microsoft.com/en-us/microsoft-edge/web-platform/password-reveal

