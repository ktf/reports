## Recent AliPhysics releases
## Recent O2 releases
## Recent developments in O2 - Algorithm
	- [\#12634](https://github.com/AliceO2Group/AliceO2/pull/12634) 2024-02-01: Fix double deletion in algorithm::deleteTCollections by [@mconcas](https://github.com/mconcas)
	- [\#12654](https://github.com/AliceO2Group/AliceO2/pull/12654) 2024-02-05: DPL: move stuff out of line by [@ktf](https://github.com/ktf)
## Recent developments in O2 - Analysis
	- [\#12652](https://github.com/AliceO2Group/AliceO2/pull/12652) 2024-02-05: Add cluster size in layer by [@njacazio](https://github.com/njacazio)
	- [\#12657](https://github.com/AliceO2Group/AliceO2/pull/12657) 2024-02-06: DPL Analysis: fix internal indices not properly bound when grouping is used by [@aalkin](https://github.com/aalkin)
	- [\#12661](https://github.com/AliceO2Group/AliceO2/pull/12661) 2024-02-07: DPL Analysis: make BindingNodes constexpr by [@aalkin](https://github.com/aalkin)
## Recent developments in O2 - Common
	- [\#12590](https://github.com/AliceO2Group/AliceO2/pull/12590) 2024-01-25: DPL: use Signposts to debug oldest possible timeframe. by [@ktf](https://github.com/ktf)
	- [\#12617](https://github.com/AliceO2Group/AliceO2/pull/12617) 2024-01-30: Make sure the user routes are traced also on EoS by [@ktf](https://github.com/ktf)
	- [\#12619](https://github.com/AliceO2Group/AliceO2/pull/12619) 2024-01-31: Fixes / improvements / new options for floating-point consistency host / GPU by [@davidrohr](https://github.com/davidrohr)
	- [\#12629](https://github.com/AliceO2Group/AliceO2/pull/12629) 2024-01-31: GPU: Automatically disable math optimizations for TPC track model encoding/decoding code by [@davidrohr](https://github.com/davidrohr)
	- [\#12633](https://github.com/AliceO2Group/AliceO2/pull/12633) 2024-02-02: DPL: make sure we correctly handle DPL created messages by [@ktf](https://github.com/ktf)
## Recent developments in O2 - DataFormats
	- [\#12581](https://github.com/AliceO2Group/AliceO2/pull/12581) 2024-01-25: Infologger Cleanup by [@martenole](https://github.com/martenole)
	- [\#12592](https://github.com/AliceO2Group/AliceO2/pull/12592) 2024-01-25: o2-sim: Change way to create standalone MCHeader file by [@sawenzel](https://github.com/sawenzel)
	- [\#12607](https://github.com/AliceO2Group/AliceO2/pull/12607) 2024-01-28: Use iterative e.loss correction if kin.E loss fraction exceeds 2.5% by [@shahor02](https://github.com/shahor02)
	- [\#12611](https://github.com/AliceO2Group/AliceO2/pull/12611) 2024-01-29: Workflow for relating and dumping MC and reco tracks info by [@shahor02](https://github.com/shahor02)
	- [\#12612](https://github.com/AliceO2Group/AliceO2/pull/12612) 2024-01-29: Hide unused variables by [@shahor02](https://github.com/shahor02)
	- [\#12624](https://github.com/AliceO2Group/AliceO2/pull/12624) 2024-01-31: Suppress more unused vars in the TrackUtils by [@shahor02](https://github.com/shahor02)
	- [\#12635](https://github.com/AliceO2Group/AliceO2/pull/12635) 2024-02-01: Redefine calcMass2(pid1,pid2) to calcMass2PID to use in TTree::Draw by [@shahor02](https://github.com/shahor02)
	- [\#12636](https://github.com/AliceO2Group/AliceO2/pull/12636) 2024-02-05: Added public member function to set MID track efficiency word by [@lucaquaglia15](https://github.com/lucaquaglia15)
	- [\#12644](https://github.com/AliceO2Group/AliceO2/pull/12644) 2024-02-02: ITS MFT Time-evolving dead maps by [@nicolovalle](https://github.com/nicolovalle)
	- [\#12653](https://github.com/AliceO2Group/AliceO2/pull/12653) 2024-02-04: Always load CTP Lumi and use it to scale TPC cov.matrix extra errors by [@shahor02](https://github.com/shahor02)
	- [\#12655](https://github.com/AliceO2Group/AliceO2/pull/12655) 2024-02-07: Adjust e.loss contribution to cov.mat+account for ITS/TPC PID difference at ref.X by [@shahor02](https://github.com/shahor02)
	- [\#12658](https://github.com/AliceO2Group/AliceO2/pull/12658) 2024-02-05: Avoid ambiguity in format_to by [@martenole](https://github.com/martenole)
	- [\#12660](https://github.com/AliceO2Group/AliceO2/pull/12660) 2024-02-08: [EMCAL-688] Inclusion of EMCal Cell and Cluster labels by [@mhemmer-cern](https://github.com/mhemmer-cern)
	- [\#12672](https://github.com/AliceO2Group/AliceO2/pull/12672) 2024-02-08: bug fix when creating diagnostic frequency (clear was missing) by [@noferini](https://github.com/noferini)
## Recent developments in O2 - Detectors
	- [\#12581](https://github.com/AliceO2Group/AliceO2/pull/12581) 2024-01-25: Infologger Cleanup by [@martenole](https://github.com/martenole)
	- [\#12584](https://github.com/AliceO2Group/AliceO2/pull/12584) 2024-01-24: Avoid extra run call in the end of raw-reader cycle by [@shahor02](https://github.com/shahor02)
	- [\#12586](https://github.com/AliceO2Group/AliceO2/pull/12586) 2024-01-24: FT0 reco: rounding for mean times by [@afurs](https://github.com/afurs)
	- [\#12598](https://github.com/AliceO2Group/AliceO2/pull/12598) 2024-01-26: GLOQC: Fix QC-1091 by [@f3sch](https://github.com/f3sch)
	- [\#12601](https://github.com/AliceO2Group/AliceO2/pull/12601) 2024-01-26: Move some macros in `COMPILE_ONLY` mode in tests to workaround ROOT issues with C++20 by [@mconcas](https://github.com/mconcas)
	- [\#12603](https://github.com/AliceO2Group/AliceO2/pull/12603) 2024-01-28: Add possibility to upload and query the MID fake dead list in ccdb by [@dstocco](https://github.com/dstocco)
	- [\#12604](https://github.com/AliceO2Group/AliceO2/pull/12604) 2024-01-29: Allow to detect bad channels from MID occupancy when no calibration trigger is found by [@dstocco](https://github.com/dstocco)
	- [\#12606](https://github.com/AliceO2Group/AliceO2/pull/12606) 2024-01-26: Move another macro to be compiled only by [@ktf](https://github.com/ktf)
	- [\#12611](https://github.com/AliceO2Group/AliceO2/pull/12611) 2024-01-29: Workflow for relating and dumping MC and reco tracks info by [@shahor02](https://github.com/shahor02)
	- [\#12614](https://github.com/AliceO2Group/AliceO2/pull/12614) 2024-01-29: Switch on reading of BadChannel CCDB information in StatusMap Creator with protection added by [@lmassacr](https://github.com/lmassacr)
	- [\#12615](https://github.com/AliceO2Group/AliceO2/pull/12615) 2024-01-30: TPC timeseries: Adding new variables for skimmed data by [@matthias-kleiner](https://github.com/matthias-kleiner)
	- [\#12620](https://github.com/AliceO2Group/AliceO2/pull/12620) 2024-02-05: Ignore the 'Error decoding the superpage' in QC-Task by [@fapfap69](https://github.com/fapfap69)
	- [\#12626](https://github.com/AliceO2Group/AliceO2/pull/12626) 2024-01-31: TPC: Add getter for output tree by [@wiechula](https://github.com/wiechula)
	- [\#12628](https://github.com/AliceO2Group/AliceO2/pull/12628) 2024-01-31: TPC: Fix when no M-Shape correction map is set by [@matthias-kleiner](https://github.com/matthias-kleiner)
	- [\#12630](https://github.com/AliceO2Group/AliceO2/pull/12630) 2024-02-02: TPCQC added PID hypothesis to PID Task by [@HorstMa](https://github.com/HorstMa)
	- [\#12631](https://github.com/AliceO2Group/AliceO2/pull/12631) 2024-01-31: TPC M-Shape correction: Suppress error message if default object is used by [@matthias-kleiner](https://github.com/matthias-kleiner)
	- [\#12636](https://github.com/AliceO2Group/AliceO2/pull/12636) 2024-02-05: Added public member function to set MID track efficiency word by [@lucaquaglia15](https://github.com/lucaquaglia15)
	- [\#12637](https://github.com/AliceO2Group/AliceO2/pull/12637) 2024-02-02: TPC: Adding PID from tracking to skimmed data by [@matthias-kleiner](https://github.com/matthias-kleiner)
	- [\#12642](https://github.com/AliceO2Group/AliceO2/pull/12642) 2024-02-02: fix DaughterTrackId in AODMcProducerHelpers by [@DanielSamitz](https://github.com/DanielSamitz)
	- [\#12644](https://github.com/AliceO2Group/AliceO2/pull/12644) 2024-02-02: ITS MFT Time-evolving dead maps by [@nicolovalle](https://github.com/nicolovalle)
	- [\#12645](https://github.com/AliceO2Group/AliceO2/pull/12645) 2024-02-02: Add lowest TPC track pad-row to failed matches output by [@shahor02](https://github.com/shahor02)
	- [\#12649](https://github.com/AliceO2Group/AliceO2/pull/12649) 2024-02-02: Suppress breaks breaking CorrectionMapsLoader init by [@shahor02](https://github.com/shahor02)
	- [\#12651](https://github.com/AliceO2Group/AliceO2/pull/12651) 2024-02-03: Always extract lowest padrow when matching check is asked by [@shahor02](https://github.com/shahor02)
	- [\#12653](https://github.com/AliceO2Group/AliceO2/pull/12653) 2024-02-04: Always load CTP Lumi and use it to scale TPC cov.matrix extra errors by [@shahor02](https://github.com/shahor02)
	- [\#12655](https://github.com/AliceO2Group/AliceO2/pull/12655) 2024-02-07: Adjust e.loss contribution to cov.mat+account for ITS/TPC PID difference at ref.X by [@shahor02](https://github.com/shahor02)
	- [\#12659](https://github.com/AliceO2Group/AliceO2/pull/12659) 2024-02-06: TPC: Improve allowed number of bins and custom binning options by [@wiechula](https://github.com/wiechula)
	- [\#12660](https://github.com/AliceO2Group/AliceO2/pull/12660) 2024-02-08: [EMCAL-688] Inclusion of EMCal Cell and Cluster labels by [@mhemmer-cern](https://github.com/mhemmer-cern)
	- [\#12663](https://github.com/AliceO2Group/AliceO2/pull/12663) 2024-02-07: option to store dia TOF calib directly from digits by [@noferini](https://github.com/noferini)
	- [\#12664](https://github.com/AliceO2Group/AliceO2/pull/12664) 2024-02-06: AODProducer: fix logical inversion for prop-tracks by [@f3sch](https://github.com/f3sch)
	- [\#12671](https://github.com/AliceO2Group/AliceO2/pull/12671) 2024-02-07: TPC: Fixing timestamp in file name when storing scaler to file by [@matthias-kleiner](https://github.com/matthias-kleiner)
	- [\#12672](https://github.com/AliceO2Group/AliceO2/pull/12672) 2024-02-08: bug fix when creating diagnostic frequency (clear was missing) by [@noferini](https://github.com/noferini)
## Recent developments in O2 - Framework
	- [\#12585](https://github.com/AliceO2Group/AliceO2/pull/12585) 2024-01-24: DPL: improve "Discard"  action by [@ktf](https://github.com/ktf)
	- [\#12589](https://github.com/AliceO2Group/AliceO2/pull/12589) 2024-01-25: DPL: command line option to enable signposts by [@ktf](https://github.com/ktf)
	- [\#12590](https://github.com/AliceO2Group/AliceO2/pull/12590) 2024-01-25: DPL: use Signposts to debug oldest possible timeframe. by [@ktf](https://github.com/ktf)
	- [\#12593](https://github.com/AliceO2Group/AliceO2/pull/12593) 2024-01-26: Debug DataAllocator::matchDataHeader crash by [@martenole](https://github.com/martenole)
	- [\#12594](https://github.com/AliceO2Group/AliceO2/pull/12594) 2024-01-25: DPL: make stacktrace level not atomic by [@ktf](https://github.com/ktf)
	- [\#12595](https://github.com/AliceO2Group/AliceO2/pull/12595) 2024-01-25: DPL: allow signposts to be enabled via DPL_SIGNPOSTS by [@ktf](https://github.com/ktf)
	- [\#12596](https://github.com/AliceO2Group/AliceO2/pull/12596) 2024-01-25: DPL: add o2-log utility (for Mac, Linux coming) by [@ktf](https://github.com/ktf)
	- [\#12597](https://github.com/AliceO2Group/AliceO2/pull/12597) 2024-02-01: DPL: support for Signposts in CCDB by [@ktf](https://github.com/ktf)
	- [\#12599](https://github.com/AliceO2Group/AliceO2/pull/12599) 2024-01-26: DPL: install o2-log in the proper place by [@ktf](https://github.com/ktf)
	- [\#12600](https://github.com/AliceO2Group/AliceO2/pull/12600) 2024-01-28: DPL: do not update the new run flag unless we do process data by [@ktf](https://github.com/ktf)
	- [\#12610](https://github.com/AliceO2Group/AliceO2/pull/12610) 2024-02-01: Data inspector by [@a-wolk](https://github.com/a-wolk)
	- [\#12617](https://github.com/AliceO2Group/AliceO2/pull/12617) 2024-01-30: Make sure the user routes are traced also on EoS by [@ktf](https://github.com/ktf)
	- [\#12621](https://github.com/AliceO2Group/AliceO2/pull/12621) 2024-01-31: DPL: avoid invoking matchDataHeader twice when sending data by [@ktf](https://github.com/ktf)
	- [\#12622](https://github.com/AliceO2Group/AliceO2/pull/12622) 2024-02-01: DPL: Update the lastRunNumberProcessed only if we actually processed something by [@davidrohr](https://github.com/davidrohr)
	- [\#12632](https://github.com/AliceO2Group/AliceO2/pull/12632) 2024-02-01: DPL: avoid invoking matchDataHeader twice by [@ktf](https://github.com/ktf)
	- [\#12633](https://github.com/AliceO2Group/AliceO2/pull/12633) 2024-02-02: DPL: make sure we correctly handle DPL created messages by [@ktf](https://github.com/ktf)
	- [\#12638](https://github.com/AliceO2Group/AliceO2/pull/12638) 2024-02-01: DPL: print out how to enable disabled signposts by [@ktf](https://github.com/ktf)
	- [\#12639](https://github.com/AliceO2Group/AliceO2/pull/12639) 2024-02-01: DPL: properly install o2-log by [@ktf](https://github.com/ktf)
	- [\#12647](https://github.com/AliceO2Group/AliceO2/pull/12647) 2024-02-02: DPL: fix circular dependency between expendable / resilient tasks and output proxy by [@ktf](https://github.com/ktf)
	- [\#12652](https://github.com/AliceO2Group/AliceO2/pull/12652) 2024-02-05: Add cluster size in layer by [@njacazio](https://github.com/njacazio)
	- [\#12654](https://github.com/AliceO2Group/AliceO2/pull/12654) 2024-02-05: DPL: move stuff out of line by [@ktf](https://github.com/ktf)
	- [\#12656](https://github.com/AliceO2Group/AliceO2/pull/12656) 2024-02-06: DPL: reduce helpers for makeHolder / makeHolderTypes by [@ktf](https://github.com/ktf)
	- [\#12657](https://github.com/AliceO2Group/AliceO2/pull/12657) 2024-02-06: DPL Analysis: fix internal indices not properly bound when grouping is used by [@aalkin](https://github.com/aalkin)
	- [\#12661](https://github.com/AliceO2Group/AliceO2/pull/12661) 2024-02-07: DPL Analysis: make BindingNodes constexpr by [@aalkin](https://github.com/aalkin)
	- [\#12668](https://github.com/AliceO2Group/AliceO2/pull/12668) 2024-02-07: DPL Analysis: avoid extra cursorHelper methods by [@ktf](https://github.com/ktf)
## Recent developments in O2 - Generators
	- [\#12587](https://github.com/AliceO2Group/AliceO2/pull/12587) 2024-01-24: Pythia8: improved determination of callback filename by [@sawenzel](https://github.com/sawenzel)
## Recent developments in O2 - Steer
	- [\#12641](https://github.com/AliceO2Group/AliceO2/pull/12641) 2024-02-02: Avoid static vars in the ITS/MFT digitizer by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Utilities
	- [\#12588](https://github.com/AliceO2Group/AliceO2/pull/12588) 2024-01-24: [QC-1089] Reset Merger state before each SOR by [@knopers8](https://github.com/knopers8)
	- [\#12634](https://github.com/AliceO2Group/AliceO2/pull/12634) 2024-02-01: Fix double deletion in algorithm::deleteTCollections by [@mconcas](https://github.com/mconcas)
