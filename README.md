## Recent AliPhysics releases
## Recent O2 releases
## Recent developments in O2 - Analysis
	- [\#12990](https://github.com/AliceO2Group/AliceO2/pull/12990) 2024-04-08: Add missing energy column in StoredTracksIU by [@vkucera](https://github.com/vkucera)
	- [\#12991](https://github.com/AliceO2Group/AliceO2/pull/12991) 2024-04-11: Add momentum vector in track tables by [@vkucera](https://github.com/vkucera)
	- [\#13006](https://github.com/AliceO2Group/AliceO2/pull/13006) 2024-04-10: DPL Analysis: add ability to have ConfigurableGroup produce prefixed options by [@aalkin](https://github.com/aalkin)
	- [\#13043](https://github.com/AliceO2Group/AliceO2/pull/13043) 2024-04-19: Add pVector in McParticles by [@vkucera](https://github.com/vkucera)
## Recent developments in O2 - Common
	- [\#12998](https://github.com/AliceO2Group/AliceO2/pull/12998) 2024-04-11: QC-1143 Merge objects before publishing at End Of Stream by [@knopers8](https://github.com/knopers8)
	- [\#13018](https://github.com/AliceO2Group/AliceO2/pull/13018) 2024-04-17: [EMCAL-565] Add cut on pre and post trigger pile-up by [@jokonig](https://github.com/jokonig)
	- [\#13031](https://github.com/AliceO2Group/AliceO2/pull/13031) 2024-04-16: DPL: Fix orderedCompletionPolicy getting stuck when oldestPossibleTimeslice message jumps by > 1 at once, and any but the last TF in the jump range is missing by [@davidrohr](https://github.com/davidrohr)
	- [\#13055](https://github.com/AliceO2Group/AliceO2/pull/13055) 2024-04-20: multiple fixes for mp alignment framework by [@shahor02](https://github.com/shahor02)
	- [\#13065](https://github.com/AliceO2Group/AliceO2/pull/13065) 2024-04-23: GPU: Do not use printf in GPU code if GPUCA_GPU_DEBUG_PRINT is not defined by [@davidrohr](https://github.com/davidrohr)
## Recent developments in O2 - DataFormats
	- [\#12979](https://github.com/AliceO2Group/AliceO2/pull/12979) 2024-04-03: print function for MCEventHeader by [@sawenzel](https://github.com/sawenzel)
	- [\#13003](https://github.com/AliceO2Group/AliceO2/pull/13003) 2024-04-10: Group tracks per vertex in the TrackingStudy output, extra info by [@shahor02](https://github.com/shahor02)
	- [\#13016](https://github.com/AliceO2Group/AliceO2/pull/13016) 2024-04-12: TOF matching debug mode improvements by [@noferini](https://github.com/noferini)
	- [\#13021](https://github.com/AliceO2Group/AliceO2/pull/13021) 2024-04-15: trivial fix in one TOF setter by [@noferini](https://github.com/noferini)
	- [\#13022](https://github.com/AliceO2Group/AliceO2/pull/13022) 2024-04-15: Do not store failed laser calib, ignore in VDriftHelper by [@shahor02](https://github.com/shahor02)
	- [\#13027](https://github.com/AliceO2Group/AliceO2/pull/13027) 2024-04-15: [EMCAL-710] Fix namespace in stream operator by [@mfasDa](https://github.com/mfasDa)
	- [\#13040](https://github.com/AliceO2Group/AliceO2/pull/13040) 2024-04-21: [EMCAL-916, EMCAL-537, EMCAL-550, EMCAL-911] Integrate TRU decoding into sync reco by [@mfasDa](https://github.com/mfasDa)
	- [\#13052](https://github.com/AliceO2Group/AliceO2/pull/13052) 2024-04-19: [EMCAL-710] Fix number of error types after adding STU decoder errors by [@mfasDa](https://github.com/mfasDa)
	- [\#13053](https://github.com/AliceO2Group/AliceO2/pull/13053) 2024-04-22: Allow for smooth move to the new naming of QC flags by [@knopers8](https://github.com/knopers8)
	- [\#13055](https://github.com/AliceO2Group/AliceO2/pull/13055) 2024-04-20: multiple fixes for mp alignment framework by [@shahor02](https://github.com/shahor02)
	- [\#13065](https://github.com/AliceO2Group/AliceO2/pull/13065) 2024-04-23: GPU: Do not use printf in GPU code if GPUCA_GPU_DEBUG_PRINT is not defined by [@davidrohr](https://github.com/davidrohr)
## Recent developments in O2 - Detectors
	- [\#12978](https://github.com/AliceO2Group/AliceO2/pull/12978) 2024-04-03: ClusterSharingMapSpec loads GRPECS for NHBFPerTF by [@shahor02](https://github.com/shahor02)
	- [\#12982](https://github.com/AliceO2Group/AliceO2/pull/12982) 2024-04-05: Fixes for isolated QC step by [@shahor02](https://github.com/shahor02)
	- [\#12983](https://github.com/AliceO2Group/AliceO2/pull/12983) 2024-04-04: [EMCAL-1116] Fix in mapping for pedestal calibration by [@jokonig](https://github.com/jokonig)
	- [\#12984](https://github.com/AliceO2Group/AliceO2/pull/12984) 2024-04-05: SV study: fix in eta cut application, store matching info by [@shahor02](https://github.com/shahor02)
	- [\#12985](https://github.com/AliceO2Group/AliceO2/pull/12985) 2024-04-05: [EMCAL-1116] Minor improvemts to pedestal calibrator by [@jokonig](https://github.com/jokonig)
	- [\#12992](https://github.com/AliceO2Group/AliceO2/pull/12992) 2024-04-15: Allow specifying different track source for TPC map extraction by [@martenole](https://github.com/martenole)
	- [\#12994](https://github.com/AliceO2Group/AliceO2/pull/12994) 2024-04-07: Group refitted V0s per PV, add extra info by [@shahor02](https://github.com/shahor02)
	- [\#12995](https://github.com/AliceO2Group/AliceO2/pull/12995) 2024-04-07: Do not create RCT entry at EOR, update only SOR version by [@shahor02](https://github.com/shahor02)
	- [\#12996](https://github.com/AliceO2Group/AliceO2/pull/12996) 2024-04-11: [EMCAL-1120] Encode trailer in decimal format instead of hex format. by [@mfasDa](https://github.com/mfasDa)
	- [\#12997](https://github.com/AliceO2Group/AliceO2/pull/12997) 2024-04-09: Optionally store ref.track together with moved one. by [@shahor02](https://github.com/shahor02)
	- [\#13001](https://github.com/AliceO2Group/AliceO2/pull/13001) 2024-04-10: Fix in passing TPC t0 to vdrift calibrations by [@shahor02](https://github.com/shahor02)
	- [\#13002](https://github.com/AliceO2Group/AliceO2/pull/13002) 2024-04-10: Warn about current and TPC scaler object runNumbers only once by [@shahor02](https://github.com/shahor02)
	- [\#13003](https://github.com/AliceO2Group/AliceO2/pull/13003) 2024-04-10: Group tracks per vertex in the TrackingStudy output, extra info by [@shahor02](https://github.com/shahor02)
	- [\#13004](https://github.com/AliceO2Group/AliceO2/pull/13004) 2024-04-15: Uniform A-side X coordinate sign with the reconstructed one by [@coppedis](https://github.com/coppedis)
	- [\#13009](https://github.com/AliceO2Group/AliceO2/pull/13009) 2024-04-11: rct-updater defines dummy output to bind ccdb-populator by [@shahor02](https://github.com/shahor02)
	- [\#13010](https://github.com/AliceO2Group/AliceO2/pull/13010) 2024-04-11: Send CTF size report for QC monitoring by [@martenole](https://github.com/martenole)
	- [\#13011](https://github.com/AliceO2Group/AliceO2/pull/13011) 2024-04-11: Alice3: add minimal documentation + Magnetic field macro by [@mconcas](https://github.com/mconcas)
	- [\#13012](https://github.com/AliceO2Group/AliceO2/pull/13012) 2024-04-11: Add support for ONNXRuntime 1.17.1 by [@ktf](https://github.com/ktf)
	- [\#13013](https://github.com/AliceO2Group/AliceO2/pull/13013) 2024-04-15: Account EmptyChips in active chips status by [@shahor02](https://github.com/shahor02)
	- [\#13015](https://github.com/AliceO2Group/AliceO2/pull/13015) 2024-04-18: Simdigitizer by [@gvolpe79](https://github.com/gvolpe79)
	- [\#13016](https://github.com/AliceO2Group/AliceO2/pull/13016) 2024-04-12: TOF matching debug mode improvements by [@noferini](https://github.com/noferini)
	- [\#13018](https://github.com/AliceO2Group/AliceO2/pull/13018) 2024-04-17: [EMCAL-565] Add cut on pre and post trigger pile-up by [@jokonig](https://github.com/jokonig)
	- [\#13019](https://github.com/AliceO2Group/AliceO2/pull/13019) 2024-04-12: Fix RCTUpdater warning message by [@martenole](https://github.com/martenole)
	- [\#13022](https://github.com/AliceO2Group/AliceO2/pull/13022) 2024-04-15: Do not store failed laser calib, ignore in VDriftHelper by [@shahor02](https://github.com/shahor02)
	- [\#13023](https://github.com/AliceO2Group/AliceO2/pull/13023) 2024-04-13: Use detectror-specific AlpideParam for ROF-rate check by [@shahor02](https://github.com/shahor02)
	- [\#13024](https://github.com/AliceO2Group/AliceO2/pull/13024) 2024-04-14: Skip empty ROFs only with no-empty-rof option in digi2raw by [@shahor02](https://github.com/shahor02)
	- [\#13025](https://github.com/AliceO2Group/AliceO2/pull/13025) 2024-04-15: macro to dump volumes ideal and real origins in lab frame by [@shahor02](https://github.com/shahor02)
	- [\#13026](https://github.com/AliceO2Group/AliceO2/pull/13026) 2024-04-15: Add debug output to TRD gain calibration by [@martenole](https://github.com/martenole)
	- [\#13027](https://github.com/AliceO2Group/AliceO2/pull/13027) 2024-04-15: [EMCAL-710] Fix namespace in stream operator by [@mfasDa](https://github.com/mfasDa)
	- [\#13029](https://github.com/AliceO2Group/AliceO2/pull/13029) 2024-04-18: add protection in TOF geo by [@noferini](https://github.com/noferini)
	- [\#13030](https://github.com/AliceO2Group/AliceO2/pull/13030) 2024-04-18: fix missing fitting of HV in HMPIDDCSProcessor by [@gvolpe79](https://github.com/gvolpe79)
	- [\#13032](https://github.com/AliceO2Group/AliceO2/pull/13032) 2024-04-17: EMCAL increase check interval for bad channel and time calibrations by [@martenole](https://github.com/martenole)
	- [\#13033](https://github.com/AliceO2Group/AliceO2/pull/13033) 2024-04-16: Fixe TPC clusters extraction for millepede, decrease verbosity of RootTreeReader by [@shahor02](https://github.com/shahor02)
	- [\#13034](https://github.com/AliceO2Group/AliceO2/pull/13034) 2024-04-17: [MCH] new options to add channels from DE Ids and HV/LV DCS aliases by [@pillot](https://github.com/pillot)
	- [\#13035](https://github.com/AliceO2Group/AliceO2/pull/13035) 2024-04-17: Option to manage ROF length reporting by [@shahor02](https://github.com/shahor02)
	- [\#13039](https://github.com/AliceO2Group/AliceO2/pull/13039) 2024-04-17: [EMCAL-565] Fix axis for time histogram in bad channel calibration by [@jokonig](https://github.com/jokonig)
	- [\#13040](https://github.com/AliceO2Group/AliceO2/pull/13040) 2024-04-21: [EMCAL-916, EMCAL-537, EMCAL-550, EMCAL-911] Integrate TRU decoding into sync reco by [@mfasDa](https://github.com/mfasDa)
	- [\#13045](https://github.com/AliceO2Group/AliceO2/pull/13045) 2024-04-19: [EMCAL-565, EMCAL-566] Prevent saving/overwriting calib multiple times at EOR by [@jokonig](https://github.com/jokonig)
	- [\#13046](https://github.com/AliceO2Group/AliceO2/pull/13046) 2024-04-19: Fix bug when reading input string for chamber fixing by [@Elros60](https://github.com/Elros60)
	- [\#13048](https://github.com/AliceO2Group/AliceO2/pull/13048) 2024-04-23: TPC/simulation: Add PT correction to gas density using configurable p… by [@tubagundem](https://github.com/tubagundem)
	- [\#13052](https://github.com/AliceO2Group/AliceO2/pull/13052) 2024-04-19: [EMCAL-710] Fix number of error types after adding STU decoder errors by [@mfasDa](https://github.com/mfasDa)
	- [\#13055](https://github.com/AliceO2Group/AliceO2/pull/13055) 2024-04-20: multiple fixes for mp alignment framework by [@shahor02](https://github.com/shahor02)
	- [\#13056](https://github.com/AliceO2Group/AliceO2/pull/13056) 2024-04-21: GPU ITS tracking: make tracking mode available in configKeyVals + fixes by [@mconcas](https://github.com/mconcas)
	- [\#13057](https://github.com/AliceO2Group/AliceO2/pull/13057) 2024-04-21: ITS: Add track writer workflow by [@mconcas](https://github.com/mconcas)
	- [\#13059](https://github.com/AliceO2Group/AliceO2/pull/13059) 2024-04-21: Name debug stream according to the lane rules by [@shahor02](https://github.com/shahor02)
	- [\#13060](https://github.com/AliceO2Group/AliceO2/pull/13060) 2024-04-22: [EMCAL-630] Improve documentation of RawToCellConverterSpec by [@mfasDa](https://github.com/mfasDa)
	- [\#13062](https://github.com/AliceO2Group/AliceO2/pull/13062) 2024-04-22: Account ITS/MFT ROF start shift in AOD ITS/MFT standalone tracks time by [@shahor02](https://github.com/shahor02)
	- [\#13064](https://github.com/AliceO2Group/AliceO2/pull/13064) 2024-04-23: Add mult estimators to matching debug output by [@shahor02](https://github.com/shahor02)
	- [\#13065](https://github.com/AliceO2Group/AliceO2/pull/13065) 2024-04-23: GPU: Do not use printf in GPU code if GPUCA_GPU_DEBUG_PRINT is not defined by [@davidrohr](https://github.com/davidrohr)
	- [\#13066](https://github.com/AliceO2Group/AliceO2/pull/13066) 2024-04-25: PHS: publish pedestal vector at PHS/PedestalRun/Pedestals in the CCDB by [@sevdokim](https://github.com/sevdokim)
	- [\#13075](https://github.com/AliceO2Group/AliceO2/pull/13075) 2024-04-25: fix mult. estimator for ITSMFT debug output by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Framework
	- [\#12977](https://github.com/AliceO2Group/AliceO2/pull/12977) 2024-04-03: DPL: Improve warning message by [@davidrohr](https://github.com/davidrohr)
	- [\#12990](https://github.com/AliceO2Group/AliceO2/pull/12990) 2024-04-08: Add missing energy column in StoredTracksIU by [@vkucera](https://github.com/vkucera)
	- [\#12991](https://github.com/AliceO2Group/AliceO2/pull/12991) 2024-04-11: Add momentum vector in track tables by [@vkucera](https://github.com/vkucera)
	- [\#12993](https://github.com/AliceO2Group/AliceO2/pull/12993) 2024-04-06: reserve bit of mc particle flag for OOB pileup tagging by [@maciacco](https://github.com/maciacco)
	- [\#13006](https://github.com/AliceO2Group/AliceO2/pull/13006) 2024-04-10: DPL Analysis: add ability to have ConfigurableGroup produce prefixed options by [@aalkin](https://github.com/aalkin)
	- [\#13007](https://github.com/AliceO2Group/AliceO2/pull/13007) 2024-04-11: Add comment to labelledArray types by [@jgrosseo](https://github.com/jgrosseo)
	- [\#13031](https://github.com/AliceO2Group/AliceO2/pull/13031) 2024-04-16: DPL: Fix orderedCompletionPolicy getting stuck when oldestPossibleTimeslice message jumps by > 1 at once, and any but the last TF in the jump range is missing by [@davidrohr](https://github.com/davidrohr)
	- [\#13033](https://github.com/AliceO2Group/AliceO2/pull/13033) 2024-04-16: Fixe TPC clusters extraction for millepede, decrease verbosity of RootTreeReader by [@shahor02](https://github.com/shahor02)
	- [\#13036](https://github.com/AliceO2Group/AliceO2/pull/13036) 2024-04-23: Demote exit transition timeout error to warning by [@martenole](https://github.com/martenole)
	- [\#13043](https://github.com/AliceO2Group/AliceO2/pull/13043) 2024-04-19: Add pVector in McParticles by [@vkucera](https://github.com/vkucera)
	- [\#13051](https://github.com/AliceO2Group/AliceO2/pull/13051) 2024-04-22: DPL: Fix memory leak in variant_helper by [@ktf](https://github.com/ktf)
## Recent developments in O2 - Generators
	- [\#12980](https://github.com/AliceO2Group/AliceO2/pull/12980) 2024-04-05: Providing an box generator natively for ALICEO2. by [@sawenzel](https://github.com/sawenzel)
## Recent developments in O2 - Steer
	- [\#13000](https://github.com/AliceO2Group/AliceO2/pull/13000) 2024-04-09: Digitization: Fix timestamps for querying CCDB when using BasicCCDBMa… by [@sawenzel](https://github.com/sawenzel)
	- [\#13015](https://github.com/AliceO2Group/AliceO2/pull/13015) 2024-04-18: Simdigitizer by [@gvolpe79](https://github.com/gvolpe79)
## Recent developments in O2 - Utilities
	- [\#12987](https://github.com/AliceO2Group/AliceO2/pull/12987) 2024-04-05: EPN Stderr monitor: Prepend messages from syslog with [GLOBAL SYSLOG] by [@davidrohr](https://github.com/davidrohr)
	- [\#12998](https://github.com/AliceO2Group/AliceO2/pull/12998) 2024-04-11: QC-1143 Merge objects before publishing at End Of Stream by [@knopers8](https://github.com/knopers8)
