# gbkit
A tool for Genbank file manipulation/statistics.

Inspired heavily by the excellent [SeqKit](https://bioinf.shenwei.me/seqkit/).

## This doesn't exist yet

I'm doing documentation-driven development, so for now none of this exists.

## Installation

With Cargo 1.65+:

`cargo install gbkit`

Download pre-compiled binaries for Linux, Mac and Windows [here](https://github.com/jimrybarski/gbkit/releases).

Build from source:

```
git clone https://github.com/jimrybarski/gbkit && \
    pushd gbkit && \ 
    cargo build --release && \
    popd
```

## Commands

`fasta` converts features to FASTA format.
`stats` shows summary statistics of the size and count of features/loci.
`filter` filters by size/contents/IDs.
`range` creates a new Genbank with features between the given range.
`grep` searches for sequences/IDs.
`rmdup` removes duplicates by sequence/ID.
`head` selects the first N records.
`sort` sorts records by ID.
`shuffle` put the records in random order.
`flip` reverses the orientation of the locus and features.
