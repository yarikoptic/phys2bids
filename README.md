
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3559868.svg)](https://doi.org/10.5281/zenodo.3559868)
[![Join the chat at https://gitter.im/phys2bids/community](https://badges.gitter.im/phys2bids/community.svg)](https://gitter.im/phys2bids/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


phys2bids
=========
Phys2bids is a python3 library meant to format physiological files in BIDS.
It was born for Acqknowledge files (BIOPAC), and at the moment it supports
``.acq`` files as well as ``.txt`` files obtained by labchart
(ADInstruments).
It doesn't support physiological files recorded with the MRI, as you can find a software for it [here](https://github.com/tarrlab/physio2bids).

It requires python 3.6 or above, as well as the modules:
- `numpy >= 1.9.3`
- `matplotlib >= 3.1.1`

In order to process ``.acq`` files, it needs [`bioread`](https://github.com/uwmadison-chm/bioread), an excellent module
that can be found at [this link](https://github.com/uwmadison-chm/bioread).

### Linux and mac installation
Donwload the package as zip from github and uncompress or if you have ``git`` use the command:

``git clone https://github.com/smoia/phys2bids.git``

open a terminal in the phy2bids folder and execute the command:

``pip3 install .``

type the command:

``phys2bids -v``

if your output is: ``phys2bids 0.4.0`` or similar, phys2bids is ready to be used.

**The project is currently under development**.
Any suggestion/bug report is welcome! Feel free to open an issue.

At the very moment, it assumes all the extracted channels from a file
have the same sampling freq.

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!


License
-------

Copyright 2019, The Phys2BIDS community.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/danalclop"><img src="https://avatars0.githubusercontent.com/u/38854309?v=4" width="100px;" alt=""/><br /><sub><b>danalclop</b></sub></a><br /><a href="#design-danalclop" title="Design">🎨</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!