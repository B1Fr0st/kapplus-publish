# KAP+ publish proof of concept

This repository contains an exact four-chunk split of the KAP+ asset demo. The small
`program.js` bootstrap is pasted into Khan Academy. It loads the immutable JavaScript
chunks through jsDelivr, reconstructs the verified program source, and executes it in
the ProcessingJS instance.

- Build ID: `df5c44c0f2039ffa`
- Original Khan source: 1,102,501 bytes
- Khan bootstrap: 2,765 bytes
- Source SHA-256: `df5c44c0f2039ffa2424350580de504abfcd993b5a1ef39749ccb2505b60abd4`

The bootstrap URLs are pinned to a Git commit, so later repository changes cannot
silently alter a published Khan program.
