# Hi, I'm Angad

I am a freshman at the University of Maryland. Most of my projects involve robots, physics, random tooling, or shoving Rust into places it doesn't belong. Here are some of my favorites.

## Projects

### [`fluidsim`](https://codeberg.org/tendulkar/fluidsim)

A 2D SPH fluid simulation that I upgraded to 3D for my AP Physics final project. Sebastian Lague's [first fluid simulation video](https://www.youtube.com/watch?v=rSKMYc1CQHE) was a big inspiration. Somehow, I managed to write everything in Rust, including `wgpu` for the host code and `rust-gpu` for the shaders, which compiled to SPIR-V.

I wrote about [making the 2D version](https://angad.page/blog/fluid-simulation/) and [dragging it into the third dimension](https://angad.page/blog/fluid-simulation-in-3-dimensions/).

### [`protein`](https://github.com/Team2791/Protein-2026)

Although not a solo project, my biggest personal accomplishment in the 2026 FRC season was pioneering the use of a Meta Quest 3S to replace PhotonVision entirely, giving us the most accurate localization we've ever had _and_ getting us an Innovation in Controls award, finally completing our [award hexfecta](https://bcr2200.github.io/hexfecta/html_output/2791.html).

Better pose estimates also let me completely redesign our autonomous around a position-based pathfinder rather than the velocity- and time-based trajectory following used by both Choreo and PathPlanner. Although slightly slower (mostly due to a lack of time to tune my algorithm), our routines could recover from bumps, wheel slippage, and temporary jams.

I could never have done this without the help of Dev Bhatia, Naomi Li, or Sidney Xia.

Named after this wonderful old game piece I found at our practice field.
![Protein](https://codeberg.org/tendulkar/.profile/raw/branch/main/protein.jpg)

### [`attendance`](https://codeberg.org/tendulkar/attendance)

An attendance system for FRC teams, because Google Forms and spreadsheets were kind of a pain. It has an end-to-end encrypted student database with WebAssembly on the client, a [generated OpenAPI schema](https://attendance.team2791.org/api/docs), and [the only fully type-safe form library I've ever seen](https://codeberg.org/tendulkar/attendance/src/branch/main/app/utils/form).

You can also just [click a button](https://railway.com/deploy/frc-attendance?referralCode=Y3VMtD&utm_medium=integration&utm_source=template&utm_campaign=generic) to deploy it yourself, which I find to be very cool.

### [`angadOS`](https://codeberg.org/tendulkar/angados)

Truly the epitome of "shoving Rust in places it doesn't belong:" a tiny operating system for RISC-V, written from scratch, in Rust. Although it's temporarily on ice while I work on other stuff, I hope to come back to it and hopefully (re)do a large portion in C.

### [`jasmine`](https://codeberg.org/tendulkar/jasmine)

This started as a janky programming language that transpiled Rust-ish code into Java, mostly because I was taking AP Computer Science and did not enjoy writing boilerplate. Currently, I'm working on hacking `rustc` to see if I can get the combined power of the MIR, HIR, and THIR to get some actual Rust compiling up to Java.

### [`kbnt`](https://codeberg.org/tendulkar/kbnt) -- Keyboard over NetworkTables

We got fancy new controllers with extra paddles which could act as keyboard keys, but not as separate controller buttons. I wrote an itty-bitty Rust program, making use of some low-level Windows API hooks to catch those keypresses and send them to the robot.

It also got [flagged as a keylogger by my school’s antivirus](https://angad.page/blog/kbnt/).

### [`mensura`](https://codeberg.org/tendulkar/mensura)

A units-of-measure library I made in about a day and will probably use for every physics-related project from here on out. `uom` takes too long to compile, what else can I say?

### Other rabbit holes

I contributed [dynamic NetworkTables struct parsing](https://github.com/Gold872/elastic_dashboard/pull/225) to Elastic Dashboard, maintain a k3s homelab (working on publishing GitOps), and once made a proof-of-concept chessboard that moved pieces with electromagnets.
