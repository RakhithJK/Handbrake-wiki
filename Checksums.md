This page mirrors the checksums for official HandBrake downloads on https://handbrake.fr. Checksums should always match those listed on https://handbrake.fr/checksums.php. If there is a discrepancy, please make us aware by raising an [Issue](https://github.com/HandBrake/HandBrake/issues).

## Where to Download HandBrake

The only official download site for HandBrake is our main website: https://handbrake.fr/downloads.php 

We recommend you verify the hashes for any files you download match those listed here, *especially* if you choose to download from a third-party site.

## Validating checksums

The following instructions have been tested on macOS and Ubuntu Linux, and assume you have downloaded the files to the `Downloads` folder in your home directory.

Open a terminal (`/Applications/Utilities/Terminal.app` on macOS) and run the following commands:

```
cd ~/Downloads
shasum -a 1 HandBrake-* && shasum -a 256 HandBrake-*
```

The SHA1 for each file will be printed, followed by the SHA256 for each file.

**If the hashes for any files do not match those listed here and on our website, the files may be corrupt or tampered with. You should delete any files with non-matching hashes, then download from https://handbrake.fr/downloads.php and verify again.**

## Current Release

### Version (1.2.1)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.2.0-x86_64-Win_GUI.zip | 17.66 | b5e7f6f6bd708f703847c2d73d43036f32652658 | 1914a241d4aa35e3366ab590b5779b5cc556ba8218d3a27b0a131de3e5a41749 |
| HandBrake-1.2.1-source.tar.bz2 | 17.12 | dac584e5f887c281c29b32590cc23728b8a2317a | 00316eec7bb29b88b8dd11b14581c99c35fd7a315f5bc8cc7f1eb144b2fa783d |
| HandBrake-1.2.1-x86_64-Win_GUI.exe | 12.75 | 5862cad2e9485f5fe3869188c9325d6ae5403700 | 455754f5221cfa2553d357cdc6cd911987afa9c8178f4adc09cee720f02a403b |
| HandBrake-1.2.1-x86_64.flatpak | 22.82 | 04e5dd8a8caafe41ed999b8b2c9a9b1668148b6d | ffabc5b81b11619f5756c1f64c666d1fecddf12e430e5fecdbd54f1335b7e0b5 |
| HandBrake-1.2.1.dmg | 19.65 | 7409abc1af62054a7319656ab2563483d8c2f08d | 38ac310eaa7dda470d170093da3d68d111f042647d1a822b9818e83708c261fc |
| HandBrakeCLI-1.2.1-win-x86_64.zip | 16.4 | 3bdfc05549372240a4b94718413dc6dcc604f104 | 8fc4437573c5537004f714ee121d9f78c971c2d786f4cd99b3f58b9676032f38 |
| HandBrakeCLI-1.2.1-x86_64.flatpak | 9.05 | 4ccfad22ed693e272e5fa78dcaf028d454eaa210 | 8597cacd3950ff7650aa9ef08993d0914ee4398161d033967de533ece37469ad |
| HandBrakeCLI-1.2.1.dmg | 16.41 | a89460dc248f0e2e89f6c6dad8830e7ea119d488 | 38c02a45b3ac7956bab8cc9f4c5a296f19c05a98ccb927138928d536e1602501 |
| LibHB-1.2.1-win-x86_64.zip | 16.74 | 773327ac3cf95ae2c63646bbe162cce73afc2724 | 576b71ad27d310784285dc3426478edd8c5eecf89f3b1bc24975d7673392dd4b |

## Previous Releases

### Version (1.2.0)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.2.0-source.tar.bz2 | 17.04 | 1abdb80bbefab23bdad78d7081cc24e71926fb35 | 113b398a50147d48c8777e6ff2c4de6825af5f1079b3822e41bf0eacec9c940d |
| HandBrake-1.2.0-x86_64-Win_GUI.exe | 12.94 | 59fb9b4503dbcaa31fcc19b6a63b1871e53276a5 | 5bae36eeb01d3dd65bf00d9f0634376c89fc17fa05a04ff273ae8c22d1f25239 |
| HandBrake-1.2.0-x86_64-Win_GUI.zip | 18.2 | be347a991d9e603cb026d8019e8b255bc54c83ce | 0171b65d14bd6b30fc59b2f4f5604e7a3312ca1def34b6bb14112ecd40203a6c |
| HandBrake-1.2.0-x86_64.flatpak | 22.7 | 28996556ff84529e5e50745fb1e7be6d86042cbf | fd9e3cc2d849bbed281ea0d4914382eefe62550433ef0f83a633925d7ef201d3 |
| HandBrake-1.2.0.dmg | 19.65 | f6f325bc9f49d9759b69a75b4f7cdfb44a4e045b | 60b396be7953caee896c1abbe8dc96d851c6e0d7be5455eeef69c7073872c53f |
| HandBrakeCLI-1.2.0-win-x86_64.zip | 16.98 | 7c8ef6e746d193fa4bcdc1f114fa1d62fceb3f47 | bd12c0b5e6e0ef562e0123cae7de9c6988b1d17e7e8f90f48c88931d9dc4d5a9 |
| HandBrakeCLI-1.2.0-x86_64.flatpak | 9.04 | 50af44424c86cdc04016eab5b31d486927682043 | 2be4666782f3e7b81340c78c11480aa3703f9133c287daa70916d37fd045e058 |
| HandBrakeCLI-1.2.0.dmg | 16.4 | 0cf497be2c6404061e08d29107ca382239a155d0 | 5267f6c650c76c3aa97419600a56addbbcb172cbf7a426593a6b2952c92137b5 |
| LibHB-1.2.0-win-x86_64.zip | 17.32 | 776643bef52820db77fb48343d1443ce1bcf164e | b254152fc571e13512e6ec66ffd27626d075063d3d17a2e2e9005e712f845ba8 |


