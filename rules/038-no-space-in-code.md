---
title: MD038 - Spaces inside code span elements
tags:  [whitespace, code]
alias: no-space-in-code
---

This rule is triggered on code span elements that have spaces right inside the
backticks:

    ` some text `

    `some text `

    ` some text`

To fix this, remove the spaces inside the codespan markers:

    `some text`


