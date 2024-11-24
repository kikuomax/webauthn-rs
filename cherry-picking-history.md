# Cherry Picking History

## 0.4.8 → 0.5.0

From newer to older commits.
The latest commit 6f4688dcab445debe9bbf27b61759f7071518d8e is tagged as `cherry-pick-head-v0.5.0-wo-openssl.0`.

- [x] 6f4688dcab445debe9bbf27b61759f7071518d8e    **CONFLICT** chasing clippy fixes (#440)
- [x] 826dc1b16a6db4b709160c89672851e843ccf6c4    Update ssh keys to latest version (#439)
- [x] 380c8cd146f6e068c3925c6e90ebe0d35b3fa26b    Fixed actix tutorial (#438)
- [x] 628599aa47b5c120e7f29cce8c526af532fba9ce    **CONFLICT** Things that you only find during a release (#437)
- [x] 7008a387ff1b58c5fbf7f9afb2bceb03967106d4    **CONFLICT** Release 0.5.0 (#436)
- [x] 3b80be72dcbb5f4eaece0b14a6c58b5570d14a7d    Add support for Webauthn L3 options (#435)
- [x] e7d7cef75139f715706befe524c23a664632e1f9    **CONFLICT** Private base64 field (#433)
- [x] e7cf209020c6a4618764841729d83608fb88597d    Make rk flag public (#434)
- [x] c36419cdb6db7c34cf1f6d29e81a3cf28531c1ce    Add RsassaPkcsv15Sha1Raw (#432)
- [x] 297a41899374f8b373559b5c9d998e4f3c98678f    YubiKey 5 vendor commands (#415)
- [x] 6ff6ab20aa513dcb9eaf904f3aeeb9dd0a8dc303    Add myself per Firstyear. (#430)
- [x] 869a0b98a7e7d169acd994b786f72ff3f12f9690    Replace `println!` from library functions with configurable logging (#424)
- [x] 1386f66016ed8c4b92a91e0e8f2f2cfc629daa31    Fix spelling, etc. (#429)
- [x] cb38125906f281a33c1b609613eb59b130023c5e    Lock bumpalo to less than 3.15.0 (#427) (#428)
- [x] 23cf17c8ff0eae882374aeda193f111390efbfd8    webauthn-rs command line (#414)
- [x] a506d89c7c73dbd05ae720bfdc739de7bb42b797    **CONFLICT** Fix building on nightly, broken doc links (#426)
- [x] 9f1d995b68c86512530cf10709b3f79e5863902d    Remove outdated documentation about vendored OpenSSL version. (#416)
- [x] f6451ded1ab8dfc4622b0a1562cb1d43cb453322    Won't work but unnecessary, as OpenSSL is not used. ~~Add explicit OpenSSL version checks to attestation-ca and webauthn-rs-core (#418)~~
- [x] edb8f57972629b2a89ed0cf584c99a02201fe221    pin clap to 4.4.18 (last version supporting rustc 1.70.0) (#419)
- [x] d278c56adfa39a0723c79bdcd461644194bc5138    Add fake credential generator interfaces (#410)
  - Replaces `openssl`
- [x] fe7a717a510ae509ee78861cae24236fe1a3a3b9    **CONFLICT** clips (#409)
- [x] f4c363e6ee4e72928a079f7dec266f32d3bedb3a    **CONFLICT** Add EDDSA support (#408)
  - Introduction of ed25519-dalek, and ed448-verifier.
- [x] f40f95f06c564913e3939501b1e62b16e8de150e    **CONFLICT** 20231215 264 cleanup (#400)
- [x] 142e8d77335cfcd947ecc8610d45a3abfe4cd823    One line fix - missing cfg (#398)
- [x] 5f4db4172f8e22aedc68c282d177e98db2b1892f    **CONFLICT** **WONT COMPILE** 20231129 attestation finalisation (#396)
- [x] ebd6ff03532fdc72c553bcd8d10b5dad334dcfc3    394 - fixing tutorials (#395)
- [x] 7837bb7195c3a10426d428f09b2f3f63bc11c7c0    Fix some clippy warnings (#393)
- [x] 6518c6966a6cd2a17a97165498a3229000ef4210    **CONFLICT** 20231025 attestation ca devices (#390)
- [x] fd5648dde99de05f7adf63b24bbecbd641f196f8    WIP: fixing documentation in CI (#392)
- [x] a0cb1e8845474a66605fe30cf75e65ebea793c2c    Port from axum-sessions to tower-sessions (#389)
- [x] b6d1dc410b7b2387157f2e089391cff7104aa05b    20231111 compat tester improvements (#384)
- [x] c70b1bbcc877f1d392d3dcdfce60e0d719eac979    Feature/configurable timeout (#385)
- [x] bd3c90b4f887d90ad293a2f9058984c5db43a0b0    20231027 378 optional conditional UI (#379)
- [x] 0ff6b525d428b5155243a37e1672c1e3205d41e8    Implement some SoloKeys2/Trussed vendor commands (#377)
- [x] c32c83beb702a1e11c68dd8a1494e00970b8c6b7    Ignore Trussed CCID devices, document ignored_reader better, and improve its tests (#376)
- [x] eecc9fe640152f37eec671a3fa60241ed9032d83    Fix incorrect ATR Y(n) byte parsing (#375)
- [x] b16b267568080e944b08998153a4f1e81bda2584    Add feature for android specific work arounds (#371)
- [x] f0c735fdff6c5fce300b968a9514920d74e82799    Update tests to demonstrate broken eddsa behaviour in solokey 2 (#374)
- [x] 377bdc69ac48d65b784a393987549fa78d93ba30    Show "processing" status for BTLE and USB keys (#373)
- [x] 2218d2055c0c900ef57b398423eee5e8d5521f4c    Expose sshkeys (#370)
- [x] 1d0ba2f5cc80d52dd12b59a0571faddbbb37d957    test android and ios getinforesponse (#369)
- [x] 193926a55e0a2767e2db6a21b49f908dfcd3d711    Accept unknown transports in deserialisation (#367)
- [x] 1aeb3783d43b87f9a462e64abe6019a81ee0566b    Add subjectAltName to webauthn-rs-demo example (#366)
- [x] 35cc2c382011c8f9589937f3cc08204e5fff23bf    win10: fix incorrect user entity encoding (#363)
- [x] 18a3ddf5dc025301beec2000470cc2e211577558    Switch webauthn-rs-demo to OpenSSL. (#360)
- [x] 7dc3eed9e74971ea6e820f0025987b76ea4bcab7    Fix axum example for credential creation (#361)
- [x] 13dc8b65af915c298f79a8f8195df3c6a4bd74cf    fido-key-manager: disable tests (#358)
- [x] c20e83f4aae635682b8b2f2fa9fca8534fe32d35    Add "HumanBinaryData" as an alternative to "Base64UrlSafeData" (#354)
- [x] 1f85ef40a8754fb0c0c3cbf5815c7658dc4e120a    fix redundant clone (#355)
- [x] 840a6f5cc7f65bd3c585ab00293addf76f70d973    SessionLayer::with_secure(false) (#336)
- [x] 36a6c45f63f6d4189d034455497aa7b58c459a28    **CONFLICT** 20230206 238 fido mds and quirks (#348)
- [x] 0b51d0cde10f1baf37d264d71fb994646d6173a0    Bump MSRV to v1.70.0 (fixes #346) (#349)
- [x] 908b2d9cf8a8fb8e1f600ee67d5b0dd0f47b3f20    OpenSSL dependency update to support v3.x (#340)
- [x] f226b91e58a4c0437ab2870fb49ab33d3414a6c2    Update soft tokens to allow uv in tests (#343)
- [x] 26cff193ce4fa617c643f34adb152a03ddc6fa61    Add Clone derivation to Webauthn struct (#338)
- [x] a7cda7ac78e251e898a4c4f2c4969bb61e99ac98    **CONFLICT** migrating to serde_cbor_2 (#342)
- [x] d4b418487ff7726464549b43bf850509694c3e74    Fix missing base64 conversion of response.userHandle (#335)
- [x] 8016462fcb3fea471862114bfcfcb3ac7e52e371    Fix incorrect feature flag definition (#333)
- [x] c01900df8b7a332a092c1c2aa4a65eaf9c9b159a    Add design philosophy doc (#285)
- [x] 5a49ab5a78dba1e7cf2c6f1b18d3647895445cb0    Event-based Transport/Token API / USB HID rewrite (#324)
- [x] a7bb46177c23a9afe078658ffacf34cc8aaa30fe    migrate from winres to embed-resource (#329)
- [x] 1d5b2f0cbee470dd70796c464892cd28dc8dfad0    add OpenSSL notes and tidy build file (#328)
- [x] 9f9f3acad1e99006cd28be5fa475191c50e05802    Add handlers for isConditionalMediation and isExternalCTAP2 (#327)
- [x] 3e1de50fc989c83e11337752963da6676eeca3ba    Rename passwordless and device key to attested passkey and attested residentkey (#326)
- [x] a17e8c56cbc135a8ffa3ab38d4df990a6e8a73c8    **CONFLICT** Add ssh key attestation (#249)
- [x] 063ec0eb49fe94e6c1e94205f87cb87a8d5f4636    Update metadata for cable-tunnel-server to allow publishing (#325)
- [x] 2db3a1a873c8d316e4782c80d8dc4f5bd6d86233    Pass the username parameter in the request body, rather than URL (#322)
- [x] d14fadfd19cc1b347176db29f7f2e2afb67d4f4c    Implement credential management (#320)
- [x] 82562f545b8fe8ab93efffd61147ce11bf5d37df    handle unavailability of SCardSvr gracefully (on Windows) (#321)
- [x] fbbc3051e88a78448126255c89ea3b84f3eba5ec    base16 encode tracing output (#319)
- [x] 11ca5c638b86258d6a1c58c5d4aa741888f11db1    Push functionality into more features (#317)
- [x] 0c11505ccf6e91c9846d53fafdab208fa302347b    Automatically cancel jobs in CI when a revision is obsolete. (#316)
- [x] c7ab114f2fa5dc32a63f560587381515e3a16e46    Migrate to clap 4.2, run binaries/examples with --help in CI, and clean up examples (#315)
- [x] dcb6ebd5af361db77d171b4fab6d146b13655e09    caBLE tunnel server (#291)
- [x] 93089ea78d75ab18d438811973a52c645df65fc8    implement bluetooth (#272)
- [x] 833f694925c5bedfbd188a272a77775dfedc92d9    Move key_manager to fido-key-manager, and make it run standalone (v2). (#311)
- [x] 5fc0ebe9a52a3b7b5f25784cc5c89c8b5412a715    workaround https://github.com/rust-lang/rust-clippy/issues/10421 (#312)
- [x] 30954dbf7cb9cf6a46428ffd0e34f5a413ec3a46    CI performance improvements (#308)
- [x] 406f21d3db716427ee3cd2dc0affb9eb6679fa34    API changes needed for BTLE work (#274)
- [x] c673a351e6aac19af1d82f2712d0b33b3a2f8705    20230416 passkey define (#303)
- [x] 410a9aa99e83f2e8dc210277a9ac3b13ff32532f    add CLI tool to derive caBLE tunnel server domain (#305)
- [x] f2cf35470955583173147d8515ecc3619b3d5bab    move common dependencies into workspace (#304)
  - `webauthn-rs-core`:
    - `compact_jwt` → `compact_jwt_wo_openssl`
- [x] 8619cfd367df6a6572c56104deba06e52bae74fb    Allow overriding tunnel server protocol/domain for caBLE (#295)
- [x] d4d151cc5794d3bb0f9451d9ed8198c35e2be3f8    Add remaining FIDO 2.1 GetInfoResponse fields (#302)
- [x] 5534dd11a74c16f25dd7c9c5b625acd40de14cea    Resolve potential client side UV bypass in passkeys (#284)
- [x] 844e5d6c3edde31fb0296f7f975a4461b4478ec6    Switch to dtolnay/rust-toolchain, bump MSRV to 1.66.0 (#301)
- [x] b187b414e1c78ccf694d41e5acfe564b5b3dc6ef    Fix deviceplug force-push of dev branch (#300)
- [x] dede877e893ff7728afe45dcc1fd2aa619642885    Add getter to read public key from passkey credential (#299)
- [x] 0000543399501653191f6f178cc15decdb581848    Add residentKey to AuthenticatorSelectionCriteria (#292)
- [x] 9c54c0757010bf26ba32a96bcbed2da8e08be245    clippy: fix multiple issues (#293)
- [x] e9ebff3123263073c3668228fa088f007f3fa555    making a basic test for a webauthn object from a chrome extension (#289)
- [x] aded3a8da5afabd395e0ba7ad8f7b5742904cb69    Fix PIN Protocol 2 implementation, and add a test (#269). (#286)
- [x] 8cbe1747674e6ca7a025a44df77f7fcb828964db    Fix #262; null pointer dereference for GetAssertion on Windows 10 (#287)
- [x] 5356504a1bf46f6c614c153e66aba8048e95ff2d    20230220 opportunistic cred protect (#282)
- [x] 6ec69a850f02be5153e581791a34d705fede54f7    fmt (#283)
- [x] 09ff14cec763863cbe2122a48fa72e36efc24e09    Update base64urlsafedata (#280)
- [x] c6a5a334b19af9c981479a558e30fc8f0cfbe695    Update Base64 & MSRV to 1.57.0 (#279)
- [x] 31f19d22f80793454356d05103e172f9c6a8de41    display rather than debug (#273)
- [x] 2a8319dcc9bb2fe43625128c84e889f1eebb03ac    Add Micolous to codeowners (#275)
- [x] eba013549b07bf9304bcf263fcc6ca69afb5871f    Make aaguid a Uuid (#270)
- [x] c2966642737628f5786587fc2e04c612f01e124a    Add support for CTAP 2.1-PRE biometric enrollment and move config commands to CTAP 2.1 (#261)
- [x] 8c9585dc31fe3a74f9a726a8c37e6fc9c7de7b9e    Fix up user verification with CtapAuthenticator, and minor fixing (#267)
- [x] e460f74257dea71aaab66db7c0c35c5856612522    **CONFLICT** Document feature flags (#266)
- [x] 5dfb0876745297ee3265cfdf57d5a1a7a5f8add3    fix rustdoc syntax in webauthn_rs_core (#265)
- [x] 19aa0e46fd7d413a9be7292552b6f7f365ce04aa    Add basic support for caBLE authenticators / initiators (#232)
- [x] 38b61c036baccbacf0cdfbfc6d87345341124f72    Add a HTML/Javascript front-end example (#258)
- [x] 8b88f9b2e6c016c8218235466006c449b203a103    Fail builds when running on old/broken versions of OpenSSL that stop the library from working (#256)
- [x] 220a442a3134f92c4798f8014a8c8afb869f7629    **CONFLICT** require at least openssl 0.10.41 for set_affine_coordinates_gfp (#257)
- [x] f99ed1fd31a4ff87c60f563d4519b6101856a8f4    Add actix_web tutorial (#254)
- [x] 04c3bf346ba6542848f23c37f05a11c5b3d3ba20    **CONFLICT** Common API changes needed to (later) add caBLE support. (#251)
- [x] a71a5d14e5d2ac1151c749b771d2bc3e75fdde9d    Fixed typo (#253)
- [x] c76118185756f2d4aa8262b250601b1a01d12c52    **CONFLICT** 245 disable rs1 (#250)
- [x] 696a7b003891690452d112ba8698055814dd5987    Add improved query support (#244)
- [x] c4bd6819ecfe7bd526acf14555932637121b468d    **EMPTY?** Clippy calming (#241)
- [x] b993536237dbc45728d248585d56f7f9d6c71693    fixed link in readme (#247)
- [x] 460d4a60fa24869b654149e114e92970a6d3628e    don't cancel all ci runs when one fails, and fix lints (#246)
- [x] e2d11724a2b7e8f04396dcfce9242f7162021056    Transport/Token AuthenticatorBackend for CTAP 2.0/2.1 (#215)
- [x] d06bafbf9cafb09011191cddbfec61eaad0eaaad    Doc and CI improvements (#242)
- [x] 03f15bc037cafa503b1798e8ab81ea3d448dff83    Improve some details of the listing tool (#237)
- [x] 75e1752233325d56773e5f31906937ca1c376a21    Update project support guidelines (#233)
- [x] e1b7817f5194d5ade2b00a30b46bf0568b43ee33    Fix up feature flag (#239)
- [x] f30193c95fb309dd230d446ac643b5d63880d783    Improve condui wasm (#236)
- [x] e6912eda2f4afd1ef6dd68f7c17476f86eb3654e    **CONFLICT** Update docs, move to 5.0 dev, and change security key feature property (#235)
- [x] 72ce0030baf98647e2e29d5f30a3d6c9e066d1c2    **CONFLICT** 20221116 missing icon (#227)
- [x] 6b758bb5b5ca3b5be796a82ade74115998814e72    **CONFLICT** Common code changes from transport-auth (#215): (#225).
- [x] f7884b3515f266e95e450c77a3addd8673f21ca4    Improve OpenSSL error handling, and pull sha256 function into common area (#226)
- [x] 4d199c1274a2b5198e93998565b39deb701e6daa    Update base64urlsafe to 0.1.2 (#224)