### Version (1.1.2)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.1.2-source.tar.bz2 | 14.58 | 423cabfc36cd53b47e273b44bed339d4466267fc | ba9a4a90a7657720f04e4ba0a2880ed055be3bd855e99c0c13af944c3904de2e |
| HandBrake-1.1.2-x86_64-Win_GUI.exe | 11.18 | a14cd428cd2b7168461c0607489a85f9375ed4c7 | f4cce05a18402d9dfa768529cabac2dd721b733cb0d631b940125d6a94bf1a0e |
| HandBrake-1.1.2-x86_64-Win_GUI.zip | 15.97 | 74750d82a65e6d7b68d3bae4bd7b12723cd30f4c | ded98899ee3a9bbf648040ee5064e70de9582c374cf3cb52c6fdbd6f2f67c5c2 |
| HandBrake-1.1.2-x86_64.flatpak | 18.15 | a7e77fa18e13ca37ab6d5408f224f7a3a577051b | 801f8ed6c5149bcf8619a169b6c612e8a5bd27aa4a8d05d4f62c7973aa3d3fcc |
| HandBrake-1.1.2.dmg | 16.29 | ee509ca285de0cb6aa5e9535f602e0972517ac3b | 181feb443687d84b15cc8da7cc43183fb1b88a62c8b4476cf77b948a6406b368 |
| HandBrakeCLI-1.1.2-win-x86_64.zip | 14.89 | 6b471a56a2c5c36a28f88a34f72871e29fa468c0 | 8b275a6584a3a2d01244d4c372bf002ed6a9fc86189dbc18ff7a3204851c4fcd |
| HandBrakeCLI-1.1.2-x86_64.flatpak | 6.88 | c8a43379914599283e28583b143cf9e82ab5a9a0 | 45a00f7480a8611886402f7f87fb5552cf33046d517f36756ff8342b4b4ddae5 |
| HandBrakeCLI-1.1.2.dmg | 13.01 | 713ba5ce63bfcc29ea8ee22b16ada2c9d750d529 | 0251e0824bb0c24726012ced40be4271d7af0494322997de6a3f6fcb257a3d00 |
| LibHB-1.1.2-win-x86_64.zip | 15.16 | 8db6fccc4cb81e37112366e5e4014e2c986ecda1 | 63b5876e843604926178829cfa8e2c9d0c6172022e314baa04e4362a45761423 |

### Version (1.1.1)
| File                               | Size (MB) | SHA1                                     | SHA256                                                           |
|------------------------------------|------|------------------------------------------|------------------------------------------------------------------|
| HandBrake-1.1.1-source.tar.bz2     | 15.3 | 4382f6cd053ea596cf7634f78550e605a574b34b | e3390c5fd901fb06d72e29c62a63d373d5fb5b3467295d114d815ae7b78a9d7a |
| HandBrake-1.1.1-x86_64-Win_GUI.exe | 11.7 | 2fc6b967b99446bb2c14ba1a72b29829a43d3a09 | 7295a2934a37d9fe4dcbf97539cbf6c743f896dd91c7114ba827df7103b044e4 |
| HandBrake-1.1.1-x86_64-Win_GUI.zip | 16.8 | 7484901496e10c116a100ebba0838facb002762a | 415afbe7f4b6e3ab0368ad74ae4ae5a65023beb70b3bb7855da819eee55315e1 |
| HandBrake-1.1.1-x86_64.flatpak     | 19.2 | b533450fbbf22c2d2eed9265cae4cfdaa1c1ed2a | ccdf5d7bb3b832972245219f246d724db4061465ee14c0e938d33cd82e478c1c |
| HandBrake-1.1.1.dmg                | 16.9 | e676628d09a285d0a0f8fc241de4144ed2204fca | 309f2c87d8d63819b1f6074dfd6e7827eb5c98cba56e08a8113413cfb984cfd9 |
| HandBrakeCLI-1.1.1-win-x86_64.zip  | 15.6 | 55c65433f8537f71285a3696c57df18e5d613e46 | 89a84259d7a4b285cf9f4c4e73b1f782b6442dd69f0add51b437d5136cf52f34 |
| HandBrakeCLI-1.1.1-x86_64.flatpak  | 7.12 | 031fc847a6097d3174b9c51450abd5ccefe4e89e | 9822b04c3f0d3f9ba44ae67da401e0d94f5c9cd80a75f14e72e1369639008f9e |
| HandBrakeCLI-1.1.1.dmg             | 13.5 | c6935b0113bf8c6bf0fd0f854041afc92dc19dff | 7098083141a685e1a6464942017c86a3ee13275ca6814fb31cf37b6fbe2d1dc0 |
| LibHB-1.1.1-win-x86_64.zip         | 15.8 | 550ec59b07692e3c6e3eff541a7110cdeacffaa2 | 72586788fe53d783059b3a93f8051f8abf828756e2113fe89b30500d4eb2cd03 |



### Version (1.1.0)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.1.0-source.tar.bz2 | 14.56 | b73a53b50b2c18709e570725e21557e49d8f5756 | a02e7c6f8bd8dc28eea4623663deb5971dcbca1ad59da9eb74aceb481d8c40da |
| HandBrake-1.1.0-x86_64-Win_GUI.exe| 11.15 | c570e7c892074158d72a8e767bbff2268c58e7ea | 9cf7c0813f91e16218eb770f834380cad0d1641d93ba93926702562bd9d2eece |
| HandBrake-1.1.0.dmg | 16.12 | 426d3cebfecca28387f77b86a09a6bf0c1776b52 | d2457954cab59a7bbc58f0c12a2b03e262f6d2eb5e7b43960ab04e87531b1e33 |
| HandBrakeCLI-1.1.0-win-x86_64.zip | 14.87 | 64ed4eb931cd4657b2273cb739fbfee502489b80 | 8a8b5370f4c0f397b5bc7ff626c29e68bcaf48993819044b2082f7c6632f74ff |
| HandBrakeCLI-1.1.0.dmg | 12.89 | 41625833e4ee0307373e384a33d4273f96212c52 | 006945a4cd98de2b227a9db0aa25107379c60404a4d3da06f98360c505f21715 |

