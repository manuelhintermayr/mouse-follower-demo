# Third-Party Notices

**mouse-follower-demo** is a static showcase (a single `index.html`) that loads all
of its third-party libraries from public CDNs. No third-party library source is
vendored (redistributed) in this repository; each library is referenced at runtime
from its CDN. This document records those dependencies and separates them from the
project's own code.

## 1. Own source code

The project's own source code is licensed under the **MIT License**
(see [LICENSE](LICENSE)), Copyright (c) 2025 Manuel Hintermayr.

## 2. Third-party libraries (loaded via CDN)

| Library | Author | Role | License |
|---|---|---|---|
| [Mouse Follower](https://github.com/Cuberto/mouse-follower) | Cuberto | The cursor-effect library this demo showcases | **MIT** |
| [GSAP](https://gsap.com/) / ScrollTrigger | GreenSock | Animation (required by Mouse Follower) | Free to use under GreenSock's standard "No Charge" license — see the GSAP website for current terms |
| [Vue 3](https://vuejs.org/) | Vue.js | UI reactivity | MIT |
| [Tailwind CSS](https://tailwindcss.com/) | Tailwind Labs | Styling (play CDN) | MIT |

Each library remains under its own license and copyright; refer to the respective
project for the authoritative license text.

## 3. Trademarks

Product and project names referenced above are the property of their respective
owners and are used for identification only.
