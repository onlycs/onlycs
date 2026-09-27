# Hi, I'm Angad

I build projects across physics simulation, robotics, and random developer tools. Here are some of my favorites.

## Projects

### `fluidsim`

A 2D SPH fluid simulation that I upgraded to 3D for my AP Physics final project. Sebastian Lague's [first fluid simulation video](https://www.youtube.com/watch?v=rSKMYc1CQHE) was a big inspiration. Somehow, I managed to write everything in Rust, including `wgpu` for the host code and `rust-gpu` for the shaders, which compiled to SPIR-V.

I wrote about [making the 2D version](https://angad.page/blog/fluid-simulation/) and [dragging it into the third dimension](https://angad.page/blog/fluid-simulation-in-3-dimensions/).

### `attendance`

An attendance system for FRC teams, because Google Forms and spreadsheets were kind of a pain. It has an end-to-end encrypted student database with WebAssembly on the client, a [generated OpenAPI schema](https://attendance.team2791.org/api/docs), and [the only fully-typesafe form library I've ever seen](https://codeberg.org/tendulkar/attendance/src/branch/main/app/utils/form).

### `angadOS`

A tiny and work-in-progress operating system for RISC-V, written in Rust (for some reason) from scratch. It's on ice while I work on other stuff, but I hope to come back to it and hopefully do a large portion in C.

### `jasmine`

This started as a janky programming language that transpiled Rust-ish code into Java, mostly because I was taking AP Computer Science and did not enjoy writing boilerplate. I'm now messing with `rustc` to see if I can get the same sort of Java output from actual Rust.

### `kbnt` -- Keyboard over NetworkTables

We got fancy new controllers with extra paddles which could act as keyboard keys, but not as seperate controller buttons. I wrote an itty-bitty Rust program, making use of some low-level Windows API hooks to catch those keypresses and send them to the robot.

It also got [flagged as a keylogger by my school’s antivirus](https://angad.page/blog/kbnt/).

### `mensura`

A units-of-measure library I made in about a day and will probably use for every physics-related project from here on out. `uom` takes too long to compile, what else can I say?

### Other rabbit holes

I contributed [dynamic NetworkTables struct parsing](https://github.com/Gold872/elastic_dashboard/pull/225) to Elastic Dashboard, maintain a k3s homelab (public ArgoCD coming soon). and once made a proof-of-concept chessboard that moved pieces with electromagnets.
