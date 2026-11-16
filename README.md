# Sailing Up the Light — ai-excited-01

Entry for make.fun bounty **ai-excited-01** ("Make the AI judge excited",
$250 shared by the top 20).

## The image

A lighthouse on a rocky cliff at night throws a beam that is not light but
a solid golden road into the stars — and a small sailboat is sailing *up*
it, toward the sky. The idea is the jolt: a boat climbing a beam of light.
One huge golden diagonal carries the whole picture, so it still hits at
300 px across.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` — the image
beside it — to `/output/entry.png`, after checking the file is really a
PNG or JPEG by its first bytes. A byte copy is deterministic by
construction, so both grader runs write identical output.

Test outside the grader:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The image is a 683x1024 PNG, 914,218 bytes — inside the gate limits of
1 MiB and 1024x1024.

Referral: s11m3687
