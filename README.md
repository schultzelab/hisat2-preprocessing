# HISAT2 alignment pipeline

![Flow diagram](./docs/rulegraph.svg )

## Usage

See ![`docker-compose.yml`](./docker-compose.yml) for details.

### Branch TruSeq

Adapted pipeline to be run on Truseq libraries.

#### V0.0.1:
Added RNA-strandness option for Hisat2 alignment in configfile

#### v0.0.2:
Changed htseq-count opption to --stranded reverse (hardcoded).
