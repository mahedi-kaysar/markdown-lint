---
title: MD020 - No space inside hashes on closed atx style header
tags:  [headers, atx_closed, spaces]
alias: no-missing-space-closed-atx
---

This rule is triggered when spaces are missing inside the hash characters
in a closed atx style header:

    #Header 1#

    ##Header 2##

To fix this, separate the header text from the hash character by a single
space:

    # Header 1 #

    ## Header 2 ##

Note: this rule will fire if either side of the header is missing spaces.

