Abortion Analysis
================

  - [Overview](#overview)
  - [Methodology](#method)
  - [Limitations](#limitations)
  - [License](#license)

## Overview

This repository contains the code needed to reproduce [Mother Jones'](https://www.motherjones.com) analysis of Center for Reproductive Rights and Centers for Disease Control and Prevention abortion data. The analysis uses 2020 Decennial Census data to quantify the impact of states likely to ban abortion if the Supreme Court strikes down *Roe v. Wade*. That outcome seemed more likely after a [leaked draft Supreme Court opinion](https://www.motherjones.com/politics/2022/05/roe-wade-abortion-rights-overturned-supreme-court-leak/) was published.

[Read the story about this analysis.](https://www.motherjones.com/?p=957871&preview=true)

<a id="method"></a>

## Methodology

#### How we analyzed abortion data

Mother Jones acquired data for abortions from the [Centers for Disease Control and Prevention Abortion Surveillance program](https://www.cdc.gov/mmwr/volumes/70/ss/ss7009a1.htm#T1_down) and joined it to an [analysis of state laws](https://reproductiverights.org/maps/what-if-roe-fell/) from the Center for Reproductive Rights and 2020 Decennial Census data. Analysis was done in R using the Tidyverse.

<a id="limitations"></a>

## Errors and limitations

Census analysis excludes California, New Hampshire and Maryland because those states do not report data to the CDC.

<a id="license"></a>

## License

Copyright 2022, Foundation for National Progress

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
