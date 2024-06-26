# Zenlink Assets Info

![Check](https://github.com/trustwallet/assets/workflows/Check/badge.svg)

# To Add Logo
- [ ] Fork the Github repository

- [ ] Create folder with name of token smartcontact address in **CHECKSUM** format `blockchains/moonriver/assets/<token_smartcontract_address>/`.

- [ ] Tell your designer that token image must be in PNG format, avoid transparent background, recommended size 256x256px, with max file size of 100kB.

- [ ] Upload your logo with file named `logo.png` to previously created folder with smartcontract address, and if you done all correctly your path should look like this. `blockchains/moonriver/assets/0x1A93B23281CC1CDE4C4741353F3064709A16197d/logo.png`

- [ ] Run `npm run check` and make sure tests pass

- [ ] Create a pull request to the master branch of the zenlink/assets repo

- [ ] Send an asset merge request email to apollo@zenlink.pro


# Scripts

There are several scripts available for maintainers:

- `npm run check` -- Execute validation checks; also used in continuous integration.
- `npm run check-sanity` -- Strict subset of checks
- `npm run fix` -- Perform automatic fixes where possible
- `npm run fix-sanity` -- Stricter subset
- `npm run updateAuto` -- Run automatic updates from external sources, executed regularly (GitHub action)
- `npm run update` -- Run manual updates from external sources, for manual use.
- `npm test` -- Run script unit tests
- `npm lint` -- Run Lint static code check

# Disclaimer
- The purpose of this repo is just to record and provide token profile freely.
- Zenlink doesn't fully verify the authenticity of the token profile and will be not responsible for that.
- Zenlink has the right to reject any token information that we consider suspicious.
- When adding token information, please ensure that the information is true and reliable, Zenlink will reserve the right to pursue legal action.