### Version (1.0.7)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.0.7-i686-Win_GUI.exe | 9.85 | a3b5a28475ccf4d31a8d72e4de49a2302859110f | b35000df800b522bb48d0e8991fda009015e9335835977513850e35eb777c9d5 |
| HandBrake-1.0.7-x86_64-Win_GUI.exe | 10.22 | 602e342cd786227812c34040574084ca95bad479 | 3d63e96ba3e0e538d6d7fce86070fa5621b2bcd89123d53d25bbe625b7e7c4ba |
| HandBrake-1.0.7.dmg | 12.71 | 6d2e5158f101dad94ede3d5cf5fda8fe9fd3c3b9  | 3cd2e6228da211349574dcd44a0f67a3c76e5bd54ba8ad61070c21b852ef89e2 |
| HandBrake-1.0.7.tar.bz2 | 12.36 | fb5907840c0688e0692f092ecc592af8a6fa7e55  | ffdee112f0288f0146b965107956cd718408406b75db71c44d2188f5296e677f |
| HandBrakeCLI-1.0.7-win-i686.zip | 11.08 | bdcb588c00d5dea5efdd058fc69658a58788e5eb | 152046b12d17c576d68eedecf5231001fafbc660c27ce52075b7a48d8ca91c8a |
| HandBrakeCLI-1.0.7.dmg | 10.07 | 75c6204d7bd7d9c6e5b1fedb56697ae2f3857789 | 9c954eb29eeea863b3b330bcf72c9fc31af8e115dad7f83858af5b843a0f9c11 |
| HandBrakeCLI-1.0.7-win-x86_64.zip | 11.81 | e0f3deb227aeec128cf9414dd12f84fec8926374 | b00c00520705e05bfb42701b4121de8e56c9c283af2b30d42ce10b24823519e0 |


### Version (1.0.3)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.0.3-i686-Win_GUI.exe | 9.7 MB	 | 16f9e7b80b7d40c8908b3c0ce08b2b767988f286 | d515be89d06189df2383d55dd18bb4577b89462220e31dacf04c9df0b556222b |
| HandBrake-1.0.3-x86_64-Win_GUI.exe | 10.0 MB | 2c07352b32add0bffcf62476db090dbd76ce2145 | fcf38bac7721783c610fa7ae7748d4f0ed30359cb2ae69fbf147e74b1677c0b6 |
| HandBrake-1.0.3.dmg | 12.6 MB	 | b4c5fa4a2b45d6ab8d5024576bc2e8e11169ecf8 | 0db04efca99317a57a85477e06f8d96319dcbd0b22ce939241109a13ab2af93e |
| HandBrake-1.0.3.tar.bz2 | 12.0 MB | 1ae1cec085dfd081892127f23c3cf4b556f8d2fb | 591fb489edd6146136f0a92f895c2098365f612ad308d5ff9dc83223ad73ed27 |
| HandBrakeCLI-1.0.3-win-i686.zip | 10.9 MB	 | 81af97000c2cd45afaec6e1b698ff9bce6525f8e | 44df91708721dd131a504bd4b23f6b4f0ab582e88f6d91f87a28b260c27b8d18 |
| HandBrakeCLI-1.0.3-win-x86_64.zip |	11.6 MB | 5d5c373e5f63469023a016b024619b8208b964ec | 64cf72ce281a1abaf52924f5f531f4037311e6ed4dabc0ba8e7130f08f8c00fa |
| HandBrakeCLI-1.0.3.dmg	| 10.0 MB | 2c1fd8114ad6a7a1b0dd40dc9712ed6ef26ccd86 | 74f6c32b817eda5eb5543975ab961210299e6e5903185ac312acf1dfd6836c4c |

### Version (1.0.2)

| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.0.2-i686-Win_GUI.exe | 9.71 | 564fec517f67d51acc9db720663c6a2204fe138a | a7784f56ef28195930cdcc58b9b488c2379ba60bc57eb46a56271b12efed2b28 |
| HandBrake-1.0.2-x86_64-Win_GUI.exe | 10.07 | f4ad7da61ce8c41d916c4c54e3c4e5bba6557c8d | 41a174c78842917fd7a7481759b9bb31ed50894f9db3487426d1cee28b8c8d49 |
| HandBrake-1.0.2.dmg | 12.64 | d2607a6ef3b995767aa7496d5a93d0acf5bf0246 | f433d50e180f8a8ffc74422c2967c273d71bbc304987b26927eb87ef043e1a93 |
| HandBrake-1.0.2.tar.bz2 | 12.01 | f5d74276699051026ab920c29dd5077f9f16a3c3 | 18e4563cc150309df03f7e73462b823ba2eca61644a7a536c9930611f3f9aa1e |
| HandBrakeCLI-1.0.2-win-i686.zip | 10.93 | 2850cd3d76a3db3c3f01eb61502924ec084d3a5f | 7e40cc61ac1537b60ba214bce3c83d36062b4edc1292854028e7873963efd908 |
| HandBrakeCLI-1.0.2.dmg | 10.05 | 165da874447e5c67618e0086c9f7486934e00406 | 0b5c0646a6858fb3fae66b584cae133b1526f0514ada794c4bd109de66b431b0 |
| HandBrakeCLI-1.0.2-win-x86_64.zip | 11.67 | 88e026d8e67791f666801f5e8b2300abc34c4b03 | 419393cc99da1a0167b620b8705dddfce0c50f3f56900c45afc302806e1e032d |

### Version (1.0.1)

| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.0.1-i686-Win_GUI.exe | 9.71 | a0dd0cb03dc16c3af208d566393f2d4e10b566c3 | 7eb4bf518537783128d64a78d6a2fc116fb7bc16b431e759da41a3dc83efca69 |
| HandBrake-1.0.1-x86_64-Win_GUI.exe | 10.07 | 478b444e6707fb83a849fa4946becd01a6a03dcf | 1d4abe165716a1f022132d8addd185417b2d51eb70eeb4c5a7f19ad02a95712d |
| HandBrake-1.0.1.dmg | 12.64 | 31467599b070b54127f20f8964644c4afd4be564 | 27f936ef028c9d20ee5da2b23c7352968c98226274ca43f3bc1571cf71820673 |
| HandBrake-1.0.1.tar.bz2 | 12.01 | 5edc6c4da45cd22161d98174ff68555e696b7cd7 | af4badcdf56465abc798e5e11fe0e437e23ea89bbee20798408980a34c4d5876 |
| HandBrakeCLI-1.0.1-win-i686.zip | 10.93 | f7d6e265d6efd33ab5580ce2573b88f30cebda9f | 61b1c44aaeb2f76d44fa705f2ae8fc019ade0e9e92bc4235588bd652c5439013 |
| HandBrakeCLI-1.0.1-win-x86_64.zip | 11.67 | 81ac5c90f791105fdf753c7d77af26f65841cea0 | caf785506cbdf44996543c4df958869617d6744239a974f54861bc6e87e51171 |
| HandBrakeCLI-1.0.1.dmg | 10.05 | 6b1cb69990257926214ebe7520b65d9f49b34a3b | 045d884749480fbc8ed57a4ada7114a78d8352997eb391be09d69f770c73ab91 |


### Version (1.0.0)

| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-1.0.0-i686-Win_GUI.exe | 9.71 | 2896fe0e3c8516f44cf88b37650bc0c27207a88f | 0a408219c0d86aa25ac895b95c8fe8009d1f6ca5b7c21d340b20db1f8e66817c |
| HandBrake-1.0.0-x86_64-Win_GUI.exe | 10.07 | d304173fe8af7ed30d89f707fd1d16c8238e03bf | 6a3381b383b2e318fdf94b82130c5c9df570d6266084ada1af48ef2d35b6de92 |
| HandBrake-1.0.0.dmg | 12.64 | 2e6738133621299a2da221c6e3a181988ddc6ae2 | be51aa13eed29d6426e87f0111c0de2bd408214af4ba1b5d45c910ae1c626a52 |
| HandBrake-1.0.0.tar.bz2 | 12.01 | 7f8f03ea5731059d2b0aa93e9b6d939a5f261eed | 15fb4593c70d75621212e4499f018c3c93d7ce39f1083bf527d4616ded0044c5 |
| HandBrakeCLI-1.0.0-win-i686.zip | 10.93 | 845281a668ffae2c3a0b1b313ae6c3336efded3e | 0d8d7f27f8590453801f8fcfd54a08832bd85a5f70587ce14c76da160cc0ada2 |
| HandBrakeCLI-1.0.0-win-x86_64.zip | 11.67 | af9baf7b55e6c0982579a6c50c32739b022deef8 | b0e6ef7b2174641c4087fc874d90dac836c42554c8ea72d79230098571c7f56d |
| HandBrakeCLI-1.0.0.dmg | 10.05 | f72827157e27e63faae86c50a21fd120b11e5800 | 493cfd7d8e623242120a10ba976d28008cafc0424e864a5002f83a9e695bfe9b |

### Version (0.10.5)

| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.10.5-i686-Win_CLI.zip | 8.76 | 7d66daf8a5b3208854e5a490ecefaf12f54e33ba | 087dcf8be360ae68be112c1bb03b05c49359f44ed2206e0578e6254bf004a640 |
| HandBrake-0.10.5-i686-Win_GUI-1.exe | 14.8 | 0acc3b72430c0420504eee9fb4b20466c0b6fc42 | adf0ffbe277fe90b6a4c33deed149e59b04861c4ad2115aa9209279c7181ea10 |
| HandBrake-0.10.5-MacOSX.6_CLI_x86_64.dmg | 8.13 | f7ef19fc51a1058d590bf35f22d6975812ddeb43 | 7f292422f4e13b59a936bb4e433a9248afaf5dd5f428e5928d54b0dee98a8786 |
| HandBrake-0.10.5-MacOSX.6_GUI_x86_64.dmg | 10.26 | 9ad219b09570fd985d8ca8b7127f801833249de2 | a2f1cacfb508e5ebe2489c64fa15204f15578aaf5e7f8a5ae9ab1fdccde51222 |
| HandBrake-0.10.5-x86_64-Win_CLI.zip | 9.5 | cb9b25d289e8ff198cfc25065e0f659ac135d9b8 | 4bdcbd678f83163223b4dc8a959aead838ff6e01a3c67ef3319af3f06e1aeaaa |
| HandBrake-0.10.5-x86_64-Win_GUI-1.exe | 15.75 | 1cc2fff081e79ba7c4ce98bbe52919203d16d567 | c823c89acc4a3688eda9ccdd769147be61bcadbcbe08e35cb6212d322d38c584 |
| HandBrake-0.10.5.tar.bz2 | 9.97 | 3685e3f216468c9c5627b794a79cda96d6913caf | fb9230dd121b456f6829d1d25ac8bbf76e503b51c4efc70f0a7fd2bb8607e2f0 |

### Version (0.10.3)

| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.10.3-i686-Win_CLI.zip | 9.12 | df0848939bcf2381ef49bdf338c0dfc1ab3fb26d | 6f703f1af309fd5abd09738e08ee9f1c0686f26632c2abbc0f4f26f1b8ed5ec1 |
| HandBrake-0.10.3-i686-Win_GUI.exe | 15.4 | 115ac65b6826f250dc0527c7afde3cd5d9afa47b | e992eb2558f2557afd2b46bb3be67d2e20d95b77a9ca2e7455065bedfae13550 |
| HandBrake-0.10.3-MacOSX.6_CLI_x86_64.dmg | 8.11 | ec1f62db5a180fc624c44ea0776a19ac7b064844 | 6b349d63fa947215c4032d556ab98748ccfb4471954cda114099696378e75507 |
| HandBrake-0.10.3-MacOSX.6_GUI_x86_64.dmg | 10.21 | c578adfda26e20e12065ed3ee52f5c47ce80b3e5 | 5bf327f6d42901668490338c32eab8cc2d4db3e09ea1cb9b8c44573ed8fb5dda |
| HandBrake-0.10.3-x86_64-Win_CLI.zip | 9.92 | 37bb0fc997f53ec596174f31f2fe856e29836ef8 | 9bd695c7bbb15a0ce01c55735e3a6414360879624737ed7e4921ed4b0ac26c44 |
| HandBrake-0.10.3-x86_64-Win_GUI.exe | 16.45 | af993c65ee0be6820212187482745154dee50df8 | 3fe6f3b3004e733a1e7be2cd1243304eb1d91da805d3482799071c2b6aafa68a |
| HandBrake-0.10.3.tar.bz2 | 9.97 | 357eb86575b06069c303d35d386094e8bce5560c | 57144fa929382ba8dc0e32ccdb53b4c79f7baf83df0fc8a4c03eccba2d6aea87 |

### Version (0.10.2)

| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.10.2-i686-Win_CLI.zip | 9.05 | 7912de9fa74be269ccf4e2a15f078e8bd74c6d2e | 4d81eadb15cf1522645d4870e77bb9fb62d0d30ab5205861907126dcd43dbb7a |
| HandBrake-0.10.2-i686-Win_GUI.exe | 15.26 | d735ece4bd9a620036699405c40ab5314e954d1b | e9ee85392d724387b730caff027a4be4537357d451df685281e1bacedff3af0e |
| HandBrake-0.10.2-MacOSX.6_CLI_x86_64.dmg | 8 | e64a9884d52722993ec4b3f46c4908a33a90e937 | 4531d5b09b10e7d04aa35edac0a9979b995355b61bfe4c604d87d4daf66a590c |
| HandBrake-0.10.2-MacOSX.6_GUI_x86_64.dmg | 10.1 | 9e280ea1afd7e36518c93d35b5a64cca702b9cc9 | 9591cefbfcbe97ad4e039b456f82ea0e76035b5db9c9aa2ebca044fb171d4dd5 |
| HandBrake-0.10.2-x86_64-Win_CLI.zip | 9.75 | ae035e3bc8c80e4a69ac1f1fb20a12d925577b54 | 2eb3ccc64fa28b44545007669ccb963fae59c9b0931324facbb03d46cecfc005 |
| HandBrake-0.10.2-x86_64-Win_GUI.exe | 16.19 | b221858b745331178fcaf770c99182c17f4e2fa3 | f5b6dfdf5bc39b426b54e37907d4debaeacccfcd62b84e7b0d15acd849a8648f |
| HandBrake-0.10.2.tar.bz2 | 9.96 | 857c1c0c274f086424ce7863940c5ee0fd065c40 | 4cc3828393b26a982dbe00febd700c5090d3443c1d45492e0b373e02da73c699 |

### Version (0.10.1)

| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.10.1-i686-Win_CLI.zip | 8.97 | 306d470b99c1b4389cb20b7d29436ad6f0b8cd71 | 03931772bde4d315f8a956ac0cab27508f88b75b1ce32a7a94484dd9a67cde98 |
| HandBrake-0.10.1-i686-Win_GUI.exe | 15.11 | d00fdfd78783635576ddfd6f0a081e4f0d7de6ef | 3f970020ca94ec0a4c0ce54f97b2fe397fc610f3c5274d4970dbf09ec10e8cd4 |
| HandBrake-0.10.1-MacOSX.6_CLI_x86_64.dmg | 7.8 | 87aff78d6ed55fd42b1532b5b225a9c60a1b5559 | 457eecaa9758b91772c29874be1bac549d1d6645f7cac09c23886b734fe0151f |
| HandBrake-0.10.1-MacOSX.6_GUI_x86_64.dmg | 9.94 | 782d4a33cf1c9533b2ed41750b54d316e6958e33 | 7c6f231889433d932d3d483df8f4f90fab517386987376542176dd8d2d032bd2 |
| HandBrake-0.10.1-x86_64-Win_CLI.zip | 9.63 | e680ff66173bd7150d3352859e7633eaea2630f4 | f030a77723b953892a09f52f0fb5fb1d282c7ebe8a0f269b64911852c49f59f0 |
| HandBrake-0.10.1-x86_64-Win_GUI.exe | 15.98 | 265c287a6ea62b4838cde8e34f60ce74b1dd9d8b | 44ae8961c7c3a7fc1e7a1f389255c7874d591b683e55af50af2c7eee9ff914d2 |
| HandBrake-0.10.1.tar.bz2 | 9.96 | f5dbd665b39b6390ad1040d93898cd6d85ef6978 | 7ea42031fd4d5efd04903a9aae79c952c50fd43b6f7bf08fd1a93f6b358a23f5 |

### Version (0.10.0)

| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.10.0-i686-Win_CLI.zip | 8.96 | bc3761228c74d53936dae299f6ca3f2440d9b55d | 09eb0dd5250c8f4598d7a44975d1808c0978f125f92a76267a8e5189203a4159 |
| HandBrake-0.10.0-i686-Win_GUI.exe | 15.09 | f5055bb44eb5bd2006681a0bf39a7893c36e4270 | 8043fbe25778bceb89aa47de2789b0de6e6353e327379dbdb8f81f18905612d3 |
| HandBrake-0.10.0-MacOSX.6_CLI_x86_64.dmg | 7.79 | e6b2e0b2b9f1caaa24a64832b8d1a3bb3c3f929b | 84dcc20cffd2cbbe1d7804dbb8dfdb4ce7ce78b2f44ae25a998f18771a9c05f9 |
| HandBrake-0.10.0-MacOSX.6_GUI_x86_64.dmg | 9.92 | 05dba0571c61060834e21698019fc5f48239588a | c26a1a37d03c977e0296f0198ce11bf74ee5da8aa410ea3b5eef6449e0aa3c9c |
| HandBrake-0.10.0-x86_64-Win_CLI.zip | 9.62 | b6bd3d5b3b4cf47f0aa28e8c44c4f3d300dc5815 | 09373d38442f5d0789082a1e712ded1c15a9b508f17356438ba206f0c38a685f |
| HandBrake-0.10.0-x86_64-Win_GUI.exe | 15.95 | c00498018b1a2bc8699f15779030eb502d6e43b4 | fc3467590a1f1c13820eb13efdeba42f392a2e19b11ff4e90ab97a863263d080 |
| HandBrake-0.10.0.tar.bz2 | 9.89 | 5408b80694db602269b480e539ea5097fadbdca8 | a91042da3cc08454844f7c171ee2fde4f0ed08176407fc0328d5118227ed4114 |




### Version (0.9.9)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.9.9-1_i686-Win_GUI.exe | 13.24 | 2610a34a5e399bebaf1831ac22038e2f5373eeef | 0bed557edbd7af697d11404406924b5e3dc13f81de098a0c5bddd05a6574b33b |
| HandBrake-0.9.9-1_x86_64-Win_GUI.exe | 13.64 | 011f7f179d649ef301955d2b7e5d24fd7f6a4bc2 | 2efc0660481bda720696d9fbaf06b4325e58e904f8e38426b9186f9746ccba7d |
| HandBrake-0.9.9-i686-Win_CLI.zip | 7.72 | 04a70a7f92624564bb423ed8179fd0c4a62845f0 | 57eaf45edaae72217c39b1227ea726d86f5a83b5e8d8ebc9176afb278c94a2ee |
| HandBrake-0.9.9-i686-Win_GUI.exe | 13.24 | 802e300a904f628292cf350a6f4327ff04713bf5 | a5377ac5d841c7e06c844a7be3d1d040783eeab0f79aecba2badb25816c12f67 |
| HandBrake-0.9.9-MacOSX.6_CLI_x86_64.dmg | 6.57 | 8c175265b18bea37a9072ea90406192462600141 | 120d7d0a9af5d15813d05781cbbf2599e454b4400f0266db4fa1acd4f62d244e |
| HandBrake-0.9.9-MacOSX.6_GUI_x86_64.dmg | 8.65 | 9b6f0259f3378b0cc136378d7859162aa95c0eb7 | 050f9d0d3a126b25d24cb4971062d66f4f975317b6586f8c288795c17a0c05f9 |
| HandBrake-0.9.9-x86_64-Win_CLI.zip | 8.05 | 5c103914073cdedf0c05e6b3ce3325d0d3c814f6 | b1bf4cb69fbf4ea2aaf865b61bec808fac4e2d78d6122723ea28ea69b2083294 |
| HandBrake-0.9.9-x86_64-Win_GUI.exe | 13.63 | 94b7e3b3b6718035c471a45f0dc689487ec98209 | 49e3b5a6bcf856fb0fb169f935fe0e96ca1a14a14f8cdd13d510405c8f485ff1 |
| HandBrake-0.9.9.tar.bz2 | 8.88 | 64414bdc425115545f7dd735c7d1e30b8b005056 | a71dd774104cda00cfb51a813550351d638253791f2f419d04a66f3158a835b3 |



### Version (0.9.8)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.9.8-i686-Win_CLI.zip | 7.7 | 33141efe3203b8374c721b4cdf4c9784c09a6b3e | 6dcaa5ea0a71410da87eef8f565369953eda594e7a54c157cfc25ca3c2e2a404 |
| HandBrake-0.9.8-i686-Win_GUI.exe | 6.58 | 4c38058c681b4b88c74c51534f734f3ddd74339a | 1168c955ed08f7b4e96df07e28aaf9eecbc728b0f85cc0c75dcd054183c9b788 |
| HandBrake-0.9.8-MacOSX.6_CLI_x86_64.dmg | 6.51 | a1a55cc680f89b9da443689e96b82c1ccf13f6a9 | 30fb931dd9dc72612fbc4ab1bc75adf9d5996ab1597ae077ccf5aab76a3b6a86 |
| HandBrake-0.9.8-MacOSX.6_GUI_x86_64.dmg | 7.14 | d255b4daa64cc359209e306ff9ef8a24a66e20aa | 6c1d72d0d305542feb4e2986055a623783bcf77ce2281b2863ccbb8d41204373 |
| HandBrake-0.9.8-x86_64-Win_CLI.zip | 8.07 | 887b9b02b5a3da4c2c5c7478208035a4e6f598fc | c1044dd7deac4f328e06ce94345d22709e2f795e712174a6bc6b79ce698847d1 |
| HandBrake-0.9.8-x86_64-Win_GUI.exe | 6.88 | ee70dd10cf3932f8c0c772fcbe7630d4a17ee103 | b8930ab7e03568186366789b577d6a6b1dc0b41c66167e041ee8e334d93ef451 |
| HandBrake-0.9.8.tar.bz2 | 3.01 | d7b4cf51d61e36184f1ff6ca632ef13a9d6611d3 | dba75a9ff772e419c01d75532c1bf0d7253e73d7ead184eee755cd4c133dc798 |



