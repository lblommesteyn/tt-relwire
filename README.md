# RelWire protocol emulator (Tiny Tapeout, IHP CMOS5L)

Tiny Tapeout submission for the Jane Street protocol-emulator ASIC competition.
Four cores run one relational protocol program; a role mask per core makes the
same binary a controller, a target or a sniffer.

This repository is generated from the main project,
[lblommesteyn/relwire](https://github.com/lblommesteyn/relwire), by
`tapeout/export_tt_repo.sh`: the language, reference model, compiler, timing
certificates and the full test suites live there. See [docs/info.md](docs/info.md)
for how the chip works and how to test it.
