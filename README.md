## Recent AliPhysics releases
## Recent O2 releases
## Recent developments in O2 - Analysis
	- [\#12942](https://github.com/AliceO2Group/AliceO2/pull/12942) 2024-03-27: DPL Analysis: fix off-by-one when looking up filter info by [@aalkin](https://github.com/aalkin)
	- [\#12990](https://github.com/AliceO2Group/AliceO2/pull/12990) 2024-04-08: Add missing energy column in StoredTracksIU by [@vkucera](https://github.com/vkucera)
	- [\#12991](https://github.com/AliceO2Group/AliceO2/pull/12991) 2024-04-11: Add momentum vector in track tables by [@vkucera](https://github.com/vkucera)
	- [\#13006](https://github.com/AliceO2Group/AliceO2/pull/13006) 2024-04-10: DPL Analysis: add ability to have ConfigurableGroup produce prefixed options by [@aalkin](https://github.com/aalkin)
## Recent developments in O2 - Common
	- [\#12938](https://github.com/AliceO2Group/AliceO2/pull/12938) 2024-03-26: Add number of entries in operator+= by [@mfasDa](https://github.com/mfasDa)
	- [\#12943](https://github.com/AliceO2Group/AliceO2/pull/12943) 2024-03-27: GPU: CMake improvements towards porting all CUDA features to HIP and some related cleanup by [@davidrohr](https://github.com/davidrohr)
	- [\#12947](https://github.com/AliceO2Group/AliceO2/pull/12947) 2024-03-28: DPL: replace LOG with Signposts by [@ktf](https://github.com/ktf)
	- [\#12954](https://github.com/AliceO2Group/AliceO2/pull/12954) 2024-04-03: More consistent MCHeader forwarding when using GeneratorFromFile by [@sawenzel](https://github.com/sawenzel)
	- [\#12956](https://github.com/AliceO2Group/AliceO2/pull/12956) 2024-03-28: DPL: fix spurios error message and wrong update. by [@ktf](https://github.com/ktf)
	- [\#12998](https://github.com/AliceO2Group/AliceO2/pull/12998) 2024-04-11: QC-1143 Merge objects before publishing at End Of Stream by [@knopers8](https://github.com/knopers8)
	- [\#13031](https://github.com/AliceO2Group/AliceO2/pull/13031) 2024-04-16: DPL: Fix orderedCompletionPolicy getting stuck when oldestPossibleTimeslice message jumps by > 1 at once, and any but the last TF in the jump range is missing by [@davidrohr](https://github.com/davidrohr)
## Recent developments in O2 - DataFormats
	- [\#12960](https://github.com/AliceO2Group/AliceO2/pull/12960) 2024-03-29: GPU: Several minor fixes / improvements by [@davidrohr](https://github.com/davidrohr)
	- [\#12970](https://github.com/AliceO2Group/AliceO2/pull/12970) 2024-04-06: TPC: Use qmax/time contributions to cluster error and occupancy estimators - not yet final, don't merge by [@davidrohr](https://github.com/davidrohr)
	- [\#12979](https://github.com/AliceO2Group/AliceO2/pull/12979) 2024-04-03: print function for MCEventHeader by [@sawenzel](https://github.com/sawenzel)
	- [\#13003](https://github.com/AliceO2Group/AliceO2/pull/13003) 2024-04-10: Group tracks per vertex in the TrackingStudy output, extra info by [@shahor02](https://github.com/shahor02)
	- [\#13016](https://github.com/AliceO2Group/AliceO2/pull/13016) 2024-04-12: TOF matching debug mode improvements by [@noferini](https://github.com/noferini)
	- [\#13021](https://github.com/AliceO2Group/AliceO2/pull/13021) 2024-04-15: trivial fix in one TOF setter by [@noferini](https://github.com/noferini)
	- [\#13022](https://github.com/AliceO2Group/AliceO2/pull/13022) 2024-04-15: Do not store failed laser calib, ignore in VDriftHelper by [@shahor02](https://github.com/shahor02)
	- [\#13027](https://github.com/AliceO2Group/AliceO2/pull/13027) 2024-04-15: [EMCAL-710] Fix namespace in stream operator by [@mfasDa](https://github.com/mfasDa)
## Recent developments in O2 - Detectors
	- [\#12941](https://github.com/AliceO2Group/AliceO2/pull/12941) 2024-03-27: Fix bug in MIP dE/dx vs sector plot by [@lauraser](https://github.com/lauraser)
	- [\#12944](https://github.com/AliceO2Group/AliceO2/pull/12944) 2024-03-28: [EMCAL-1115] Fix container size for LEDMONs by [@mfasDa](https://github.com/mfasDa)
	- [\#12945](https://github.com/AliceO2Group/AliceO2/pull/12945) 2024-04-01: [MCH] new functionalities to fill the status map by [@pillot](https://github.com/pillot)
	- [\#12948](https://github.com/AliceO2Group/AliceO2/pull/12948) 2024-03-28: ITS GPU: INVALID_TRIGGER_ERROR_NO_HOST_CODE should not be defined away but GPUg() should only be used in GPUCode by [@davidrohr](https://github.com/davidrohr)
	- [\#12952](https://github.com/AliceO2Group/AliceO2/pull/12952) 2024-04-11: ITSMFT: check on strobe length for STFDecoder by [@IsakovAD](https://github.com/IsakovAD)
	- [\#12953](https://github.com/AliceO2Group/AliceO2/pull/12953) 2024-03-29: [EMCAL-741] Fix number of LEDMON channels in pedestal extraction by [@mfasDa](https://github.com/mfasDa)
	- [\#12955](https://github.com/AliceO2Group/AliceO2/pull/12955) 2024-03-28: ITS GPU: Remove hip_runtime.h include from headers, include cuda/hip runtime in source files by [@davidrohr](https://github.com/davidrohr)
	- [\#12957](https://github.com/AliceO2Group/AliceO2/pull/12957) 2024-03-29: GPU: Make HIP RTC fully work + some other fixes / improvements by [@davidrohr](https://github.com/davidrohr)
	- [\#12958](https://github.com/AliceO2Group/AliceO2/pull/12958) 2024-04-03: [EMCAL-1116] Add maximum value for pedestal calib by [@jokonig](https://github.com/jokonig)
	- [\#12959](https://github.com/AliceO2Group/AliceO2/pull/12959) 2024-04-02: [EMCAL-752] Fix number of LEDMON channel in Pedestal object by [@jokonig](https://github.com/jokonig)
	- [\#12961](https://github.com/AliceO2Group/AliceO2/pull/12961) 2024-03-29: ctpdev : fatal changed to error by [@lietava](https://github.com/lietava)
	- [\#12963](https://github.com/AliceO2Group/AliceO2/pull/12963) 2024-04-01: onnxruntime upstream uses onnxruntime::onnxruntime: Adhere to that and remain compatible with our custom onnxruntime build by [@davidrohr](https://github.com/davidrohr)
	- [\#12964](https://github.com/AliceO2Group/AliceO2/pull/12964) 2024-04-02: Some fixes for onnxruntime in TRD, but disabling it since still broken and untested by [@davidrohr](https://github.com/davidrohr)
	- [\#12966](https://github.com/AliceO2Group/AliceO2/pull/12966) 2024-04-01: GPU: More fixes for the HIP CMake code and for GCC13 by [@davidrohr](https://github.com/davidrohr)
	- [\#12967](https://github.com/AliceO2Group/AliceO2/pull/12967) 2024-04-03: ONNXRuntime: some fixes to use onnxruntime >= 1.16 by [@davidrohr](https://github.com/davidrohr)
	- [\#12968](https://github.com/AliceO2Group/AliceO2/pull/12968) 2024-04-01: Fix in the RCT updater deployment by [@shahor02](https://github.com/shahor02)
	- [\#12969](https://github.com/AliceO2Group/AliceO2/pull/12969) 2024-04-02: Mute stray debug log in o2-raw-tf-reader by [@shahor02](https://github.com/shahor02)
	- [\#12970](https://github.com/AliceO2Group/AliceO2/pull/12970) 2024-04-06: TPC: Use qmax/time contributions to cluster error and occupancy estimators - not yet final, don't merge by [@davidrohr](https://github.com/davidrohr)
	- [\#12971](https://github.com/AliceO2Group/AliceO2/pull/12971) 2024-04-03: [EMCAL-1116] Add possibility to push pedestals to DCS ccdb by [@jokonig](https://github.com/jokonig)
	- [\#12972](https://github.com/AliceO2Group/AliceO2/pull/12972) 2024-04-03: ITS: Factorise whole tracking behind a single interface by [@mconcas](https://github.com/mconcas)
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
	- [\#13016](https://github.com/AliceO2Group/AliceO2/pull/13016) 2024-04-12: TOF matching debug mode improvements by [@noferini](https://github.com/noferini)
	- [\#13019](https://github.com/AliceO2Group/AliceO2/pull/13019) 2024-04-12: Fix RCTUpdater warning message by [@martenole](https://github.com/martenole)
	- [\#13022](https://github.com/AliceO2Group/AliceO2/pull/13022) 2024-04-15: Do not store failed laser calib, ignore in VDriftHelper by [@shahor02](https://github.com/shahor02)
	- [\#13023](https://github.com/AliceO2Group/AliceO2/pull/13023) 2024-04-13: Use detectror-specific AlpideParam for ROF-rate check by [@shahor02](https://github.com/shahor02)
	- [\#13024](https://github.com/AliceO2Group/AliceO2/pull/13024) 2024-04-14: Skip empty ROFs only with no-empty-rof option in digi2raw by [@shahor02](https://github.com/shahor02)
	- [\#13025](https://github.com/AliceO2Group/AliceO2/pull/13025) 2024-04-15: macro to dump volumes ideal and real origins in lab frame by [@shahor02](https://github.com/shahor02)
	- [\#13026](https://github.com/AliceO2Group/AliceO2/pull/13026) 2024-04-15: Add debug output to TRD gain calibration by [@martenole](https://github.com/martenole)
	- [\#13027](https://github.com/AliceO2Group/AliceO2/pull/13027) 2024-04-15: [EMCAL-710] Fix namespace in stream operator by [@mfasDa](https://github.com/mfasDa)
	- [\#13033](https://github.com/AliceO2Group/AliceO2/pull/13033) 2024-04-16: Fixe TPC clusters extraction for millepede, decrease verbosity of RootTreeReader by [@shahor02](https://github.com/shahor02)
	- [\#13035](https://github.com/AliceO2Group/AliceO2/pull/13035) 2024-04-17: Option to manage ROF length reporting by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Framework
	- [\#12939](https://github.com/AliceO2Group/AliceO2/pull/12939) 2024-03-27: DPL: Delay "Maximum number of TF in flight reached" alarm by 15 seconds in online mode by [@davidrohr](https://github.com/davidrohr)
	- [\#12942](https://github.com/AliceO2Group/AliceO2/pull/12942) 2024-03-27: DPL Analysis: fix off-by-one when looking up filter info by [@aalkin](https://github.com/aalkin)
	- [\#12946](https://github.com/AliceO2Group/AliceO2/pull/12946) 2024-03-28: DPL Rate Limiter: Fix typo by [@davidrohr](https://github.com/davidrohr)
	- [\#12947](https://github.com/AliceO2Group/AliceO2/pull/12947) 2024-03-28: DPL: replace LOG with Signposts by [@ktf](https://github.com/ktf)
	- [\#12956](https://github.com/AliceO2Group/AliceO2/pull/12956) 2024-03-28: DPL: fix spurios error message and wrong update. by [@ktf](https://github.com/ktf)
	- [\#12977](https://github.com/AliceO2Group/AliceO2/pull/12977) 2024-04-03: DPL: Improve warning message by [@davidrohr](https://github.com/davidrohr)
	- [\#12990](https://github.com/AliceO2Group/AliceO2/pull/12990) 2024-04-08: Add missing energy column in StoredTracksIU by [@vkucera](https://github.com/vkucera)
	- [\#12991](https://github.com/AliceO2Group/AliceO2/pull/12991) 2024-04-11: Add momentum vector in track tables by [@vkucera](https://github.com/vkucera)
	- [\#12993](https://github.com/AliceO2Group/AliceO2/pull/12993) 2024-04-06: reserve bit of mc particle flag for OOB pileup tagging by [@maciacco](https://github.com/maciacco)
	- [\#13006](https://github.com/AliceO2Group/AliceO2/pull/13006) 2024-04-10: DPL Analysis: add ability to have ConfigurableGroup produce prefixed options by [@aalkin](https://github.com/aalkin)
	- [\#13007](https://github.com/AliceO2Group/AliceO2/pull/13007) 2024-04-11: Add comment to labelledArray types by [@jgrosseo](https://github.com/jgrosseo)
	- [\#13031](https://github.com/AliceO2Group/AliceO2/pull/13031) 2024-04-16: DPL: Fix orderedCompletionPolicy getting stuck when oldestPossibleTimeslice message jumps by > 1 at once, and any but the last TF in the jump range is missing by [@davidrohr](https://github.com/davidrohr)
	- [\#13033](https://github.com/AliceO2Group/AliceO2/pull/13033) 2024-04-16: Fixe TPC clusters extraction for millepede, decrease verbosity of RootTreeReader by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Generators
	- [\#12954](https://github.com/AliceO2Group/AliceO2/pull/12954) 2024-04-03: More consistent MCHeader forwarding when using GeneratorFromFile by [@sawenzel](https://github.com/sawenzel)
	- [\#12980](https://github.com/AliceO2Group/AliceO2/pull/12980) 2024-04-05: Providing an box generator natively for ALICEO2. by [@sawenzel](https://github.com/sawenzel)
## Recent developments in O2 - Steer
	- [\#13000](https://github.com/AliceO2Group/AliceO2/pull/13000) 2024-04-09: Digitization: Fix timestamps for querying CCDB when using BasicCCDBMa… by [@sawenzel](https://github.com/sawenzel)
## Recent developments in O2 - Utilities
	- [\#12987](https://github.com/AliceO2Group/AliceO2/pull/12987) 2024-04-05: EPN Stderr monitor: Prepend messages from syslog with [GLOBAL SYSLOG] by [@davidrohr](https://github.com/davidrohr)
	- [\#12998](https://github.com/AliceO2Group/AliceO2/pull/12998) 2024-04-11: QC-1143 Merge objects before publishing at End Of Stream by [@knopers8](https://github.com/knopers8)
