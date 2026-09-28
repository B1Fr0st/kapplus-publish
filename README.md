# KAP+ publish proof of concept

This repository contains an exact four-chunk split of the KAP+ asset demo. The small
`program.js` bootstrap is pasted into Khan Academy. It loads the immutable JavaScript
chunks through jsDelivr, reconstructs the verified program source, and executes it in
the ProcessingJS instance.

- Build ID: `4daf003314327be6`
- Original Khan source: 924,175 bytes
- Khan bootstrap: 1,889 bytes
- Source SHA-256: `4daf003314327be651261b29ea1d426f6d969e760c4cd350477ee1505a3bbae6`

The bootstrap URLs are pinned to a Git commit, so later repository changes cannot
silently alter a published Khan program.
