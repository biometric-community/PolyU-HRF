# PolyU HRF

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FPolyU--HRF-181717?logo=github)](https://github.com/biometric-community/PolyU-HRF)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www4.comp.polyu.edu.hk/~biometrics/)

**PolyU HRF** — tbiom catalog packaging for `polyu-hrf` (fingerprint; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/PolyU-HRF
- **Upstream source**: https://www4.comp.polyu.edu.hk/~biometrics/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `polyu-hrf` |
| Category | `fingerprint` |
| Access | `register` |
| Upstream homepage | https://www4.comp.polyu.edu.hk/~biometrics/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: PolyU high-resolution fingerprint (pores).

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/PolyU-HRF.git
cd PolyU-HRF
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_polyu_hrf.sh
```

Place licensed archives under `projects/datasets/polyu-hrf/` (gitignored).

## Dataset structure

```text
PolyU-HRF/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www4.comp.polyu.edu.hk/~biometrics/
- Packaging: https://github.com/biometric-community/PolyU-HRF/issues
