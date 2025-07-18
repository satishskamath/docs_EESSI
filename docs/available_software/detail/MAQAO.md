---
hide:
- toc
json_ld:
  '@context': https://schema.org
  '@type': SoftwareApplication
  applicationCategory: DeveloperApplication
  description: MAQAO (Modular Assembly Quality Analyzer and Optimizer) is a performanceanalysis
    and optimization framework operating at binary level with a focus on coreperformance.
    Its main goal of is to guide application developers along the optimizationprocess
    through synthetic reports and hints.MAQAO mixes both dynamic and static analyses
    based on its ability to reconstruct highlevel structures such as functions and
    loops from an application binary. Since MAQAOoperates at binary level, it is agnostic
    with regard to the language used in the sourcecode and does not require recompiling
    the application to perform analyses.
  license: Not confirmed
  name: MAQAO
  offers:
    '@type': Offer
    price: 0
  operatingSystem: LINUX
  review:
    '@type': Review
    author:
      '@type': Organization
      name: EESSI
    reviewBody: Application has been successfully made available on all architectures
      supported by EESSI
    reviewRating:
      '@type': Rating
      ratingValue: 5
  softwareRequirements: See https://www.eessi.io/docs/ for how to make EESSI available
    on your system
  softwareVersion: '[''MAQAO/2.21.1'']'
  url: https://maqao.org
---

MAQAO
=====


MAQAO (Modular Assembly Quality Analyzer and Optimizer) is a performanceanalysis and optimization framework operating at binary level with a focus on coreperformance. Its main goal of is to guide application developers along the optimizationprocess through synthetic reports and hints.MAQAO mixes both dynamic and static analyses based on its ability to reconstruct highlevel structures such as functions and loops from an application binary. Since MAQAOoperates at binary level, it is agnostic with regard to the language used in the sourcecode and does not require recompiling the application to perform analyses.

https://maqao.org
# Available modules


The overview below shows which MAQAO installations are available per target architecture in EESSI, ordered based on software version (new to old).

To start using MAQAO, load one of these modules using a `module load` command like:

```shell
module load MAQAO/2.21.1
```

*(This data was automatically generated on {{ generated_time }})*

| |aarch64/generic|aarch64/neoverse_n1|aarch64/neoverse_v1|aarch64/nvidia/grace|x86_64/generic|x86_64/amd/zen2|x86_64/amd/zen3|x86_64/amd/zen4|x86_64/intel/cascadelake|x86_64/intel/haswell|x86_64/intel/icelake|x86_64/intel/sapphirerapids|x86_64/intel/skylake_avx512|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|MAQAO/2.21.1|x|x|x|x|x|x|x|x|x|x|x|x|x|
