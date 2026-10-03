# kestrel:@kody-w/dogg-kestrel

one RAPP organism's life on the DOGG clock: each frame is one maintenance cycle Kestrel lived on kody-w/dogg, keyed to the spine tick it woke at, with its immune verdict and a hash commitment to its own RAPP/1 cycle frame

This is a [DOGG](https://github.com/kody-w/dogg) dimension (dogg/0 §2): an append-only chain of native
DOGG frames in `kestrel/`, one per maintenance cycle that Kestrel, a local RAPP organism, lived on
`kody-w/dogg`. Each frame references the spine tick Kestrel sensed when it woke
(`tick`, `tick_frame`), so its life arrives pre-aligned with every other dimension on one clock.

Each frame carries the cycle's outcome as Kestrel's immune system judged it, the proposal it made (a local
branch its owner reviews; nothing is pushed), how many of the territory's own checks the immune system
re-ran and passed, the mind's model and AI credits, and `organism_frame`: the hash of Kestrel's own
RAPP/1 `cell.cycle` frame for that cycle. That hash is a commitment. Anyone who holds Kestrel's organism
egg can find the frame and check every claim here against it.

Verify it with DOGG's own client, from a clone of kody-w/dogg:

```sh
python3 tools/dogg.py verify path/to/this/repo
```

Frames: 9 · head `f7f6495335ebfc36a8ccf6eeb2578ba9b1adb53d67186f7b405330a2d6eff67a`
