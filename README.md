## Recent AliPhysics releases
- v5-09-55c-01: Done on 2021-05-07.
## Recent O2 releases
## Recent developments in O2 - Analysis
- [\#6032](https://github.com/AliceO2Group/AliceO2/pull/6032) 2021-05-04: PWGLF: Clean spectra tasks by [@njacazio](https://github.com/njacazio)
- [\#6041](https://github.com/AliceO2Group/AliceO2/pull/6041) 2021-05-04: PWGHF: Add pt dependent mass histograms for mc task by [@ginnocen](https://github.com/ginnocen)
- [\#6043](https://github.com/AliceO2Group/AliceO2/pull/6043) 2021-05-07: PWGHF: Add PID track selector class. by [@vkucera](https://github.com/vkucera)
- [\#6058](https://github.com/AliceO2Group/AliceO2/pull/6058) 2021-05-04: Rename option in TOF MC QA by [@njacazio](https://github.com/njacazio)
- [\#6063](https://github.com/AliceO2Group/AliceO2/pull/6063) 2021-05-05: Split HistogramRegistry headers + AxisConfigurables in Correlations  by [@jgrosseo](https://github.com/jgrosseo)
- [\#6068](https://github.com/AliceO2Group/AliceO2/pull/6068) 2021-05-05: DPL: drop unneeded header. by [@ktf](https://github.com/ktf)
- [\#6073](https://github.com/AliceO2Group/AliceO2/pull/6073) 2021-05-06: Merging same and mixed event correlation analysis by [@jgrosseo](https://github.com/jgrosseo)
- [\#6080](https://github.com/AliceO2Group/AliceO2/pull/6080) 2021-05-07: improving configuration harvesting by [@jgrosseo](https://github.com/jgrosseo)
## Recent developments in O2 - Common
- [\#6057](https://github.com/AliceO2Group/AliceO2/pull/6057) 2021-05-04: Work on TRD in the GPU workflow, move around several files and reduce dependencies, some fixes by [@davidrohr](https://github.com/davidrohr)
- [\#6062](https://github.com/AliceO2Group/AliceO2/pull/6062) 2021-05-05: DPL: add a DataTakingContext to be filled with run related constants by [@ktf](https://github.com/ktf)
- [\#6064](https://github.com/AliceO2Group/AliceO2/pull/6064) 2021-05-06: GPU Workflow: Add helper class to fill GPUIOPtr from RecoContainer by [@davidrohr](https://github.com/davidrohr)
- [\#6077](https://github.com/AliceO2Group/AliceO2/pull/6077) 2021-05-06: Multiple fixes for PVertexing and related classes by [@shahor02](https://github.com/shahor02)
- [\#6086](https://github.com/AliceO2Group/AliceO2/pull/6086) 2021-05-06: Use new clang version, enable more OpenCL extensions, revert workarounds by [@davidrohr](https://github.com/davidrohr)
- [\#6090](https://github.com/AliceO2Group/AliceO2/pull/6090) 2021-05-07: Fix file name building by [@fcatalan92](https://github.com/fcatalan92)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - DataFormats
- [\#6026](https://github.com/AliceO2Group/AliceO2/pull/6026) 2021-05-03: TRD tracking adaptions in view of GPU processing by [@martenole](https://github.com/martenole)
- [\#6040](https://github.com/AliceO2Group/AliceO2/pull/6040) 2021-05-08: Ctp configuration mostly by [@lietava](https://github.com/lietava)
- [\#6042](https://github.com/AliceO2Group/AliceO2/pull/6042) 2021-05-02: RecoContainer: considers simpler contributors if derived track was rejected by [@shahor02](https://github.com/shahor02)
- [\#6045](https://github.com/AliceO2Group/AliceO2/pull/6045) 2021-05-03: Adapt ITS-TPC matching combined or separate ITS-(TPC,TPC-TOF) input by [@shahor02](https://github.com/shahor02)
- [\#6046](https://github.com/AliceO2Group/AliceO2/pull/6046) 2021-05-03: Fix in GlobalTrackID::includesDet method by [@shahor02](https://github.com/shahor02)
- [\#6050](https://github.com/AliceO2Group/AliceO2/pull/6050) 2021-05-03: IDC data format + unrelated fixes by [@wiechula](https://github.com/wiechula)
- [\#6059](https://github.com/AliceO2Group/AliceO2/pull/6059) 2021-05-04: Add missing header to ROOTMAP by [@davidrohr](https://github.com/davidrohr)
- [\#6064](https://github.com/AliceO2Group/AliceO2/pull/6064) 2021-05-06: GPU Workflow: Add helper class to fill GPUIOPtr from RecoContainer by [@davidrohr](https://github.com/davidrohr)
- [\#6067](https://github.com/AliceO2Group/AliceO2/pull/6067) 2021-05-06: New CPV data format by [@sevdokim](https://github.com/sevdokim)
- [\#6077](https://github.com/AliceO2Group/AliceO2/pull/6077) 2021-05-06: Multiple fixes for PVertexing and related classes by [@shahor02](https://github.com/shahor02)
- [\#6084](https://github.com/AliceO2Group/AliceO2/pull/6084) 2021-05-07: Create a class TrackTRD in o2::trd::dataformats, and add more TRD support to generic readers / recocontainer by [@davidrohr](https://github.com/davidrohr)
- [\#6090](https://github.com/AliceO2Group/AliceO2/pull/6090) 2021-05-07: Fix file name building by [@fcatalan92](https://github.com/fcatalan92)
- [\#6097](https://github.com/AliceO2Group/AliceO2/pull/6097) 2021-05-08: If we use a template for the creator callback, we can pass in different track types by [@davidrohr](https://github.com/davidrohr)
- [\#6098](https://github.com/AliceO2Group/AliceO2/pull/6098) 2021-05-07: Fix 2 minor issues when reading TRD tracks by [@davidrohr](https://github.com/davidrohr)
- [\#6104](https://github.com/AliceO2Group/AliceO2/pull/6104) 2021-05-08: RecoContainer should create sharedClusterMap only if both clusters and tracks are requested by [@davidrohr](https://github.com/davidrohr)
- [\#6108](https://github.com/AliceO2Group/AliceO2/pull/6108) 2021-05-09: Use createTracksVariadic instead of createTracksWithMatchingTimeInfo by [@shahor02](https://github.com/shahor02)
- [\#6111](https://github.com/AliceO2Group/AliceO2/pull/6111) 2021-05-09: Add PVertex to RecoContainer and InputHelper, deploy in workflows by [@shahor02](https://github.com/shahor02)
- [\#6114](https://github.com/AliceO2Group/AliceO2/pull/6114) 2021-05-09: Split container-creation and ioptr-setting during o2::trd::getRecoInputContainer in 2 parts to be used individually by [@davidrohr](https://github.com/davidrohr)
- [\#6116](https://github.com/AliceO2Group/AliceO2/pull/6116) 2021-05-09: RecoContainer was requesting ITS MC labels instead of TPC labels by [@davidrohr](https://github.com/davidrohr)
- [\#6119](https://github.com/AliceO2Group/AliceO2/pull/6119) 2021-05-09: 2 minor bug fixes by [@davidrohr](https://github.com/davidrohr)
## Recent developments in O2 - Detectors
- [\#6026](https://github.com/AliceO2Group/AliceO2/pull/6026) 2021-05-03: TRD tracking adaptions in view of GPU processing by [@martenole](https://github.com/martenole)
- [\#6036](https://github.com/AliceO2Group/AliceO2/pull/6036) 2021-05-03: Ensure MFT digits are decoded in chipID increasing order by [@shahor02](https://github.com/shahor02)
- [\#6038](https://github.com/AliceO2Group/AliceO2/pull/6038) 2021-05-02:  Raw decoding optimized; Made Mapping singleton; Semigauss raw fitter added; by [@peressounko](https://github.com/peressounko)
- [\#6040](https://github.com/AliceO2Group/AliceO2/pull/6040) 2021-05-08: Ctp configuration mostly by [@lietava](https://github.com/lietava)
- [\#6042](https://github.com/AliceO2Group/AliceO2/pull/6042) 2021-05-02: RecoContainer: considers simpler contributors if derived track was rejected by [@shahor02](https://github.com/shahor02)
- [\#6045](https://github.com/AliceO2Group/AliceO2/pull/6045) 2021-05-03: Adapt ITS-TPC matching combined or separate ITS-(TPC,TPC-TOF) input by [@shahor02](https://github.com/shahor02)
- [\#6047](https://github.com/AliceO2Group/AliceO2/pull/6047) 2021-05-04: Use InputHelper in global workflows, avoid global DataRequest + related fixes by [@shahor02](https://github.com/shahor02)
- [\#6050](https://github.com/AliceO2Group/AliceO2/pull/6050) 2021-05-03: IDC data format + unrelated fixes by [@wiechula](https://github.com/wiechula)
- [\#6053](https://github.com/AliceO2Group/AliceO2/pull/6053) 2021-05-08: [MFT] Adds configuration methods to the MFT track fitter by [@rpezzi](https://github.com/rpezzi)
- [\#6057](https://github.com/AliceO2Group/AliceO2/pull/6057) 2021-05-04: Work on TRD in the GPU workflow, move around several files and reduce dependencies, some fixes by [@davidrohr](https://github.com/davidrohr)
- [\#6060](https://github.com/AliceO2Group/AliceO2/pull/6060) 2021-05-04: MCH: adapted page reader output spec to three-letters standard by [@aferrero2707](https://github.com/aferrero2707)
- [\#6064](https://github.com/AliceO2Group/AliceO2/pull/6064) 2021-05-06: GPU Workflow: Add helper class to fill GPUIOPtr from RecoContainer by [@davidrohr](https://github.com/davidrohr)
- [\#6065](https://github.com/AliceO2Group/AliceO2/pull/6065) 2021-05-06: fluka input data filename corrected by [@amorsch](https://github.com/amorsch)
- [\#6066](https://github.com/AliceO2Group/AliceO2/pull/6066) 2021-05-06: TRD track readers + requested changes from PR6057 by [@martenole](https://github.com/martenole)
- [\#6067](https://github.com/AliceO2Group/AliceO2/pull/6067) 2021-05-06: New CPV data format by [@sevdokim](https://github.com/sevdokim)
- [\#6069](https://github.com/AliceO2Group/AliceO2/pull/6069) 2021-05-09: Tested with the Entropy Encoder. OK by [@fapfap69](https://github.com/fapfap69)
- [\#6070](https://github.com/AliceO2Group/AliceO2/pull/6070) 2021-05-08: reducing granularity in PoissonSolver test by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [\#6077](https://github.com/AliceO2Group/AliceO2/pull/6077) 2021-05-06: Multiple fixes for PVertexing and related classes by [@shahor02](https://github.com/shahor02)
- [\#6079](https://github.com/AliceO2Group/AliceO2/pull/6079) 2021-05-06: FT0,FDD Fix copy-paste errors in ini files by [@shahor02](https://github.com/shahor02)
- [\#6083](https://github.com/AliceO2Group/AliceO2/pull/6083) 2021-05-07: Log only 1st instances of Alpide/GBT errors in ITS/MFT, summarize on EOS by [@shahor02](https://github.com/shahor02)
- [\#6084](https://github.com/AliceO2Group/AliceO2/pull/6084) 2021-05-07: Create a class TrackTRD in o2::trd::dataformats, and add more TRD support to generic readers / recocontainer by [@davidrohr](https://github.com/davidrohr)
- [\#6085](https://github.com/AliceO2Group/AliceO2/pull/6085) 2021-05-08: [MCH] add optional protections against high-occupancy DE and/or event by [@pillot](https://github.com/pillot)
- [\#6086](https://github.com/AliceO2Group/AliceO2/pull/6086) 2021-05-06: Use new clang version, enable more OpenCL extensions, revert workarounds by [@davidrohr](https://github.com/davidrohr)
- [\#6090](https://github.com/AliceO2Group/AliceO2/pull/6090) 2021-05-07: Fix file name building by [@fcatalan92](https://github.com/fcatalan92)
- [\#6092](https://github.com/AliceO2Group/AliceO2/pull/6092) 2021-05-08: Multithread version of populateCCDB used at MW2 by [@shahor02](https://github.com/shahor02)
- [\#6097](https://github.com/AliceO2Group/AliceO2/pull/6097) 2021-05-08: If we use a template for the creator callback, we can pass in different track types by [@davidrohr](https://github.com/davidrohr)
- [\#6098](https://github.com/AliceO2Group/AliceO2/pull/6098) 2021-05-07: Fix 2 minor issues when reading TRD tracks by [@davidrohr](https://github.com/davidrohr)
- [\#6101](https://github.com/AliceO2Group/AliceO2/pull/6101) 2021-05-08: TRD Bugfix: TPC track id is overwritten during loading by [@davidrohr](https://github.com/davidrohr)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
- [\#6104](https://github.com/AliceO2Group/AliceO2/pull/6104) 2021-05-08: RecoContainer should create sharedClusterMap only if both clusters and tracks are requested by [@davidrohr](https://github.com/davidrohr)
- [\#6108](https://github.com/AliceO2Group/AliceO2/pull/6108) 2021-05-09: Use createTracksVariadic instead of createTracksWithMatchingTimeInfo by [@shahor02](https://github.com/shahor02)
- [\#6111](https://github.com/AliceO2Group/AliceO2/pull/6111) 2021-05-09: Add PVertex to RecoContainer and InputHelper, deploy in workflows by [@shahor02](https://github.com/shahor02)
- [\#6114](https://github.com/AliceO2Group/AliceO2/pull/6114) 2021-05-09: Split container-creation and ioptr-setting during o2::trd::getRecoInputContainer in 2 parts to be used individually by [@davidrohr](https://github.com/davidrohr)
- [\#6116](https://github.com/AliceO2Group/AliceO2/pull/6116) 2021-05-09: RecoContainer was requesting ITS MC labels instead of TPC labels by [@davidrohr](https://github.com/davidrohr)
- [\#6119](https://github.com/AliceO2Group/AliceO2/pull/6119) 2021-05-09: 2 minor bug fixes by [@davidrohr](https://github.com/davidrohr)
## Recent developments in O2 - Framework
- [\#6051](https://github.com/AliceO2Group/AliceO2/pull/6051) 2021-05-03: DPL Analysis: fix for spawner trying to create a projector for a table with empty schema by [@aalkin](https://github.com/aalkin)
- [\#6062](https://github.com/AliceO2Group/AliceO2/pull/6062) 2021-05-05: DPL: add a DataTakingContext to be filled with run related constants by [@ktf](https://github.com/ktf)
- [\#6063](https://github.com/AliceO2Group/AliceO2/pull/6063) 2021-05-05: Split HistogramRegistry headers + AxisConfigurables in Correlations  by [@jgrosseo](https://github.com/jgrosseo)
- [\#6068](https://github.com/AliceO2Group/AliceO2/pull/6068) 2021-05-05: DPL: drop unneeded header. by [@ktf](https://github.com/ktf)
- [\#6071](https://github.com/AliceO2Group/AliceO2/pull/6071) 2021-05-05: AliECS dump: parametrize session id by [@knopers8](https://github.com/knopers8)
- [\#6072](https://github.com/AliceO2Group/AliceO2/pull/6072) 2021-05-06: DPL: allow for custom channel selection in multi output proxy by [@knopers8](https://github.com/knopers8)
- [\#6078](https://github.com/AliceO2Group/AliceO2/pull/6078) 2021-05-08: [QC-579] Fix detecting overlapping inputs in DataSpecUtils::includes and Data Sampling by [@knopers8](https://github.com/knopers8)
- [\#6087](https://github.com/AliceO2Group/AliceO2/pull/6087) 2021-05-07: DPL GUI: improve profiler / debugger support by [@ktf](https://github.com/ktf)
- [\#6091](https://github.com/AliceO2Group/AliceO2/pull/6091) 2021-05-09: Introduce Resource management by [@ktf](https://github.com/ktf)
- [\#6100](https://github.com/AliceO2Group/AliceO2/pull/6100) 2021-05-08: DPL GUI: support for multiple axis by [@ktf](https://github.com/ktf)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
- [\#6106](https://github.com/AliceO2Group/AliceO2/pull/6106) 2021-05-09: DPL: Print out Device name of missing input [O2-2317] by [@ktf](https://github.com/ktf)
## Recent developments in O2 - Steer
- [\#6040](https://github.com/AliceO2Group/AliceO2/pull/6040) 2021-05-08: Ctp configuration mostly by [@lietava](https://github.com/lietava)
- [\#6057](https://github.com/AliceO2Group/AliceO2/pull/6057) 2021-05-04: Work on TRD in the GPU workflow, move around several files and reduce dependencies, some fixes by [@davidrohr](https://github.com/davidrohr)
- [\#6082](https://github.com/AliceO2Group/AliceO2/pull/6082) 2021-05-06: Some fixes in digitization by [@sawenzel](https://github.com/sawenzel)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Utilities
- [\#6048](https://github.com/AliceO2Group/AliceO2/pull/6048) 2021-05-03: jobutils: More robust return code determination by [@sawenzel](https://github.com/sawenzel)
- [\#6078](https://github.com/AliceO2Group/AliceO2/pull/6078) 2021-05-08: [QC-579] Fix detecting overlapping inputs in DataSpecUtils::includes and Data Sampling by [@knopers8](https://github.com/knopers8)
- [\#6102](https://github.com/AliceO2Group/AliceO2/pull/6102) 2021-05-09: boost::filesystem -> std::filesystem by [@shahor02](https://github.com/shahor02)
- [\#6105](https://github.com/AliceO2Group/AliceO2/pull/6105) 2021-05-08: jobutils: Fix propagation of return codes by [@sawenzel](https://github.com/sawenzel)
