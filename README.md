Rust systems engineer near Barcelona, Spain. Worked on Ethereum execution
clients, compilers and more low level code.

Open to Rust roles.

## Work

- [**ethrex**](https://github.com/lambdaclass/ethrex) - Ethereum execution client
  in Rust. Implemented EIP-7928 block-level access
  lists end to end: spec, peer exchange over `eth/71`, parallel execution and
  metrics. Shipped Glamsterdam and Hegotá fork support, tested on cross-client
  devnets. Most of my time went to performance on LEVM and the state layer:
  opcode dispatch, parallel merkleization, batched storage reads.
  [Writeup](https://edgl.dev/blog/bal-in-ethrex/)
- [**cairo_native**](https://github.com/starkware-libs/cairo_native) - Compiler
  from Cairo's Sierra IR to MLIR, for Starknet contracts. *LambdaClass,
  2022-2025.*
- [**concrete**](https://github.com/lambdaclass/concrete) - Systems language
  built on LLVM and MLIR.

## Maintaining

- [**melior**](https://github.com/mlir-rs/melior) - Rustic MLIR bindings in Rust.

## Side Projects

- [**edos**](https://github.com/edg-l/edos): Hobby x86_64 operating system written
  from scratch in Rust, with an SMP kernel, its own filesystem, TCP/IP and USB
  stacks, and a window manager ([edos.edgl.dev](https://edos.edgl.dev))
- [**blitz**](https://github.com/edg-l/blitz): Compiler backend for x86-64 that
  does optimization and instruction selection in a single e-graph
- [**edlang**](https://github.com/edg-l/edlang): Experimental statically-typed
  compiled language made with LLVM and Rust
- [**irvm**](https://github.com/edg-l/irvm): IR compiler target with a Rust-native
  API that lowers to LLVM IR
- [**rysk**](https://github.com/edg-l/rysk): RISC-V (RV64G) emulator
- [**homura**](https://github.com/edg-l/homura): Rust ML inference framework built
  on MLIR
- [**paypal-rs**](https://github.com/edg-l/paypal-rs): Async, strongly typed Rust
  wrapper for the PayPal API. Published crate with real users
- [**sitewriter**](https://github.com/edg-l/sitewriter): Rust library to generate
  sitemaps
- [**ddnet**](https://github.com/ddnet/ddnet): DDraceNetwork, a free cooperative
  platformer game. Contributor

## Blog

Latest entries from [edgl.dev](https://edgl.dev/):

- 2026-08-10: [Creating an x86_64 kernel in Rust: Part 4](https://edgl.dev/blog/creating-a-kernel-p4/)
- 2026-08-10: [Creating an x86_64 kernel in Rust: Part 3](https://edgl.dev/blog/creating-a-kernel-p3/)
- 2026-05-23: [How Block Access Lists are implemented in ethrex](https://edgl.dev/blog/bal-in-ethrex/)
- 2026-03-10: [New Programming Languages Have an AI Problem](https://edgl.dev/blog/ai-language-adoption/)
- 2025-08-30: [Creating an x86_64 kernel in Rust: Part 2](https://edgl.dev/blog/creating-a-kernel-p2/)

<details>
<summary>Good Reads</summary>

> To follow the path:
> look to the master,
> follow the master,
> walk with the master,
> see through the master,
> become the master.

> The programmer, like the poet, works only slightly removed from pure thought-stuff. He builds his castles in the air, from air, creating by exertion of the imagination. Few media of creation are so flexible, so easy to polish and rework, so readily capable of realizing grand conceptual structures.... Yet the program construct, unlike the poet's words, is real in the sense that it moves and works, producing visible outputs separate from the construct itself.
>
> —Fred Brooks, The Mythical Man-Month

- [How To Become A Hacker](http://www.catb.org/~esr/faqs/hacker-howto.html) by Eric Steven Raymond (hackers as in builders)
- [Writing an OS in Rust](https://os.phil-opp.com/) by Philipp Oppermann
- [Just for Fun. No, Really](https://justforfunnoreally.dev/)
- <https://www.hardmo.de/article/2021-03-14-zst-proof-types.md>
- [AMD64 Architecture Programmer's Manual Volume 2: System Programming](https://docs.amd.com/v/u/en-US/24593_3.43)

</details>
