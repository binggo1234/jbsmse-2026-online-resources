# Online Resources 1–5

Supplementary material for the manuscript:

> **Kerf-aware CNC toolpath planning with atomic-span coverage and state-dependent execution**
> Xinpeng Cai, Rongrong Li
> Co-Innovation Center of Efficient Processing and Utilization of Forest Resources,
> Nanjing Forestry University, Nanjing 210037, China
> Corresponding author: Rongrong Li (rongrong.li@njfu.edu.cn)

This repository mirrors the supplementary files submitted with the manuscript to the
*Journal of the Brazilian Society of Mechanical Sciences and Engineering*. It exists so
that reviewers and readers can retrieve the archives unchanged: the journal's submission
system expands uploaded archives into individual files and cannot preserve them in
archive form.

## Contents

| Online Resource | File | Bytes | SHA-256 |
|---|---|---|---|
| 1 | `ESM_1.pdf` | 411,482 | `e32904b6459ccd4d078cba5d0a0a413187ccfb7e6dcd594eb2143af1bd7d7d51` |
| 2 | `ESM_2.zip` | 2,008,627 | `18c1957493386ce1c27cd9e7453e00ead7922d8430300bcaac0eaedc9c60de2e` |
| 3 | `ESM_3.zip` | 1,142,143 | `2c85726399fed0d30d565b07425feff508076cf1944dc75f1ce0f90609356823` |
| 4 | `ESM_4.zip` | 133,538 | `e5225008deb2ffc57fe5d671f8fb5fcbde9186f9a196d365a9a548b6e8bd91e4` |
| 5 | `ESM_5.zip` | 85,790 | `ca406928dcf33b95d183d1aeaf46029e63bb9108e0a09c3cc24a5abe706de85d` |

- **Online Resource 1** — supplementary text. Section S11 names and indexes every
  accompanying file.
- **Online Resource 2** (`Public_Reproduction.zip`) — 30 2DPackLib-derived layouts and
  240 public state-control references.
- **Online Resource 3** (`Industrial_Evidence.zip`) — historical source snapshot, frozen
  protocols and manifests, aggregate factory-task/XML/NC results, public NC examples, and
  VERICUT case-selection files.
- **Online Resource 4** (`Reproducibility_Addendum.zip`) — deidentified source-selection
  ledger, comparator configurations, and a complete partial-common-cut
  selection/replay/NC example.
- **Online Resource 5** (`Detailed_Records.zip`) — the pre-existing publication-safe
  VERICUT run archive, corrected Fusion export checks, and engineering records.

## Verification

```bash
shasum -a 256 -c SHA256SUMS.txt
```

The hashes above are the ones recorded in the submission package; they match the files in
this repository byte for byte.

## What is not included

Raw factory CSV/XML records, original production geometry and identifiers, full
board-level NC databases, production-controller data, and commercial-CAM records remain
restricted by commercial confidentiality. Proprietary CGTech geometry, libraries,
simulator-native projects, VCT Designs, and branded native reports are not redistributed;
controlled inspection depends on licensing permission. Requests for restricted inputs go
to the corresponding author.

## Code

The original project repository is
<https://github.com/binggo1234/chapter3_cnc_cutting>. The archives above, rather than that
repository's current branch, define the executable versions used in the article.
