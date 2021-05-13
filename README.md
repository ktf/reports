## Recent AliPhysics releases
- v5-09-55c-01: Done on 2021-05-07.
## Recent O2 releases
## Recent developments in O2 - Analysis
- [\#6073](https://github.com/AliceO2Group/AliceO2/pull/6073) 2021-05-06: Merging same and mixed event correlation analysis by [@jgrosseo](https://github.com/jgrosseo)
- [\#6080](https://github.com/AliceO2Group/AliceO2/pull/6080) 2021-05-07: improving configuration harvesting by [@jgrosseo](https://github.com/jgrosseo)
- [\#6095](https://github.com/AliceO2Group/AliceO2/pull/6095) 2021-05-12: Fix check on enabled tables by [@njacazio](https://github.com/njacazio)
- [\#6096](https://github.com/AliceO2Group/AliceO2/pull/6096) 2021-05-10: Rework of some tutorials by [@pbuehler](https://github.com/pbuehler)
- [\#6118](https://github.com/AliceO2Group/AliceO2/pull/6118) 2021-05-11: PID: rename default PID tables and tasks by [@njacazio](https://github.com/njacazio)
- [\#6132](https://github.com/AliceO2Group/AliceO2/pull/6132) 2021-05-12: Changes to enable the use of fwdtrack model in the DQ analysis framework; Added computation of 2-track secondary vertices using the DCAFitterN by [@iarsene](https://github.com/iarsene)
## Recent developments in O2 - Common
- [\#6064](https://github.com/AliceO2Group/AliceO2/pull/6064) 2021-05-06: GPU Workflow: Add helper class to fill GPUIOPtr from RecoContainer by [@davidrohr](https://github.com/davidrohr)
- [\#6077](https://github.com/AliceO2Group/AliceO2/pull/6077) 2021-05-06: Multiple fixes for PVertexing and related classes by [@shahor02](https://github.com/shahor02)
- [\#6086](https://github.com/AliceO2Group/AliceO2/pull/6086) 2021-05-06: Use new clang version, enable more OpenCL extensions, revert workarounds by [@davidrohr](https://github.com/davidrohr)
- [\#6090](https://github.com/AliceO2Group/AliceO2/pull/6090) 2021-05-07: Fix file name building by [@fcatalan92](https://github.com/fcatalan92)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
- [\#6135](https://github.com/AliceO2Group/AliceO2/pull/6135) 2021-05-12: DPL: introduce accumulated metric for total bytes processed (O2-2324) by [@ktf](https://github.com/ktf)
## Recent developments in O2 - DataFormats
- [\#6064](https://github.com/AliceO2Group/AliceO2/pull/6064) 2021-05-06: GPU Workflow: Add helper class to fill GPUIOPtr from RecoContainer by [@davidrohr](https://github.com/davidrohr)
- [\#6067](https://github.com/AliceO2Group/AliceO2/pull/6067) 2021-05-06: New CPV data format by [@sevdokim](https://github.com/sevdokim)
- [\#6077](https://github.com/AliceO2Group/AliceO2/pull/6077) 2021-05-06: Multiple fixes for PVertexing and related classes by [@shahor02](https://github.com/shahor02)
- [\#6081](https://github.com/AliceO2Group/AliceO2/pull/6081) 2021-05-12: TOF calibration with cosmics + improvements for TimeCalibration framework by [@chiarazampolli](https://github.com/chiarazampolli)
- [\#6084](https://github.com/AliceO2Group/AliceO2/pull/6084) 2021-05-07: Create a class TrackTRD in o2::trd::dataformats, and add more TRD support to generic readers / recocontainer by [@davidrohr](https://github.com/davidrohr)
- [\#6090](https://github.com/AliceO2Group/AliceO2/pull/6090) 2021-05-07: Fix file name building by [@fcatalan92](https://github.com/fcatalan92)
- [\#6097](https://github.com/AliceO2Group/AliceO2/pull/6097) 2021-05-08: If we use a template for the creator callback, we can pass in different track types by [@davidrohr](https://github.com/davidrohr)
- [\#6098](https://github.com/AliceO2Group/AliceO2/pull/6098) 2021-05-07: Fix 2 minor issues when reading TRD tracks by [@davidrohr](https://github.com/davidrohr)
- [\#6104](https://github.com/AliceO2Group/AliceO2/pull/6104) 2021-05-08: RecoContainer should create sharedClusterMap only if both clusters and tracks are requested by [@davidrohr](https://github.com/davidrohr)
- [\#6107](https://github.com/AliceO2Group/AliceO2/pull/6107) 2021-05-10: Cleanup for TRD tracking by [@martenole](https://github.com/martenole)
- [\#6108](https://github.com/AliceO2Group/AliceO2/pull/6108) 2021-05-09: Use createTracksVariadic instead of createTracksWithMatchingTimeInfo by [@shahor02](https://github.com/shahor02)
- [\#6111](https://github.com/AliceO2Group/AliceO2/pull/6111) 2021-05-09: Add PVertex to RecoContainer and InputHelper, deploy in workflows by [@shahor02](https://github.com/shahor02)
- [\#6114](https://github.com/AliceO2Group/AliceO2/pull/6114) 2021-05-09: Split container-creation and ioptr-setting during o2::trd::getRecoInputContainer in 2 parts to be used individually by [@davidrohr](https://github.com/davidrohr)
- [\#6116](https://github.com/AliceO2Group/AliceO2/pull/6116) 2021-05-09: RecoContainer was requesting ITS MC labels instead of TPC labels by [@davidrohr](https://github.com/davidrohr)
- [\#6119](https://github.com/AliceO2Group/AliceO2/pull/6119) 2021-05-09: 2 minor bug fixes by [@davidrohr](https://github.com/davidrohr)
- [\#6121](https://github.com/AliceO2Group/AliceO2/pull/6121) 2021-05-11: Modify internals of RecoContainer, add fwd-declared getters + support for S-vertices (also in InputHelper) by [@shahor02](https://github.com/shahor02)
- [\#6128](https://github.com/AliceO2Group/AliceO2/pull/6128) 2021-05-11: Fix some issues in GPUWorkflowHelper needed for TRD Workflow + unrealted stuff by [@davidrohr](https://github.com/davidrohr)
- [\#6130](https://github.com/AliceO2Group/AliceO2/pull/6130) 2021-05-12: TRD tracking developments by [@martenole](https://github.com/martenole)
- [\#6138](https://github.com/AliceO2Group/AliceO2/pull/6138) 2021-05-12: TrackPar::setPID will not alter the charge by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Detectors
- [\#6053](https://github.com/AliceO2Group/AliceO2/pull/6053) 2021-05-08: [MFT] Adds configuration methods to the MFT track fitter by [@rpezzi](https://github.com/rpezzi)
- [\#6064](https://github.com/AliceO2Group/AliceO2/pull/6064) 2021-05-06: GPU Workflow: Add helper class to fill GPUIOPtr from RecoContainer by [@davidrohr](https://github.com/davidrohr)
- [\#6065](https://github.com/AliceO2Group/AliceO2/pull/6065) 2021-05-06: fluka input data filename corrected by [@amorsch](https://github.com/amorsch)
- [\#6066](https://github.com/AliceO2Group/AliceO2/pull/6066) 2021-05-06: TRD track readers + requested changes from PR6057 by [@martenole](https://github.com/martenole)
- [\#6067](https://github.com/AliceO2Group/AliceO2/pull/6067) 2021-05-06: New CPV data format by [@sevdokim](https://github.com/sevdokim)
- [\#6069](https://github.com/AliceO2Group/AliceO2/pull/6069) 2021-05-09: Tested with the Entropy Encoder. OK by [@fapfap69](https://github.com/fapfap69)
- [\#6070](https://github.com/AliceO2Group/AliceO2/pull/6070) 2021-05-08: reducing granularity in PoissonSolver test by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [\#6077](https://github.com/AliceO2Group/AliceO2/pull/6077) 2021-05-06: Multiple fixes for PVertexing and related classes by [@shahor02](https://github.com/shahor02)
- [\#6079](https://github.com/AliceO2Group/AliceO2/pull/6079) 2021-05-06: FT0,FDD Fix copy-paste errors in ini files by [@shahor02](https://github.com/shahor02)
- [\#6081](https://github.com/AliceO2Group/AliceO2/pull/6081) 2021-05-12: TOF calibration with cosmics + improvements for TimeCalibration framework by [@chiarazampolli](https://github.com/chiarazampolli)
- [\#6083](https://github.com/AliceO2Group/AliceO2/pull/6083) 2021-05-07: Log only 1st instances of Alpide/GBT errors in ITS/MFT, summarize on EOS by [@shahor02](https://github.com/shahor02)
- [\#6084](https://github.com/AliceO2Group/AliceO2/pull/6084) 2021-05-07: Create a class TrackTRD in o2::trd::dataformats, and add more TRD support to generic readers / recocontainer by [@davidrohr](https://github.com/davidrohr)
- [\#6085](https://github.com/AliceO2Group/AliceO2/pull/6085) 2021-05-08: [MCH] add optional protections against high-occupancy DE and/or event by [@pillot](https://github.com/pillot)
- [\#6086](https://github.com/AliceO2Group/AliceO2/pull/6086) 2021-05-06: Use new clang version, enable more OpenCL extensions, revert workarounds by [@davidrohr](https://github.com/davidrohr)
- [\#6090](https://github.com/AliceO2Group/AliceO2/pull/6090) 2021-05-07: Fix file name building by [@fcatalan92](https://github.com/fcatalan92)
- [\#6092](https://github.com/AliceO2Group/AliceO2/pull/6092) 2021-05-08: Multithread version of populateCCDB used at MW2 by [@shahor02](https://github.com/shahor02)
- [\#6093](https://github.com/AliceO2Group/AliceO2/pull/6093) 2021-05-10: Explicitly add direct dependencies by [@dstocco](https://github.com/dstocco)
- [\#6094](https://github.com/AliceO2Group/AliceO2/pull/6094) 2021-05-10: Fix crash occurring when MID decoder spec is stopped without having collected data by [@dstocco](https://github.com/dstocco)
- [\#6097](https://github.com/AliceO2Group/AliceO2/pull/6097) 2021-05-08: If we use a template for the creator callback, we can pass in different track types by [@davidrohr](https://github.com/davidrohr)
- [\#6098](https://github.com/AliceO2Group/AliceO2/pull/6098) 2021-05-07: Fix 2 minor issues when reading TRD tracks by [@davidrohr](https://github.com/davidrohr)
- [\#6101](https://github.com/AliceO2Group/AliceO2/pull/6101) 2021-05-08: TRD Bugfix: TPC track id is overwritten during loading by [@davidrohr](https://github.com/davidrohr)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
- [\#6104](https://github.com/AliceO2Group/AliceO2/pull/6104) 2021-05-08: RecoContainer should create sharedClusterMap only if both clusters and tracks are requested by [@davidrohr](https://github.com/davidrohr)
- [\#6107](https://github.com/AliceO2Group/AliceO2/pull/6107) 2021-05-10: Cleanup for TRD tracking by [@martenole](https://github.com/martenole)
- [\#6108](https://github.com/AliceO2Group/AliceO2/pull/6108) 2021-05-09: Use createTracksVariadic instead of createTracksWithMatchingTimeInfo by [@shahor02](https://github.com/shahor02)
- [\#6111](https://github.com/AliceO2Group/AliceO2/pull/6111) 2021-05-09: Add PVertex to RecoContainer and InputHelper, deploy in workflows by [@shahor02](https://github.com/shahor02)
- [\#6114](https://github.com/AliceO2Group/AliceO2/pull/6114) 2021-05-09: Split container-creation and ioptr-setting during o2::trd::getRecoInputContainer in 2 parts to be used individually by [@davidrohr](https://github.com/davidrohr)
- [\#6116](https://github.com/AliceO2Group/AliceO2/pull/6116) 2021-05-09: RecoContainer was requesting ITS MC labels instead of TPC labels by [@davidrohr](https://github.com/davidrohr)
- [\#6119](https://github.com/AliceO2Group/AliceO2/pull/6119) 2021-05-09: 2 minor bug fixes by [@davidrohr](https://github.com/davidrohr)
- [\#6121](https://github.com/AliceO2Group/AliceO2/pull/6121) 2021-05-11: Modify internals of RecoContainer, add fwd-declared getters + support for S-vertices (also in InputHelper) by [@shahor02](https://github.com/shahor02)
- [\#6122](https://github.com/AliceO2Group/AliceO2/pull/6122) 2021-05-10: Add --loop and --delay options to o2-ctf-reader-workflow by [@shahor02](https://github.com/shahor02)
- [\#6123](https://github.com/AliceO2Group/AliceO2/pull/6123) 2021-05-10: Fix type of aod-timeframe-id to uint64 by [@sawenzel](https://github.com/sawenzel)
- [\#6127](https://github.com/AliceO2Group/AliceO2/pull/6127) 2021-05-12: MID raw data checker workflow by [@dstocco](https://github.com/dstocco)
- [\#6128](https://github.com/AliceO2Group/AliceO2/pull/6128) 2021-05-11: Fix some issues in GPUWorkflowHelper needed for TRD Workflow + unrealted stuff by [@davidrohr](https://github.com/davidrohr)
- [\#6130](https://github.com/AliceO2Group/AliceO2/pull/6130) 2021-05-12: TRD tracking developments by [@martenole](https://github.com/martenole)
- [\#6141](https://github.com/AliceO2Group/AliceO2/pull/6141) 2021-05-12: Fix in TPC-ITS matching: cleaunup of prev TF reco buffers was incomplete by [@shahor02](https://github.com/shahor02)
- [\#6145](https://github.com/AliceO2Group/AliceO2/pull/6145) 2021-05-12: make sure MFT digi2raw creates 1 file per link if requested by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Framework
- [\#6072](https://github.com/AliceO2Group/AliceO2/pull/6072) 2021-05-06: DPL: allow for custom channel selection in multi output proxy by [@knopers8](https://github.com/knopers8)
- [\#6078](https://github.com/AliceO2Group/AliceO2/pull/6078) 2021-05-08: [QC-579] Fix detecting overlapping inputs in DataSpecUtils::includes and Data Sampling by [@knopers8](https://github.com/knopers8)
- [\#6087](https://github.com/AliceO2Group/AliceO2/pull/6087) 2021-05-07: DPL GUI: improve profiler / debugger support by [@ktf](https://github.com/ktf)
- [\#6091](https://github.com/AliceO2Group/AliceO2/pull/6091) 2021-05-09: Introduce Resource management by [@ktf](https://github.com/ktf)
- [\#6100](https://github.com/AliceO2Group/AliceO2/pull/6100) 2021-05-08: DPL GUI: support for multiple axis by [@ktf](https://github.com/ktf)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
- [\#6106](https://github.com/AliceO2Group/AliceO2/pull/6106) 2021-05-09: DPL: Print out Device name of missing input [O2-2317] by [@ktf](https://github.com/ktf)
- [\#6126](https://github.com/AliceO2Group/AliceO2/pull/6126) 2021-05-12: DPL: Propagate labels to DeviceSpec by [@knopers8](https://github.com/knopers8)
- [\#6132](https://github.com/AliceO2Group/AliceO2/pull/6132) 2021-05-12: Changes to enable the use of fwdtrack model in the DQ analysis framework; Added computation of 2-track secondary vertices using the DCAFitterN by [@iarsene](https://github.com/iarsene)
- [\#6133](https://github.com/AliceO2Group/AliceO2/pull/6133) 2021-05-11: DPL: improve documentation for DPL metrics by [@ktf](https://github.com/ktf)
- [\#6135](https://github.com/AliceO2Group/AliceO2/pull/6135) 2021-05-12: DPL: introduce accumulated metric for total bytes processed (O2-2324) by [@ktf](https://github.com/ktf)
- [\#6137](https://github.com/AliceO2Group/AliceO2/pull/6137) 2021-05-12: DPL GUI: use id rather than device name to identify metrics by [@ktf](https://github.com/ktf)
- [\#6139](https://github.com/AliceO2Group/AliceO2/pull/6139) 2021-05-12: DPL: fix off by one error in metrics by [@ktf](https://github.com/ktf)
## Recent developments in O2 - Steer
- [\#6082](https://github.com/AliceO2Group/AliceO2/pull/6082) 2021-05-06: Some fixes in digitization by [@sawenzel](https://github.com/sawenzel)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Utilities
- [\#6078](https://github.com/AliceO2Group/AliceO2/pull/6078) 2021-05-08: [QC-579] Fix detecting overlapping inputs in DataSpecUtils::includes and Data Sampling by [@knopers8](https://github.com/knopers8)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
- [\#6105](https://github.com/AliceO2Group/AliceO2/pull/6105) 2021-05-08: jobutils: Fix propagation of return codes by [@sawenzel](https://github.com/sawenzel)
