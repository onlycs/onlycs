# Introduction? I guess

Hello, I'm Angad.

I do coding things. To be entirely honest, my projects are kind of all over the place. Here are some of my favorites though:

## Projects

### [`fluidsim`](https://codeberg.org/tendulkar/fluidsim)

A 2D SPH simulation I recently upgraded to 3D to show off for my AP Physics final project. Very much inspired by Sebastian Lague's first video. I used Rust with wgpu for the CPU side of things, and `rust-gpu` (which compiles to SPIR-V) for the GPU shaders, and absolutely no game engine after I finished the initial prototype.

Read a bit more about [the process of creating the 2D version](https://angad.page/blog/fluid-simulation/) and [upgrading to 3D](https://angad.page/blog/fluid-simulation-in-3-dimensions/)

### [`attendance`](https://codeberg.org/tendulkar/attendance)

A wonderful FRC-focused attendance tracking system, complete with an E2EE student database backed by webassembly on the client end, a completely generated [OpenAPI schema](https://attendance.team2791.org/api/docs), and [the best Vue form library ever written](https://codeberg.org/tendulkar/attendance/src/branch/main/app/utils/form).

### [`jasmine`](https://codeberg.org/tendulkar/jasmine)

Initially a janky ass programming language that transpiled something with a bit less boilerplate to Java source code, I'm currently working on hacking rustc to get the same effect (i.e. handwritten-ish Java code) but with actual Rust this time around.

### [`protein`](https://github.com/team2791/protein-2026)

Although not entirely a solo project, my biggest personal accomplishment in the 2026 FRC season was pioneering the use of a Meta Quest 3S to replace PhotonVision entirely, giving us the most accurate localization we've ever had AND getting us an Innovation in Controls award, finally completing our [award hexfecta](https://bcr2200.github.io/hexfecta/html_output/2791.html). This also enabled me to redesign autos to a position-based pathfinder rather than a velocity-based one, which was significantly more reliable than anything our team had ever put out before.

I could never have done this without the help of [Dev Bhatia](https://github.com/dev-glitch), Naomi Li, or [Sidney Xia](https://github.com/sxia123).

Named after this wonderful old game piece I found at our practice field.
![Protein](https://codeberg.org/tendulkar/.profile/raw/branch/main/protein.jpg)

### [`mensura`](https://codeberg.org/tendulkar/mensura)

Even though this took me like a day to make, this is hands-down _the_ library I will be using if I ever mess with anything physics-related again. `uom` takes too long to compile, what can I say?
