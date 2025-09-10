<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/effortless-zig/branding/blob/main/effortless-zig-dark-mode.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/effortless-zig/branding/blob/main/effortless-zig-light-mode.png">
  <img alt="Effortless Zig Logo." src="https://github.com/effortless-zig/branding/blob/main/effortless-zig-light-mode.png" style="object-fit: cover; display: block;">
</picture>

**EXTREMELY WORK-IN-PROGRESS, DO NOT USE THESE LIBRARIES, THEY AREN'T ANYWHERE NEAR PRODUCTION READY YET**

Effortless Zig is a one stop shop of mainly Zig libraries/tooling for a bunch of different topics. What unites them, well it's their dedication to good code and the tenants they are built on to achieve that.

There are five (plus one) core tenants of Effortless Design and so, without further ado, all our projects aim to:
- Build from Source: All projects should maintain their own implementations or use code within the effortless eco-system rather than importing externally (the only exceptions are zig's standard library (std), and if the point of the project is to build ontop of an external one, looking at you Window's APIs).
- Make the Easy Way be the Right Way: All projects should make the easiest way of using it, the most performant, and safe way of using it. (This is where the effortless part of the name comes from.)
- Document Precisely: All projects should be well commented (where needed), well documented with markdown files, and should define their own guidelines on top of these ones where needed.
- Ensure Reliability via Testing: Anything complex, error-prone, and/or (most importantly) relied on, must be tested (this is most of the codebase). Those tests must then be maintained to the same standard as the projects itself.
- Be Effortlessly Stylish: All projects should follow the style guide.

*Bonus Tenant:*
- Embrace the Chill: We are here to design great software, not start wars over some project. If things get heated, go touch some grass (you'll feel better).

And remember, we enforce rules not because they are fun but because effective, followed, and well-defined rules are the first line of defence against bad code.

## Our Projects
### Data Management and Storage
- [Effortless Hoard](https://github.com/effortless-zig/effortless-hoard): Easy storage, management, and access for all you data hoarders out there.
