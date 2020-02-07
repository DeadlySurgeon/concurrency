# Concurrency

[This exists to prove a point.](https://crates.io/crates/concurrency)

```
[1:25 PM]  ARustyDev: Ehh, imo package management itself is kinda broken no matter how you implement it
[1:25 PM]  Typhlosion: yeah, but this was an easy pitfall that if they looked at any other package managers then they'd see it
[1:25 PM]  ARustyDev: I don't disagree with you but even if they namespaced it, how do you tell which one is the one you want
[1:26 PM]  ARustyDev: There's going to be 100 other people that reserved the crate named concurrency you know
[1:27 PM]  Typhlosion: by star count like a sane package manager?
[1:27 PM]  Typhlosion: cause when you search for concurrency, <insert name>/concurrency will have 1000 stars while <insert name>/concurrency might only have 2.
[1:28 PM]  Typhlosion: which, is the case for any other non global namespace package manager
```

Rust needs to not have a global package namespace. It's dumb and stupid and
its only a matter of time before left-pad happens to it, or where someone's 
name just so happens to be a "trademarked" name and they lose access to it.

If anyone wants this crate, it's being held ransom. The price is a not shit
package manager for Rust.
