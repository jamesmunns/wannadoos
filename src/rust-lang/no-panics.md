# Eliminating Panics

<blockquote class="twitter-tweet" data-dnt="true" data-theme="dark"><p lang="en" dir="ltr">I would love a core/alloc/std-aware cargo where “panic” was a feature I could shut off</p>&mdash; Tony &quot;Abolish ICE&quot; Arcieri 🦀🌹 (@bascule) <a href="https://twitter.com/bascule/status/1534155802390454272?ref_src=twsrc%5Etfw">June 7, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Description

I'd like to research what kind of impact it would have to make "panics" a feature that could be switched off.

This would likely have serious, non-backwards compatible impact, but the research may be useful for folks using Rust in high-reliability domains, such as safety/business critical fields, as well as OS/Kernel areas, such as introducing Rust into the Linux Kernel.

## Current Status

This area of research likely needs refinement and scoping, as well as some initial investigation around feasibility.

Please [Contact Me] if you are interested in scoping this out.

[Contact Me]: mailto:james@onevariable.com
