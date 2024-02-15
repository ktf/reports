## Recent AliPhysics releases
## Recent O2 releases
## Recent developments in O2 - Algorithm
	- [\#12634](https://github.com/AliceO2Group/AliceO2/pull/12634) 2024-02-01: Fix double deletion in algorithm::deleteTCollections by [@mconcas](https://github.com/mconcas)
	- [\#12654](https://github.com/AliceO2Group/AliceO2/pull/12654) 2024-02-05: DPL: move stuff out of line by [@ktf](https://github.com/ktf)
	- [\#12707](https://github.com/AliceO2Group/AliceO2/pull/12707) 2024-02-15: DPL: allow extracting data from processing context directly using arguments by [@ktf](https://github.com/ktf)
## Recent developments in O2 - Analysis
	- [\#12652](https://github.com/AliceO2Group/AliceO2/pull/12652) 2024-02-05: Add cluster size in layer by [@njacazio](https://github.com/njacazio)
	- [\#12657](https://github.com/AliceO2Group/AliceO2/pull/12657) 2024-02-06: DPL Analysis: fix internal indices not properly bound when grouping is used by [@aalkin](https://github.com/aalkin)
	- [\#12661](https://github.com/AliceO2Group/AliceO2/pull/12661) 2024-02-07: DPL Analysis: make BindingNodes constexpr by [@aalkin](https://github.com/aalkin)
## Recent developments in O2 - Common
	- [\#12619](https://github.com/AliceO2Group/AliceO2/pull/12619) 2024-01-31: Fixes / improvements / new options for floating-point consistency host / GPU by [@davidrohr](https://github.com/davidrohr)
	- [\#12629](https://github.com/AliceO2Group/AliceO2/pull/12629) 2024-01-31: GPU: Automatically disable math optimizations for TPC track model encoding/decoding code by [@davidrohr](https://github.com/davidrohr)
	- [\#12633](https://github.com/AliceO2Group/AliceO2/pull/12633) 2024-02-02: DPL: make sure we correctly handle DPL created messages by [@ktf](https://github.com/ktf)
	- [\#12676](https://github.com/AliceO2Group/AliceO2/pull/12676) 2024-02-10: DPL: add SendingPolicy for the case destination is expendable by [@ktf](https://github.com/ktf)
	- [\#12682](https://github.com/AliceO2Group/AliceO2/pull/12682) 2024-02-15: ALICE 3: Add ECal detector by [@mconcas](https://github.com/mconcas)
	- [\#12690](https://github.com/AliceO2Group/AliceO2/pull/12690) 2024-02-13: DPL Analysis: make sure additional AOD origins are not skipped by [@aalkin](https://github.com/aalkin)
	- [\#12693](https://github.com/AliceO2Group/AliceO2/pull/12693) 2024-02-13: GPU: Add prototype for SMatrixGPU testing by [@mconcas](https://github.com/mconcas)
## Recent developments in O2 - DataFormats
	- [\#12624](https://github.com/AliceO2Group/AliceO2/pull/12624) 2024-01-31: Suppress more unused vars in the TrackUtils by [@shahor02](https://github.com/shahor02)
	- [\#12635](https://github.com/AliceO2Group/AliceO2/pull/12635) 2024-02-01: Redefine calcMass2(pid1,pid2) to calcMass2PID to use in TTree::Draw by [@shahor02](https://github.com/shahor02)
	- [\#12636](https://github.com/AliceO2Group/AliceO2/pull/12636) 2024-02-05: Added public member function to set MID track efficiency word by [@lucaquaglia15](https://github.com/lucaquaglia15)
	- [\#12644](https://github.com/AliceO2Group/AliceO2/pull/12644) 2024-02-02: ITS MFT Time-evolving dead maps by [@nicolovalle](https://github.com/nicolovalle)
	- [\#12653](https://github.com/AliceO2Group/AliceO2/pull/12653) 2024-02-04: Always load CTP Lumi and use it to scale TPC cov.matrix extra errors by [@shahor02](https://github.com/shahor02)
	- [\#12655](https://github.com/AliceO2Group/AliceO2/pull/12655) 2024-02-07: Adjust e.loss contribution to cov.mat+account for ITS/TPC PID difference at ref.X by [@shahor02](https://github.com/shahor02)
	- [\#12658](https://github.com/AliceO2Group/AliceO2/pull/12658) 2024-02-05: Avoid ambiguity in format_to by [@martenole](https://github.com/martenole)
	- [\#12660](https://github.com/AliceO2Group/AliceO2/pull/12660) 2024-02-08: [EMCAL-688] Inclusion of EMCal Cell and Cluster labels by [@mhemmer-cern](https://github.com/mhemmer-cern)
	- [\#12666](https://github.com/AliceO2Group/AliceO2/pull/12666) 2024-02-09: ctpdev: new exe for FirstOrbit/OrbitReset and shiftOrbit for CTP scalers by [@lietava](https://github.com/lietava)
	- [\#12672](https://github.com/AliceO2Group/AliceO2/pull/12672) 2024-02-08: bug fix when creating diagnostic frequency (clear was missing) by [@noferini](https://github.com/noferini)
	- [\#12682](https://github.com/AliceO2Group/AliceO2/pull/12682) 2024-02-15: ALICE 3: Add ECal detector by [@mconcas](https://github.com/mconcas)
	- [\#12706](https://github.com/AliceO2Group/AliceO2/pull/12706) 2024-02-15: ctpdev: scalers orbit shift by [@lietava](https://github.com/lietava)
## Recent developments in O2 - Detectors
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
	- [\#12666](https://github.com/AliceO2Group/AliceO2/pull/12666) 2024-02-09: ctpdev: new exe for FirstOrbit/OrbitReset and shiftOrbit for CTP scalers by [@lietava](https://github.com/lietava)
	- [\#12671](https://github.com/AliceO2Group/AliceO2/pull/12671) 2024-02-07: TPC: Fixing timestamp in file name when storing scaler to file by [@matthias-kleiner](https://github.com/matthias-kleiner)
	- [\#12672](https://github.com/AliceO2Group/AliceO2/pull/12672) 2024-02-08: bug fix when creating diagnostic frequency (clear was missing) by [@noferini](https://github.com/noferini)
	- [\#12680](https://github.com/AliceO2Group/AliceO2/pull/12680) 2024-02-11: Fixes to make the split wf work again by [@chiarazampolli](https://github.com/chiarazampolli)
	- [\#12681](https://github.com/AliceO2Group/AliceO2/pull/12681) 2024-02-08: Suppress excessive logging in the TrackMethods used by TPC QC by [@shahor02](https://github.com/shahor02)
	- [\#12682](https://github.com/AliceO2Group/AliceO2/pull/12682) 2024-02-15: ALICE 3: Add ECal detector by [@mconcas](https://github.com/mconcas)
	- [\#12684](https://github.com/AliceO2Group/AliceO2/pull/12684) 2024-02-12: [EMCAL-688] Add protection for MCClusterLabel access in case of nullptr by [@jokonig](https://github.com/jokonig)
	- [\#12687](https://github.com/AliceO2Group/AliceO2/pull/12687) 2024-02-12: Enable TF throttling with readers, use in dpl-workflow  by [@shahor02](https://github.com/shahor02)
	- [\#12691](https://github.com/AliceO2Group/AliceO2/pull/12691) 2024-02-13: Make hmp-matcher-workflow respect selected sources by [@benedikt-voelkel](https://github.com/benedikt-voelkel)
	- [\#12694](https://github.com/AliceO2Group/AliceO2/pull/12694) 2024-02-13: Add matches info tree to track-mc-study by [@shahor02](https://github.com/shahor02)
	- [\#12696](https://github.com/AliceO2Group/AliceO2/pull/12696) 2024-02-15: ALICE 3: Beam pipe vacuum vessel, IRIS vacuum vessel update by [@Cas1997](https://github.com/Cas1997)
	- [\#12697](https://github.com/AliceO2Group/AliceO2/pull/12697) 2024-02-13: its-study: add anomaly detection study by [@mconcas](https://github.com/mconcas)
	- [\#12706](https://github.com/AliceO2Group/AliceO2/pull/12706) 2024-02-15: ctpdev: scalers orbit shift by [@lietava](https://github.com/lietava)
	- [\#12707](https://github.com/AliceO2Group/AliceO2/pull/12707) 2024-02-15: DPL: allow extracting data from processing context directly using arguments by [@ktf](https://github.com/ktf)
	- [\#12715](https://github.com/AliceO2Group/AliceO2/pull/12715) 2024-02-15: Fix missing HBFUtilsInitialize plugins in various reader workflows by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Framework
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
	- [\#12674](https://github.com/AliceO2Group/AliceO2/pull/12674) 2024-02-09: DPL Analysis: support both 17 and 20 c++std for type_name() by [@aalkin](https://github.com/aalkin)
	- [\#12676](https://github.com/AliceO2Group/AliceO2/pull/12676) 2024-02-10: DPL: add SendingPolicy for the case destination is expendable by [@ktf](https://github.com/ktf)
	- [\#12685](https://github.com/AliceO2Group/AliceO2/pull/12685) 2024-02-10: DPL: keep code checker happy by [@ktf](https://github.com/ktf)
	- [\#12688](https://github.com/AliceO2Group/AliceO2/pull/12688) 2024-02-12: DPL: hide exception handling from header by [@ktf](https://github.com/ktf)
	- [\#12690](https://github.com/AliceO2Group/AliceO2/pull/12690) 2024-02-13: DPL Analysis: make sure additional AOD origins are not skipped by [@aalkin](https://github.com/aalkin)
	- [\#12695](https://github.com/AliceO2Group/AliceO2/pull/12695) 2024-02-13: DPL: fix lossy sending / forwarding policies by [@ktf](https://github.com/ktf)
	- [\#12699](https://github.com/AliceO2Group/AliceO2/pull/12699) 2024-02-13: DPL: drop reference to the now obsolete non-critical label by [@ktf](https://github.com/ktf)
	- [\#12700](https://github.com/AliceO2Group/AliceO2/pull/12700) 2024-02-14: DPL: Pass the concept of expendable tasks in DPL to templates for ECS by [@knopers8](https://github.com/knopers8)
	- [\#12701](https://github.com/AliceO2Group/AliceO2/pull/12701) 2024-02-14: DPL: make sure homogeneous_apply_ref complains when we are missing an explicit constructor by [@ktf](https://github.com/ktf)
	- [\#12707](https://github.com/AliceO2Group/AliceO2/pull/12707) 2024-02-15: DPL: allow extracting data from processing context directly using arguments by [@ktf](https://github.com/ktf)
## Recent developments in O2 - Steer
	- [\#12641](https://github.com/AliceO2Group/AliceO2/pull/12641) 2024-02-02: Avoid static vars in the ITS/MFT digitizer by [@shahor02](https://github.com/shahor02)
	- [\#12677](https://github.com/AliceO2Group/AliceO2/pull/12677) 2024-02-09: Force digitisation when not in GRP by [@benedikt-voelkel](https://github.com/benedikt-voelkel)
## Recent developments in O2 - Utilities
	- [\#12634](https://github.com/AliceO2Group/AliceO2/pull/12634) 2024-02-01: Fix double deletion in algorithm::deleteTCollections by [@mconcas](https://github.com/mconcas)
	- [\#12676](https://github.com/AliceO2Group/AliceO2/pull/12676) 2024-02-10: DPL: add SendingPolicy for the case destination is expendable by [@ktf](https://github.com/ktf)