### Version (0.9.6)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.9.6-i686-Win_CLI.zip | 7.71 | 9f685a157d855eb72459b23faad968c7ee77f196 | 619c4c3dbf814c717d5c46bd77ff4e0d8952c93224e2e39341d87f8113fe0917 |
| HandBrake-0.9.6-i686-Win_GUI.exe | 6.58 | 35f699550effdbbf5ea75648b3a33843f3e8be4e | 9546fe76d2a0d0b46a3f113c9ab3852beed554de7571bd8d92b7e3220e346318 |
| HandBrake-0.9.6-MacOSX.6_CLI_x86_64.dmg | 6.51 | ed8665b6152c95179605640c9f30ff98794ee4eb | 79b7d27616164c55ee38d6cc0bae059412a2be0fbba5528cbef38aeb45120c73 |
| HandBrake-0.9.6-MacOSX.6_GUI_x86_64.dmg | 7.14 | 416f979561392d7636fdf58d504dfd66b231a3ad | a6a1b8a1eb1ab6cca944398c11d0ebdd4a810d960e26b2d953df2790934797b1 |
| HandBrake-0.9.6-x86_64-Win_CLI.zip | 8.07 | 57bf597eadf5398b9adbfd492c6e90fd77fbda26 | 157206a2efcef38d211271dd2ec8d827164725362896b395ae2fb75b95ecf652 |
| HandBrake-0.9.6-x86_64-Win_GUI.exe | 6.87 | 677c122714153f785942f77e780cbf3e1579a7d1 | b88fadec950e7ffc5e20ce91d43aa619cf07d5ff6983c8429e488e23b2cbb1ec |
| HandBrake-0.9.6.tar.bz2 | 3.08 | d4895a2efa2c7a09a79ebea9bb465318dba5e660 | 8e7d3dd6d9eb10ba633bf0b6cabcc50a995699ec448f86cb9579c0d2fc7005f5 |
| HandBrake-cli-0.9.6-1.fc16.i686.rpm | 5.43 | 8b52b2007fd30d5897b3fdee1d625d0b2c7d8716 | 53d34c0eabfd2460453de02058c837b265b256f65792d36bb03170cfbdb62e69 |
| HandBrake-cli-0.9.6-1.fc16.x86_64.rpm | 5.55 | f9331d5ac399773e246b99b88165fb4b4642ee9b | 01baaca0b95256e5c3f1a754402aed8cf30ae9911b8dbf0fb3437969b994232e |
| HandBrake-gui-0.9.6-1.fc16.i686.rpm | 5.67 | 8bca0927a7d1ca42755f63233a91ce98717de176 | a0f1bf96dc6c3b7d9e03dbe39cd0a9b8c1b6aa433e0330bd0d8d012e8e54d332 |
| HandBrake-gui-0.9.6-1.fc16.x86_64.rpm | 5.82 | 00d68d8d68836256067d12d435179ebf1b44fcfe | 14b29848f0f586ddf3a6cd5bcde93ed7fffe43d142484583de65807400375e54 |



### Version (0.9.5)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.9.5-1-Fedora15_CLI_i686.rpm | 4.9 | 58e79472faa5bef9b1079e92755942d526d8ffb9 | 9c5978e331dc5e69f5638f46a8744f5d3555234c35133321d43ca5d8d20a4de6 |
| HandBrake-0.9.5-1-Fedora15_CLI_x86_64.rpm | 5.04 | f98fc788c7979c11831ced8e897a20416589f770 | d4d8b8cbd0841781cb2cbd107faa66c3f066481fa3705e17b14874931dc70c2c |
| HandBrake-0.9.5-1-Fedora15_GUI_i686.rpm | 5.13 | 48b31ce919732051abb8beb4e86b3eef70507a50 | 660b6cdca8d6aacdae745ce8b01be351c27ae09c9c3e6d7217a0bc8f38219a87 |
| HandBrake-0.9.5-1-Fedora15_GUI_x86_64.rpm | 5.28 | 22b5d9b3aee1876e38e7fc6b81c417172e26d042 | f8a1fd59a66e63f12d8f96bd3772164e9bc22c7a6dfde38dfade398ce4c627c2 |
| HandBrake-0.9.5-Fedora_CLI_i686.rpm | 4.85 | 9ce7faa031ce5b5da53b922a6eb43a35557fbf7d | 21cbfb7c939439271a0b9784d5fb0c668535ad03ab0dac5b64a9f159108cde18 |
| HandBrake-0.9.5-Fedora_CLI_x86_64.rpm | 5.17 | cdb588f6bc7012f32ff59b027db1c527654e34de | 5e3c921f542f93d415268f8086e3796d70ecb3f7b72707e465427c29b16ea9be |
| HandBrake-0.9.5-Fedora_GUI_i686.rpm | 5.08 | b06248fe49bc5bdaa1919e8a190b240d3a23b0dc | fae71f34e611d1fc550d47ac9d5f61a71a71750ba0e26d0ad2de184de04dd816 |
| HandBrake-0.9.5-Fedora_GUI_x86_64.rpm | 5.42 | 5fc28a703d38500f4c461550540e1a88ff95660b | 543cb00e14c8d92214605441afae5c5a3100f2b8ff8bc45a9920929dc234268e |
| HandBrake-0.9.5-MacOSX.5_CLI_i386.dmg | 6.02 | d51c10c5689a4d4ac56d5cd33d3fb36115752cf4 | a72809e3c5ed7e38cc0dca710fd0d0dbe06d155b117a234127f96547bd7b3214 |
| HandBrake-0.9.5-MacOSX.5_CLI_x86_64.dmg | 6.16 | fa62ee2529a4afbe3a775de67ed8eadae446bfdc | 9467baa21095630179e72d96d918713339541c584f9ff5bd5dd84acd7ba6deb4 |
| HandBrake-0.9.5-MacOSX.5_GUI_i386.dmg | 6.56 | 9853b2d9d54c831e7dfc085d16984d6800626f38 | ea1492b947a80fc5637973e3f9f38381a1fb8db5ef17d14f23a8612345a92292 |
| HandBrake-0.9.5-MacOSX.5_GUI_x86_64.dmg | 6.77 | 8719175152d18e3776bec0c0b0a4b30ba975742c | fc2c2443091976270d271100f00c3b8218046fc301fdafe2a14d1ca86a37c55e |
| HandBrake-0.9.5-Win_CLI.zip | 6.94 | 019b745b3e25dbf2f1479b3b4198af720ce2b821 | 60d5a05935df842c036063471773b38636178d0bec6d18eb7b238982fa5c07c5 |
| HandBrake-0.9.5-Win_GUI.exe | 5.74 | fcc7f913cca364dfcc356f0f10d5d2fd79a0e3f2 | 2a20efe700033ede96b84edb58fd6c8e9c9baa844d546b600ec2474d98132238 |
| HandBrake-0.9.5.tar.bz2 | 2.49 | 6db599fe96a640e5355f1c92b8915f11c7cb45ad | 3a9a89fee6bcaf9677107381a10fc53109630b0a5a201a7d63fd62ae28c9b25b |



