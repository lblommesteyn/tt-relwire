# RelWire protocol emulator (Tiny Tapeout, IHP CMOS5L)

Tiny Tapeout submission for the Jane Street protocol-emulator ASIC competition.
Four cores run one relational protocol program; a role mask per core makes the
same binary a controller, a target or a sniffer.

This repository is generated from the main project,
[lblommesteyn/relwire](https://github.com/lblommesteyn/relwire), by
`tapeout/export_tt_repo.sh`, at commit
[`935aee98541b`](https://github.com/lblommesteyn/relwire/tree/935aee98541b23b53cc3e6140998188297d5d7f9) (also in
`SOURCE_REV`): the language, reference model, compiler, timing
certificates and the full test suites live there. See [docs/info.md](docs/info.md)
for how the chip works and how to test it.
