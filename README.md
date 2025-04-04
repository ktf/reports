## Recent AliPhysics releases
## Recent O2 releases
## Recent developments in O2 - Algorithm
- [\#14103](https://github.com/AliceO2Group/AliceO2/pull/14103) 2025-03-25: GPU: Improvements for sorting / thrust external allocator by [@davidrohr](https://github.com/davidrohr)
- [\#14120](https://github.com/AliceO2Group/AliceO2/pull/14120) 2025-03-28: GPU RTC: Use launch bounds from runtime parameter object for RTC code generation by [@davidrohr](https://github.com/davidrohr)
## Recent developments in O2 - Analysis
- [\#14133](https://github.com/AliceO2Group/AliceO2/pull/14133) 2025-04-01: DPL Analysis: fix combinations generator parsing in analysis task by [@aalkin](https://github.com/aalkin)
- [\#14144](https://github.com/AliceO2Group/AliceO2/pull/14144) 2025-04-04: Fill alternative TPC dedx according to dEdxClusterRejectionFlagMaskAlt, store full reference by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Common
- [\#13972](https://github.com/AliceO2Group/AliceO2/pull/13972) 2025-03-18: Add D*(2007)0 PDG code by [@apalasciano](https://github.com/apalasciano)
- [\#14090](https://github.com/AliceO2Group/AliceO2/pull/14090) 2025-03-19: GPU: Several fixes for sanitizers and build with clang by [@davidrohr](https://github.com/davidrohr)
- [\#14094](https://github.com/AliceO2Group/AliceO2/pull/14094) 2025-03-20: remove deprecated confkey value by [@sawenzel](https://github.com/sawenzel)
- [\#14095](https://github.com/AliceO2Group/AliceO2/pull/14095) 2025-03-23: GPU Standalone: Modernize CMake, get rid of legacy include_directories(...) and add_definitions(...) by [@davidrohr](https://github.com/davidrohr)
- [\#14098](https://github.com/AliceO2Group/AliceO2/pull/14098) 2025-03-22: Common: allow to write c-style arrays in TreeStream by [@f3sch](https://github.com/f3sch)
- [\#14099](https://github.com/AliceO2Group/AliceO2/pull/14099) 2025-03-24: GPU: Replace GPUCA_NO_FAST_MATH by more fine-grain GPUCA_DETERMINISTIC_MODE by [@davidrohr](https://github.com/davidrohr)
- [\#14103](https://github.com/AliceO2Group/AliceO2/pull/14103) 2025-03-25: GPU: Improvements for sorting / thrust external allocator by [@davidrohr](https://github.com/davidrohr)
- [\#14107](https://github.com/AliceO2Group/AliceO2/pull/14107) 2025-03-25: GPU: Change GPUCA_DETERMINISTIC_MODE define to GPUCA_DETERMINISTIC_CODE macro, that can be used also in RTC by [@davidrohr](https://github.com/davidrohr)
- [\#14113](https://github.com/AliceO2Group/AliceO2/pull/14113) 2025-03-27: GPU: Make GPUDefParamters available as C++ struct at runtime by [@davidrohr](https://github.com/davidrohr)
- [\#14120](https://github.com/AliceO2Group/AliceO2/pull/14120) 2025-03-28: GPU RTC: Use launch bounds from runtime parameter object for RTC code generation by [@davidrohr](https://github.com/davidrohr)
- [\#14124](https://github.com/AliceO2Group/AliceO2/pull/14124) 2025-04-02: GPU: Cleanup stale ITS GPU code by [@mconcas](https://github.com/mconcas)
- [\#14125](https://github.com/AliceO2Group/AliceO2/pull/14125) 2025-03-29: GPU RTC: Ability to create and load an RTC launch bound parameter object file, and use that for RTC compilation at runtime. by [@davidrohr](https://github.com/davidrohr)
- [\#14138](https://github.com/AliceO2Group/AliceO2/pull/14138) 2025-04-03: DPL: avoid expensive find_if for check of AVAILABLE_MANAGED_SHM metric when sending metrics by [@ehellbar](https://github.com/ehellbar)
- [\#14139](https://github.com/AliceO2Group/AliceO2/pull/14139) 2025-04-04: GPU: Array add fill method by [@f3sch](https://github.com/f3sch)
- [\#14142](https://github.com/AliceO2Group/AliceO2/pull/14142) 2025-04-03: Common: DCAFitter fix collinear not touching calc by [@f3sch](https://github.com/f3sch)
## Recent developments in O2 - DataFormats
- [\#13979](https://github.com/AliceO2Group/AliceO2/pull/13979) 2025-03-18: FIT: add RecPoint reader and writer workflows for FV0 and FDD by [@andreasmolander](https://github.com/andreasmolander)
- [\#14065](https://github.com/AliceO2Group/AliceO2/pull/14065) 2025-03-18: Fix round-robin reading in DigitizationContext::retrieveHits by [@shahor02](https://github.com/shahor02)
- [\#14066](https://github.com/AliceO2Group/AliceO2/pull/14066) 2025-03-19: Avoid fatal in CTPRateFetcher by [@Barthelemy](https://github.com/Barthelemy)
- [\#14068](https://github.com/AliceO2Group/AliceO2/pull/14068) 2025-03-18: DataFormatsFIT: hotfix for LUT, excluded CCDB API from header by [@afurs](https://github.com/afurs)
- [\#14089](https://github.com/AliceO2Group/AliceO2/pull/14089) 2025-03-18: Fix BC filling in per TF digi contexts by [@sawenzel](https://github.com/sawenzel)
- [\#14123](https://github.com/AliceO2Group/AliceO2/pull/14123) 2025-04-02: [AFIT-112]: FT0's reco update, 3 new event bits by [@afurs](https://github.com/afurs)
- [\#14130](https://github.com/AliceO2Group/AliceO2/pull/14130) 2025-04-04: ITSMFT: add asString() for clusters by [@f3sch](https://github.com/f3sch)
- [\#14144](https://github.com/AliceO2Group/AliceO2/pull/14144) 2025-04-04: Fill alternative TPC dedx according to dEdxClusterRejectionFlagMaskAlt, store full reference by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Detectors
- [\#13959](https://github.com/AliceO2Group/AliceO2/pull/13959) 2025-03-18: ALICE 3: Add empty skeleton for the TRK digitization by [@mconcas](https://github.com/mconcas)
- [\#13979](https://github.com/AliceO2Group/AliceO2/pull/13979) 2025-03-18: FIT: add RecPoint reader and writer workflows for FV0 and FDD by [@andreasmolander](https://github.com/andreasmolander)
- [\#13995](https://github.com/AliceO2Group/AliceO2/pull/13995) 2025-03-27: ITS Efficiency study: modified cuts and code cleanup by [@atriolo](https://github.com/atriolo)
- [\#14066](https://github.com/AliceO2Group/AliceO2/pull/14066) 2025-03-19: Avoid fatal in CTPRateFetcher by [@Barthelemy](https://github.com/Barthelemy)
- [\#14068](https://github.com/AliceO2Group/AliceO2/pull/14068) 2025-03-18: DataFormatsFIT: hotfix for LUT, excluded CCDB API from header by [@afurs](https://github.com/afurs)
- [\#14076](https://github.com/AliceO2Group/AliceO2/pull/14076) 2025-03-18: ITSResponse: remove incompatible arg in CMake by [@mconcas](https://github.com/mconcas)
- [\#14080](https://github.com/AliceO2Group/AliceO2/pull/14080) 2025-03-19: [MCH] turn error into warning and continue the scan by [@pillot](https://github.com/pillot)
- [\#14086](https://github.com/AliceO2Group/AliceO2/pull/14086) 2025-03-19: Fixing CCDB host address for MFT noise scan by [@mcoquet642](https://github.com/mcoquet642)
- [\#14087](https://github.com/AliceO2Group/AliceO2/pull/14087) 2025-03-19: fix: debug removed by [@lietava](https://github.com/lietava)
- [\#14092](https://github.com/AliceO2Group/AliceO2/pull/14092) 2025-03-20: TPC: Adding check for empty IDCs by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [\#14093](https://github.com/AliceO2Group/AliceO2/pull/14093) 2025-03-28: FIT: Geometry alignment macros by [@andreasmolander](https://github.com/andreasmolander)
- [\#14097](https://github.com/AliceO2Group/AliceO2/pull/14097) 2025-04-04: AOD: save selected TPC standalone tracks from thinning by [@f3sch](https://github.com/f3sch)
- [\#14099](https://github.com/AliceO2Group/AliceO2/pull/14099) 2025-03-24: GPU: Replace GPUCA_NO_FAST_MATH by more fine-grain GPUCA_DETERMINISTIC_MODE by [@davidrohr](https://github.com/davidrohr)
- [\#14102](https://github.com/AliceO2Group/AliceO2/pull/14102) 2025-03-24: Make ITS reco start layer configurable by [@shahor02](https://github.com/shahor02)
- [\#14104](https://github.com/AliceO2Group/AliceO2/pull/14104) 2025-03-24: ALICE3: Fix TRKConfigParam dictionary creation by [@mconcas](https://github.com/mconcas)
- [\#14105](https://github.com/AliceO2Group/AliceO2/pull/14105) 2025-03-24: Fix method MCTrackInfo::getNITSClusCont by [@shahor02](https://github.com/shahor02)
- [\#14107](https://github.com/AliceO2Group/AliceO2/pull/14107) 2025-03-25: GPU: Change GPUCA_DETERMINISTIC_MODE define to GPUCA_DETERMINISTIC_CODE macro, that can be used also in RTC by [@davidrohr](https://github.com/davidrohr)
- [\#14114](https://github.com/AliceO2Group/AliceO2/pull/14114) 2025-04-01: TPC: Extend DCS update and fit interval by [@wiechula](https://github.com/wiechula)
- [\#14115](https://github.com/AliceO2Group/AliceO2/pull/14115) 2025-04-01: TPC: Extend time gain calibration by [@wiechula](https://github.com/wiechula)
- [\#14123](https://github.com/AliceO2Group/AliceO2/pull/14123) 2025-04-02: [AFIT-112]: FT0's reco update, 3 new event bits by [@afurs](https://github.com/afurs)
- [\#14124](https://github.com/AliceO2Group/AliceO2/pull/14124) 2025-04-02: GPU: Cleanup stale ITS GPU code by [@mconcas](https://github.com/mconcas)
- [\#14130](https://github.com/AliceO2Group/AliceO2/pull/14130) 2025-04-04: ITSMFT: add asString() for clusters by [@f3sch](https://github.com/f3sch)
- [\#14134](https://github.com/AliceO2Group/AliceO2/pull/14134) 2025-04-04: [Strangeness Tracker] Use meaningful matching chi2 calculation by [@fmazzasc](https://github.com/fmazzasc)
- [\#14144](https://github.com/AliceO2Group/AliceO2/pull/14144) 2025-04-04: Fill alternative TPC dedx according to dEdxClusterRejectionFlagMaskAlt, store full reference by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Examples
- [\#14121](https://github.com/AliceO2Group/AliceO2/pull/14121) 2025-03-28: Generator example for quick HepMC extraction from Pythia8 by [@sawenzel](https://github.com/sawenzel)
## Recent developments in O2 - Framework
- [\#14041](https://github.com/AliceO2Group/AliceO2/pull/14041) 2025-03-27: DPL: make input slots display in DebugGUI scrollable by [@aalkin](https://github.com/aalkin)
- [\#14081](https://github.com/AliceO2Group/AliceO2/pull/14081) 2025-03-18: explicitly add CCDB to some CCDB fatal error strings by [@ehellbar](https://github.com/ehellbar)
- [\#14088](https://github.com/AliceO2Group/AliceO2/pull/14088) 2025-03-20: DPL: enable early forwarding for AODs by [@ktf](https://github.com/ktf)
- [\#14096](https://github.com/AliceO2Group/AliceO2/pull/14096) 2025-03-22: DPL: cleanup creation of DataProcessorInfo by [@ktf](https://github.com/ktf)
- [\#14100](https://github.com/AliceO2Group/AliceO2/pull/14100) 2025-03-24: DPL: Print error in case we receive data with bogus runNumber / tfCounter by [@davidrohr](https://github.com/davidrohr)
- [\#14118](https://github.com/AliceO2Group/AliceO2/pull/14118) 2025-03-27: DPL: allow searching for plugins in executables as well by [@ktf](https://github.com/ktf)
- [\#14133](https://github.com/AliceO2Group/AliceO2/pull/14133) 2025-04-01: DPL Analysis: fix combinations generator parsing in analysis task by [@aalkin](https://github.com/aalkin)
- [\#14135](https://github.com/AliceO2Group/AliceO2/pull/14135) 2025-04-03: DPL: attempt at adding the run number to timers and enumerations by [@ktf](https://github.com/ktf)
- [\#14136](https://github.com/AliceO2Group/AliceO2/pull/14136) 2025-04-03: DPL: Improve debug message for missing runNumber. by [@ktf](https://github.com/ktf)
- [\#14138](https://github.com/AliceO2Group/AliceO2/pull/14138) 2025-04-03: DPL: avoid expensive find_if for check of AVAILABLE_MANAGED_SHM metric when sending metrics by [@ehellbar](https://github.com/ehellbar)
- [\#14144](https://github.com/AliceO2Group/AliceO2/pull/14144) 2025-04-04: Fill alternative TPC dedx according to dEdxClusterRejectionFlagMaskAlt, store full reference by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Generators
- [\#14108](https://github.com/AliceO2Group/AliceO2/pull/14108) 2025-03-25: GeneratorHybrid: improve unit treatment by [@sawenzel](https://github.com/sawenzel)
## Recent developments in O2 - Steer
- [\#13959](https://github.com/AliceO2Group/AliceO2/pull/13959) 2025-03-18: ALICE 3: Add empty skeleton for the TRK digitization by [@mconcas](https://github.com/mconcas)
