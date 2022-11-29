UI edit to ox_target

**Showcase video**

https://user-images.githubusercontent.com/53654750/204571950-6b5314e2-3eea-4d17-af01-9c9892132d3c.mp4


<div align='center'><h2><a href='https://overextended.github.io/docs/ox_target/'>Documentation</a></h2></div>

## ox_target

A performant and flexible standalone "third-eye" targeting resource, with additional functionality when using ox_core, esx, or qb-core.

ox_target is the successor to qtarget, which was a mostly-compatible fork of bt-target.
To improve many design flaws, ox_target has been written from scratch and drops support for bt-target/qtarget standards, though partial compatibility is being implemented where possible.

- Performance increased ~4x compared to qtarget.
- Improved error handling protects against soft-locking.
- Improved entity and world collision detection.
- Options now stack, rather than overriding.
