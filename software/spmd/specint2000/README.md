SPECInt2000 Benchamarks on Manycore
===================================

- Initial setup:
	`make checkout`
- Benchmarks imported from RAW's greenlight repo
- `rawlib/`: Since `greenlight` was originally written for raw, it uses 
  some raw library functions to run spec benchamrks. This folder
  contains manycore versions of required raw library functions.
- `Makefile.BenChMaRK`: Makefile to run `BenChMaRK`
- `Makefile`: Makefile to run all specint benchmarks
