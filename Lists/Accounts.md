List of online accounts and organisation.

* royamrit49@gmail.com — Personal stuff
* me@ekunazanu.foo — Public internet stuff
* somelazykoala@gmail.com — Old internet stuff

| Platform       | Account       | Seed | Size | Email                                 | Number         | Notes                  |
| -------------- | ------------- | ---- | ---- | ------------------------------------- | -------------- | ---------------------- |
| Google         | royamrit49    | 0    | 24   | royamrit49@gmail.com                  | +91 6901369564 | Change password        |
| Google         | somelazykoala | 0    | 24   | somelazykoala@gmail.com               |                |                        |
| Twitch         | somelazykoala | 0    | 24   | somelazykoala@gmail.com               |                |                        |
| Discord        | somelazykoala | 0    | 24   | somelazykoala@gmail.com               |                |                        |
| Kudoboard      | somelazykoala | 0    | 24   | somelazykoala@gmail.com               |                |                        |
| Tutanota       | somelazykoala | 0    | 24   | somelazykoala@tutanota.com            |                | Delete account         |
| Proton         | ekunazanu     | 0    | 24   | ekunazanu@proton.me                   | +91 6901369564 |                        |
| Porkbun        | ekunazanu     | 0    | 24   | ekunazanu@proton.me                   | +91 6901369564 |                        |
| Github         | ekunazanu     | 0    | 24   | me@ekunazanu.foo                      |                |                        |
| Codeberg       | ekunazanu     | 0    | 24   | me@ekunazanu.foo                      |                |                        |
| Stack Exchange | ekunazanu     | 0    | 24   | me@ekunzanu.foo                       |                |                        |
| Hacker News    | ekunazanu     | 0    | 24   | me@ekunazanu.foo                      |                |                        |
| Leetcode       | ekunazanu     | 0    | 24   | me@ekunazanu.foo                      |                |                        |
| Discord        | ezpznu        | 0    | 24   | me@ekunazanu.foo                      |                | Create account         |
| Discord        | camor         | 0    | 24   | royamrit49@gmail.com                  |                | Delete account         |
| Reddit         | anchit_       | 0    | 24   | royamrit49@gmail.com                  |                | Change password        |
| Open AI        |               | 0    | 24   | royamrit49@gmail.com                  |                | Change password        |
| Spotify        | romcomdom     | 0    | 24   | royamrit49@gmail.com                  |                | Change password        |
| Zerodha        | MMD399        | 0    | 24   | royamrit49@gmail.com                  | +91 6901369564 | Change password & TOTP |
| Microsoft      | anchit        | 0    | 24   | anchit.mitblr2022@learner.manipal.edu |                | Change password        |
| LinkedIn       |               | 0    | 24   | royamrit49@gmail.com                  |                | Change password        |
| Amazon         |               | 0    | 24   | royamrit49@gmail.com                  | +91 6901369564 | Change password        |
| Flipkart       |               | 0    | 24   | royamrit49@gmail.com                  | +91 6901369564 | Change password        |
| Adidas         |               | 0    | 24   | royamrit49@gmail.com                  | +91 6901369564 | Change password        |
| Coursera       |               | 0    | 24   | royamrit49@gmail.com                  |                | Delete Account         |
| Firefox        |               | 0    | 24   | royamrit49@gmail.com                  |                | Delete Account         |
| Firefox        |               | 0    | 24   | somelazykoala@tutanota.com            |                | Delete Account         |
| ZLibrary       |               | 0    | 24   | royamrit49@gmail.com                  |                | Delete Account         |
| SquareSpace    |               | 0    | 24   | royamrit49@gmail.com                  |                | Delete Account         |
| iCloud         | anchitroy     | 0    | 24   | anchitroy@icloud.com                  |                | Delete Account         |
| PC/HP          | root          | N/A  | N/A  | N/A                                   | N/A            | N/A                    |
| PC/HP          | ekunazanu     | N/A  | N/A  | N/A                                   | N/A            | N/A                    |

The password for the accounts is is the first `Size` characters of `SHA256(Account + Platform + Seed + Secret)`. All in lowercase and no spaces, except the `Secret`. Some accounts may have two factor authentication on.

.
├── SBI
│   ├── anchitroy51.gpg
│   └── anchitroy51.profilepassword.gpg
├── incometaxgov
│   └── royamrit49(a)gmail.com.gpg
├── lenskart
│   └── royamrit49(a)gmail.com.gpg
├── manipal.slcm
│   └── 225890220.gpg
└── vidyalakshmi
    └── royamrit49(a)gmail.com.gpg

## Keys

| Key Type | Name      | Location                                | Notes                     |
| -------- | --------- | --------------------------------------- | ------------------------- |
| SSH      | HP        | hp://home/ekunazanu/.ssh/hp             | Github, Codeberg, Commits |
| Minisign | ekunazanu | hp://home/ekunazanu/.minisign/ekunazanu | Packages                  |

Note: It's preferable to transition to quantum resistant cryptosystems once it is more mainstream, viable, and convenient.

* Image headers — LUKS backup headers in case I lose the encryption keys to my drive. Image headers stored at `/home/`.
* 2FA Codes — Used in case I lose access to 2FA devices. 2FA codes are symmetrically encrypted using *insert algorithm*. The decryption phrase/key is the same passphrase used to create other passwords above. Codes are stored at `/home/`.