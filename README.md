<p align="center">
  <img src="https://img.icons8.com/color/480/periodic-table-of-elements.png" height="180"/>
</p><br/>


[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)
![Open Source](https://img.shields.io/badge/Open%20Source-FB542B?style=for-the-badge&logoColor=white)
![Version](https://img.shields.io/badge/Version%201.2-2962FF?style=for-the-badge&logoColor=white)
<br/>
[![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)](../../actions)

# Periodic-Table-DB
An JSON file of the Periodic Table

> A database with all the information about each element of the periodic table.
> Still in development, but will definitely have a lot more content.

# Table of Contents
- [Future Plans](#future-plans)
- [Overview](#overview)

## Future plans
> We plan to add more precise information to the elements of the periodic table, not just about mass or electrons.

## Overview

> Data

| Name | Description | Type |
| --- | --- | --- |
| Element | Returns a name of element | String |
| Symbol | Returns a symbol of element| String |
| Atomic-Number | Returns a atomic number of element | Integer |
| Weight | Returns a weight of element | Integer |
| Group | Only for (Position) | String |
| Period | Only for (Position) | String |
| Family | Only for (Position) | String |
| Electrons | Only for (Electrons) | String |
| Details | Not avaliable for Compounds | Array |

> Details

| Name | Description | Type |
| --- | --- | --- |
| Metal-Type | Returns a metal type of element | String |
| State | Returns a state of element, example (Gas, Solid) | String |
| Energy-Levels | Returns a energy levels of element | Array |
| Electronegativity | Returns a Electronegativity of element | Float |
| Melting-Point | Returns a Melting Point of element | Float |
| Boiling-Point | Returns a Melting Point of element | Float |
| Electron-Affinity | Returns a Electron Affinity of element | Float |
| Ionization | Returns a Ionization of element | Float |
| Radius | Returns a Radius of element | Float |
| Density | Returns a Density of element | Float |
| Discovered | Returns the year the element was discovered | String |

> Expanded Details (Electrons)

| Name | Description | Type |
| --- | --- | --- |
| Oxidation-States | Returns a oxidation states of element | Array |
| Configuration | Returns a configuration of element | Array |
| Expanded | Returns a extra states of element | Array |
| HOAO | Returns a quantic numbers of element | Array |

[Back to Top](#table-of-contents)
