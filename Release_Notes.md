---
pagetitle: Release Notes for LSM6DSO16IS Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LSM6DSO16IS Component Driver
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LSM6DSO16IS component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}

<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 17-October-2022</label>
<div>			

## Main changes

### First release

- First official release [ref. DS v2.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 6-April-2023</label>
<div>

## Main changes

- Fix software_reset method
- Fix ISPU memory read/write APIs

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.1.0 / 23-May-2023</label>
<div>

## Main changes

- Use a single lsm6dsv_sh_slv_cfg_read() API for all targets
- fix shub register names (SLAVE -> SLV)
- add sh_status_get() API
- change sh_read_data_raw_get() API signature
- Change lsm6dso16is_mem_bank_set() API
- review read/write reg ret value checks
- Fix MISRA errors

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.1.1 / 30-June-2023</label>
<div>

## Main changes

- Do not break lines if not longer than 100 columns
- Fix ISPU read/write routines adding clk disabling
- Fix API name typo (ispu_read_dummy_cfg)

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V3.0.0 / 20-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)
- Add "const" to ctx arg for all APIs

##

</div>

<input type="checkbox" id="collapse-section6" checked aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V3.0.1 / 20-Jun-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description

##

</div>
:::

:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LSM6DSO16IS,
visit:
[LSM6DSO16IS](https://www.st.com/en/mems-and-sensors/lsm6dso16is.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
