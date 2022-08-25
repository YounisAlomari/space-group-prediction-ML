# Introduction

## Methodology

The aim of this project is to predict space groups structure for ternary compounds using their respective constituent elements' intrinsic properties. The material space is restricted for Trenary compounds and to elements from 1 to 85 in the periodic table except Noble gases, a.k.a. 18th column.

## Data Dictionary

The data are retrieved from [NOMAD Repository](https://nomad-lab.eu/) and they are described in the following tables.

| Number of Features | Number of entries |
|--------------------|-------------------|
| 12                 | 181054            |

| **Feature**        | Describtion                                           |
|--------------------|-------------------------------------------------------|
| Coefficient 1      | Number of atoms of the fist element in the compound   |
| Coefficient 2      | Number of atoms of the second element in the compound |
| Coefficient 3      | Number of atoms of the third element in the compound  |
| A IonizationPot1st | First ionization potential for 1st element            |
| A IonicRadius      | Ionic radius of the 1st element                       |
| B IonizationPot1st | First ionization potential for 2nd element            |
| B IonicRadius      | Ionic radius of the 2nd element                       |
| C IonizationPot1st | First ionization potential for 3rd element            |
| C IonicRadius      | Ionic radius of the 3rd element                       |
| Oxidation 1        | Oxidation number of atom A                            |
| Oxidation 2        | Oxidation number of atom B                            |
| Oxidation 3        | Oxidation number of atom C                            |
| SG \#              | Number of the space group (Target)                    |
