## Recent AliPhysics releases
## Recent O2 releases
## Recent developments in O2 - Algorithm
- [\#13704](https://github.com/AliceO2Group/AliceO2/pull/13704) 2024-11-16: GPU OpenCL: Fixes and workaround for undefined symbols that make the clang SPIRV code actually link correctly by [@davidrohr](https://github.com/davidrohr)
## Recent developments in O2 - Analysis
- [\#13617](https://github.com/AliceO2Group/AliceO2/pull/13617) 2024-11-20: Add number of TPC clusters used for PID to AO2D by [@mpuccio](https://github.com/mpuccio)
- [\#13679](https://github.com/AliceO2Group/AliceO2/pull/13679) 2024-11-19: DPL Analysis: Preliminary changes for Table rewrite by [@aalkin](https://github.com/aalkin)
## Recent developments in O2 - Common
- [\#13642](https://github.com/AliceO2Group/AliceO2/pull/13642) 2024-10-31: Add new particle: Hyper Helium4Sigma by [@wang-yuanzhe](https://github.com/wang-yuanzhe)
- [\#13695](https://github.com/AliceO2Group/AliceO2/pull/13695) 2024-11-22: register available_managed_shm metric only for readout-proxy by [@ehellbar](https://github.com/ehellbar)
- [\#13704](https://github.com/AliceO2Group/AliceO2/pull/13704) 2024-11-16: GPU OpenCL: Fixes and workaround for undefined symbols that make the clang SPIRV code actually link correctly by [@davidrohr](https://github.com/davidrohr)
- [\#13705](https://github.com/AliceO2Group/AliceO2/pull/13705) 2024-11-18: GPU: Several unrelated fixes by [@davidrohr](https://github.com/davidrohr)
- [\#13709](https://github.com/AliceO2Group/AliceO2/pull/13709) 2024-11-22: ORT library in the O2 framework by [@ChSonnabend](https://github.com/ChSonnabend)
- [\#13712](https://github.com/AliceO2Group/AliceO2/pull/13712) 2024-11-19: Don't prevent loading ROOT headers if we use DEBUG_STREAMERS, might break GPU build by [@davidrohr](https://github.com/davidrohr)
## Recent developments in O2 - DataFormats
- [\#13621](https://github.com/AliceO2Group/AliceO2/pull/13621) 2024-11-05: [TOF] update matcher by [@njacazio](https://github.com/njacazio)
- [\#13642](https://github.com/AliceO2Group/AliceO2/pull/13642) 2024-10-31: Add new particle: Hyper Helium4Sigma by [@wang-yuanzhe](https://github.com/wang-yuanzhe)
- [\#13688](https://github.com/AliceO2Group/AliceO2/pull/13688) 2024-11-15: ParticleDatabase: Added particle a2(1320) in the O2Database accroding to latest PDG by [@sawankumawat](https://github.com/sawankumawat)
- [\#13693](https://github.com/AliceO2Group/AliceO2/pull/13693) 2024-11-15: TRD add less than operator to Tracklet64 to permit std::merge usage by [@bazinski](https://github.com/bazinski)
- [\#13697](https://github.com/AliceO2Group/AliceO2/pull/13697) 2024-11-15: Orbit-early treatment in CollisionContext tool by [@sawenzel](https://github.com/sawenzel)
- [\#13703](https://github.com/AliceO2Group/AliceO2/pull/13703) 2024-11-16: CollisionContextTool: different QED printing by [@sawenzel](https://github.com/sawenzel)
- [\#13714](https://github.com/AliceO2Group/AliceO2/pull/13714) 2024-11-19: GPU: Merge GPUDataTypes and GPUDataTypeHeaders in one library by [@davidrohr](https://github.com/davidrohr)
- [\#13719](https://github.com/AliceO2Group/AliceO2/pull/13719) 2024-11-23: Object to provide TB to cut due to the Altro sync. procedure by [@shahor02](https://github.com/shahor02)
- [\#13726](https://github.com/AliceO2Group/AliceO2/pull/13726) 2024-11-24: fix typo: remove stray . in the int value by [@shahor02](https://github.com/shahor02)
- [\#13727](https://github.com/AliceO2Group/AliceO2/pull/13727) 2024-11-24: Fix another typo in AltroSyncSignal::timebin default value by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Detectors
- [\#13568](https://github.com/AliceO2Group/AliceO2/pull/13568) 2024-11-25: ITS: TrackExtensionStudy by [@f3sch](https://github.com/f3sch)
- [\#13617](https://github.com/AliceO2Group/AliceO2/pull/13617) 2024-11-20: Add number of TPC clusters used for PID to AO2D by [@mpuccio](https://github.com/mpuccio)
- [\#13621](https://github.com/AliceO2Group/AliceO2/pull/13621) 2024-11-05: [TOF] update matcher by [@njacazio](https://github.com/njacazio)
- [\#13687](https://github.com/AliceO2Group/AliceO2/pull/13687) 2024-11-13: Protect LT-int.calculation in TRD refit from bad TPC correction by [@shahor02](https://github.com/shahor02)
- [\#13691](https://github.com/AliceO2Group/AliceO2/pull/13691) 2024-11-15: TPC: add check for empty data when receiving IDCs by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [\#13693](https://github.com/AliceO2Group/AliceO2/pull/13693) 2024-11-15: TRD add less than operator to Tracklet64 to permit std::merge usage by [@bazinski](https://github.com/bazinski)
- [\#13696](https://github.com/AliceO2Group/AliceO2/pull/13696) 2024-11-18: TPC GPU Decoding code duplication removal by [@cima22](https://github.com/cima22)
- [\#13700](https://github.com/AliceO2Group/AliceO2/pull/13700) 2024-11-20: TPC: adding MC ccdb objects for simulation and reconstruction by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [\#13701](https://github.com/AliceO2Group/AliceO2/pull/13701) 2024-11-15: HBFUtils: Optional throw on failed parsing of opt by [@f3sch](https://github.com/f3sch)
- [\#13702](https://github.com/AliceO2Group/AliceO2/pull/13702) 2024-11-15: Limit TFs extraxted from CTF file with --max-tf-per-file CTF-reader N by [@shahor02](https://github.com/shahor02)
- [\#13706](https://github.com/AliceO2Group/AliceO2/pull/13706) 2024-11-18: Optional ordering of objects in CCDBPopulator by [@shahor02](https://github.com/shahor02)
- [\#13707](https://github.com/AliceO2Group/AliceO2/pull/13707) 2024-11-18: extend opt. max-tf-per-file to raw-tf reader, move it to device by [@shahor02](https://github.com/shahor02)
- [\#13710](https://github.com/AliceO2Group/AliceO2/pull/13710) 2024-11-19: TPC: Exclude electrons created between vessels and field strips by [@wiechula](https://github.com/wiechula)
- [\#13714](https://github.com/AliceO2Group/AliceO2/pull/13714) 2024-11-19: GPU: Merge GPUDataTypes and GPUDataTypeHeaders in one library by [@davidrohr](https://github.com/davidrohr)
- [\#13716](https://github.com/AliceO2Group/AliceO2/pull/13716) 2024-11-20: Protect its/mft decoder agains decreasing row in the same column by [@shahor02](https://github.com/shahor02)
- [\#13719](https://github.com/AliceO2Group/AliceO2/pull/13719) 2024-11-23: Object to provide TB to cut due to the Altro sync. procedure by [@shahor02](https://github.com/shahor02)
- [\#13724](https://github.com/AliceO2Group/AliceO2/pull/13724) 2024-11-22: Add TPC sh.clusters info to study output by [@shahor02](https://github.com/shahor02)
- [\#13726](https://github.com/AliceO2Group/AliceO2/pull/13726) 2024-11-24: fix typo: remove stray . in the int value by [@shahor02](https://github.com/shahor02)
- [\#13727](https://github.com/AliceO2Group/AliceO2/pull/13727) 2024-11-24: Fix another typo in AltroSyncSignal::timebin default value by [@shahor02](https://github.com/shahor02)
- [\#13729](https://github.com/AliceO2Group/AliceO2/pull/13729) 2024-11-25: Add AltroSyncSignal to TPC CDBTypeMap by [@shahor02](https://github.com/shahor02)
## Recent developments in O2 - Examples
- [\#13699](https://github.com/AliceO2Group/AliceO2/pull/13699) 2024-11-20: Implementation of hybrid generator  by [@jackal1-66](https://github.com/jackal1-66)
## Recent developments in O2 - Framework
- [\#13617](https://github.com/AliceO2Group/AliceO2/pull/13617) 2024-11-20: Add number of TPC clusters used for PID to AO2D by [@mpuccio](https://github.com/mpuccio)
- [\#13679](https://github.com/AliceO2Group/AliceO2/pull/13679) 2024-11-19: DPL Analysis: Preliminary changes for Table rewrite by [@aalkin](https://github.com/aalkin)
- [\#13683](https://github.com/AliceO2Group/AliceO2/pull/13683) 2024-11-19: Proper display / filtering of ROOT log messages from stderr in terminal output and InfoLogger by [@ehellbar](https://github.com/ehellbar)
- [\#13694](https://github.com/AliceO2Group/AliceO2/pull/13694) 2024-11-15: DPL: Use AnalysisContext also in the case of amended topologies by [@ktf](https://github.com/ktf)
- [\#13695](https://github.com/AliceO2Group/AliceO2/pull/13695) 2024-11-22: register available_managed_shm metric only for readout-proxy by [@ehellbar](https://github.com/ehellbar)
- [\#13708](https://github.com/AliceO2Group/AliceO2/pull/13708) 2024-11-19: DPL: initialise the initial chunk length by [@ktf](https://github.com/ktf)
- [\#13713](https://github.com/AliceO2Group/AliceO2/pull/13713) 2024-11-19: DPL: fix adjustment of spawnerInputs by [@ktf](https://github.com/ktf)
- [\#13717](https://github.com/AliceO2Group/AliceO2/pull/13717) 2024-11-20: Fix a few --compression options by [@ktf](https://github.com/ktf)
- [\#13718](https://github.com/AliceO2Group/AliceO2/pull/13718) 2024-11-21: DPL: write support for TTree using arrow::Dataset API by [@ktf](https://github.com/ktf)
- [\#13725](https://github.com/AliceO2Group/AliceO2/pull/13725) 2024-11-24: DPL: improve arrow::Dataset integration by [@ktf](https://github.com/ktf)
## Recent developments in O2 - Generators
- [\#13699](https://github.com/AliceO2Group/AliceO2/pull/13699) 2024-11-20: Implementation of hybrid generator  by [@jackal1-66](https://github.com/jackal1-66)
- [\#13721](https://github.com/AliceO2Group/AliceO2/pull/13721) 2024-11-22: Fix for failing dataflow build by [@jackal1-66](https://github.com/jackal1-66)
- [\#13722](https://github.com/AliceO2Group/AliceO2/pull/13722) 2024-11-21: Fix GeneratorPythia8 construction by [@sawenzel](https://github.com/sawenzel)
## Recent developments in O2 - Steer
- [\#13642](https://github.com/AliceO2Group/AliceO2/pull/13642) 2024-10-31: Add new particle: Hyper Helium4Sigma by [@wang-yuanzhe](https://github.com/wang-yuanzhe)
- [\#13688](https://github.com/AliceO2Group/AliceO2/pull/13688) 2024-11-15: ParticleDatabase: Added particle a2(1320) in the O2Database accroding to latest PDG by [@sawankumawat](https://github.com/sawankumawat)
- [\#13697](https://github.com/AliceO2Group/AliceO2/pull/13697) 2024-11-15: Orbit-early treatment in CollisionContext tool by [@sawenzel](https://github.com/sawenzel)
- [\#13700](https://github.com/AliceO2Group/AliceO2/pull/13700) 2024-11-20: TPC: adding MC ccdb objects for simulation and reconstruction by [@matthias-kleiner](https://github.com/matthias-kleiner)
- [\#13703](https://github.com/AliceO2Group/AliceO2/pull/13703) 2024-11-16: CollisionContextTool: different QED printing by [@sawenzel](https://github.com/sawenzel)
## Recent developments in O2 - Utilities
- [\#13683](https://github.com/AliceO2Group/AliceO2/pull/13683) 2024-11-19: Proper display / filtering of ROOT log messages from stderr in terminal output and InfoLogger by [@ehellbar](https://github.com/ehellbar)
