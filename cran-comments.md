# Release Summary

Submission of `epocakir`, version bumped to v0.9.8. In this version:

- Updated README and description
- Addressed comments from `goodpractice::gp()`

## R CMD check results

```console
-- R CMD check results ----------------------------------- epocakir 0.9.8 ----
Duration: 1m 31.9s

0 errors √ | 0 warnings √ | 0 notes √
```

## Test Environments

- Local Windows 10 install: R 4.0.3

- macOS Big Sur  (GitHub Actions): R 4.2.0
- Windows Server (GitHub Actions): R 4.2.0, R 3.6.3 with Rtools35,
- Ubuntu 18.04.6 (GitHub Actions): R-devel, 4.2.0, R 4.1.3, 4.0.5, 3.6.3, 3.5.3

- win-builder: R-devel, R-release, R-oldrelease
- R-hub: Windows R-devel, Ubuntu R-release, Fedora R-devel

- Checks:
  - `goodpractice::gp()`,
  - `rcmdcheck::rcmdcheck(args = c("--no-manual", "--as-cran"), error_on = "warning", check_dir = "check")`,
  - `devtools::spell_check()`,
  - `devtools::check_rhub()`,
  - `devtools::check_win_devel()`,
  - `codemetar::write_codemeta()`

## Revdep Checks

No published downstream dependencies
