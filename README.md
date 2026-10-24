# RST: Random-Access Hardware Sequence Compression

This repository contains the source code and RTL for **RST**, a hardware memory compression algorithm that enables random access to individual 64B compressed blocks using a 128B-per-page decompression dictionary.

## Publication

Nolan Chu, Yoon Lee, Gagandeep Panwar, Xun Jian. "Random-Access Hardware Sequence Compression."
In *Proceedings of the 53rd Annual IEEE/ACM International Symposium on Computer Architecture,
June 2026.* https://doi.org/10.1109/ISCA66397.2026.00107

```
@INPROCEEDINGS{isca2026_rst,
  author={Chu, Nolan and Lee, Yoon and Panwar, Gagandeep and Jian, Xun},
  booktitle={2026 ACM/IEEE 53rd Annual International Symposium on Computer Architecture (ISCA)}, 
  title={Random-Access Hardware Sequence Compression}, 
  year={2026},
  volume={},
  number={},
  pages={1432-1447},
  keywords={Dictionaries;Memory;Sequences;Sequential analysis;Symbols;Hardware;Design methodology;Modules (abstract algebra);Indexes;Indexing;Memory subsystem;hardware memory compression;compression algorithms;compression accelerators},
  doi={10.1109/ISCA66397.2026.00107}}

```

## Artifact

The complete artifact (source, RTL, memory dumps, QEMU VM image, and synthesis evidence) is available on Zenodo:

**[https://doi.org/10.5281/zenodo.19449274](https://doi.org/10.5281/zenodo.19449274)**

See the Zenodo archive's `README.md` for setup and experiment instructions.

```
@software{chu_2026_19501484,
  author       = {Chu, Nolan and
                  Lee, Yoon and
                  Panwar, Gagandeep and
                  Jian, Xun},
  title        = {RST: Random-Access Hardware Sequence Compression —
                   Artifact
                  },
  month        = apr,
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.19501484},
  url          = {https://doi.org/10.5281/zenodo.19501484},
}
```

## License

BSD 3-Clause Clear. See [LICENSE](LICENSE) for details.