### Version (0.9.4)
| File | Size | SHA1 | SHA256 |
| ---| ---| ---| ---|
| HandBrake-0.9.4-Fedora_CLI_i686.rpm | 3.98 | 8ab823905a92305146a96c93412448a4ebd853ad | 2b5cd42b9e4d179511f6df79d73b487e797c54fc99d2ab2669bfbec33b6f72ed |
| HandBrake-0.9.4-Fedora_CLI_x86_64.rpm | 4.25 | ff9ec8d29efed24e4f0017cfd99cee7e3db292b7 | e66356e3c00ccfa9917b863f65ec00ba5f94356f3c2f186049eb43de8a918fb4 |
| HandBrake-0.9.4-Fedora_GUI_i686.rpm | 4.2 | 7be560d9e2dbf2d38ea10dcd1a9b2ff0923cf5c5 | c0af7645f3540d5960b1a9a3404066c2f3569931ea21b74a0bcbc19ea0b41697 |
| HandBrake-0.9.4-Fedora_GUI_x86_64.rpm | 4.48 | 56ccf4a6c35043fcdf58e36dabb41524d751494f | 7fe4febd755b1c8adf0bcfe3eed490a11c263798e61b3f280782dc236edcafa8 |
| HandBrake-0.9.4-MacOSX.5_CLI_i386.dmg | 4.89 | c38ad104598733622547af19918cb72d3eb498bf | 00a2148e17e695c5466864833646449a22192c7710b1a2b716ea34980140e3ed |
| HandBrake-0.9.4-MacOSX.5_CLI_ppc.dmg | 4.53 | 67561dcdbbdfab2fbb90f12fb4efb1a8769900e7 | 5672560e82871bc134a1d23d4d0cd665392a10a869e6be4c371ff67f77704a7c |
| HandBrake-0.9.4-MacOSX.5_CLI_x86_64.dmg | 4.94 | d4f90a6ebb6f290fb8a70f657fc838f463ad8054 | 42d643efaa8fe7fbab3173a344165872958891fb1c4a780fe60d35afd33a36a3 |
| HandBrake-0.9.4-MacOSX.5_GUI_i386.dmg | 5.42 | 3b8be6b4e5f89e079ad89eef208bd8d3799371d1 | 3f2c956beacff45ff899f33eb15f58dee4f2d88c3155c74ac10da4c65778bf81 |
| HandBrake-0.9.4-MacOSX.5_GUI_ppc.dmg | 5.04 | 565057cc2ccb2f8d126e7626bdf98f3c1ce1de2e | ac9464c50a1832144fab8a8e4f0b38e41909b3d1d5d7a150201e9980ee02578d |
| HandBrake-0.9.4-MacOSX.5_GUI_x86_64.dmg | 5.54 | ccf27308b960f93a93d865f7886277b2848ba572 | c189ab5907311b67d177ad50d084a0dd5b986f95bb1945160df0aa4ed7ede1c4 |
| HandBrake-0.9.4-Ubuntu_CLI_i686.deb | 4.84 | 536d858554dd1922a2b7c2e4317b4e344ddaea95 | 93adff8279ab4f28f770417ec5aa431e0cf98546a33572da9f3c52201ee0f82e |
| HandBrake-0.9.4-Ubuntu_CLI_x86_64.deb | 5.18 | 8ae31641fc206c175bf725926fb85213942d51ac | f15ebcfae44bcce89bd065db79ce55c2c7ce74e3335868a5881959e5bcbe5189 |
| HandBrake-0.9.4-Ubuntu_GUI_i686.deb | 5.06 | 26f93d115d35148fbbddeeac324c4595868dedae | 9c92f02b618e00b3a84d24d564c6f8f43344f06217bde1adffde090f9eef22cb |
| HandBrake-0.9.4-Ubuntu_GUI_x86_64.deb | 5.4 | 85e38cab07b6bf63c7bf44ff71d5524fbf0c33b1 | b82fc38d3e2409fd966ce081caba9f1e42f2a1d7d5c681e49358e95a47738b2e |
| HandBrake-0.9.4-Win_CLI.zip | 5.61 | 3f42256473fc561d31523a1221f189bf398ccd49 | f365d6ce8003de6dbb60e18cf36ff3e7e35b57ce4d15853f8a1383f9721a8c98 |
| HandBrake-0.9.4-Win_GUI.exe | 4.66 | d5e800b29b7845f679554fb3d47650d9c3ed031b | 994f02c5de5c1ddbaf7eb042a7fdf395db2cdeb1cf2ba1974d02ef1bcde7e773 |
| HandBrake-0.9.4.tar.bz2 | 1.7 | 91329a83315b7eae0b2b3731a8bf0f2de2a6eb4d | 706b03db4e39446dc47eee2eee298d4aaa3ebd925130e8a84fdc903f231300ee |

