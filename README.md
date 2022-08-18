# Introduction

## Methodology

This aim of this project is to predict space groups for trenary compounds using their respective constituent elements' intrinsic properties.

## Data Dictionary

The data are retrieved from [NOMAD Repository](https://nomad-lab.eu/) and they are described in the following tables.

| Number of Features | Number of entries |
|--------------------|-------------------|
| 69                 | 181054            |

| **Feature**                    | Describtion                                           |
|--------------------------------|-------------------------------------------------------|
| A Symbol                       | First element symbol in the periodic table            |
| Atomic Number 1                | Atomic number of the first element                    |
| Coefficient 1                  | Number of atoms of the fist element in the compound   |
| B Symbol                       | Second element symbol in the periodic table           |
| Atomic Number 2                | Atomic number of the second element                   |
| Coefficient 2                  | Number of atoms of the second element in the compound |
| C Symbol                       | Third element symbol in the periodic table            |
| Atomic Number 3                | Atomic number of the third element                    |
| Coefficient 3                  | Number of atoms of the third element in the compound  |
| A Group                        | First element group                                   |
| B Group                        | Second element group                                  |
| C Group                        | Third element group                                   |
| A Period                       | First element period in the periodic table            |
| B Period                       | Second element period in the periodic table           |
| C Period                       | Third element period in the periodic table            |
| Formula                        | Compound formula                                      |
| A IonizationPot1st             | First ionization potential for 1st element            |
| A Electronegativity            | Atom electronegativity for 1st element                |
| A IonicRadius                  | Ionic radius of the 1st element                       |
| B IonizationPot1st             | First ionization potential for 2nd element            |
| B Electronegativity            | Atom electronegativity for 2nd element                |
| B IonicRadius                  | Ionic radius of the 2nd element                       |
| C IonizationPot1st             | First ionization potential for 3rd element            |
| C Electronegativity            | Atom electronegativity for 3rd element                |
| C IonicRadius                  | Ionic radius of the 3rd element                       |
| B/C IonicRadius                | Ionic radius from B to C in the compound              |
| C/A IonicRadius                | Ionic radius from C to A in the compound              |
| A/C IonicRadius                | Ionic radius from A to C in the compound              |
| B/A IonicRadius                | Ionic radius from B to A in the compound              |
| A/B IonicRadius                | Ionic radius from A to B in the compound              |
| No. of Atoms                   | Total number of atoms in the compound                 |
| SG \#                          | Number of the space group                             |
| SG Symbol                      | Space group symbol                                    |
| Crystal System                 | Crystal system of the compound                        |
| PG                             | Point group of the compound                           |
| cell_volume                    | Total cell volum of the system                        |
| a                              | Dimension a of the cell                               |
| b                              | Dimension b of the cell                               |
| c                              | Dimension c of the cell                               |
| alpha                          | First angle in the cell                               |
| beta                           | Second angle in the cell                              |
| A - rd [A]                     | d orbital radius for atom A                           |
| A - rp [A]                     | p orbital radius for atom A                           |
| A - rs [A]                     | s orbital radius for atom A                           |
| A - Lowest unocc KS level [eV] | Lowest unoccupied KS level in the atom A              |
| A - Highest occ KS level [eV]  | Highest unoccupied KS level in the atom A             |
| A - Electroneg                 | Electronegativity of atom A in the compound           |
| A - e Affin                    | Electron affinity for atom A                          |
| A - Ioniz Pot                  | Ionization potential of atom A                        |
| B - rp [A]                     | p orbital radius for atom B                           |
| B - rs [A]                     | s orbital radius for atom B                           |
| B - Lowest unocc KS level [eV] | Lowest unoccupied KS level in the atom B              |
| B - Highest occ KS level [eV]  | Highest unoccupied KS level in the atom B             |
| B - Electroneg                 | Electronegativity of atom B in the compound           |
| B - e Affin                    | Electron affinity for atom B                          |
| B - Ioniz Pot                  | Ionization potential of atom B                        |
| C - rd [A]                     | d orbital radius for atom C                           |
| C - rp [A]                     | p orbital radius for atom C                           |
| C - rs [A]                     | s orbital radius for atom C                           |
| C - Lowest unocc KS level [eV] | Lowest unoccupied KS level in the atom C              |
| C - Highest occ KS level [eV]  | Highest unoccupied KS level in the atom C             |
| C - Electroneg                 | Electronegativity of atom C in the compound           |
| C - e Affin                    | Electron affinity for atom C                          |
| C - Ioniz Pot                  | Ionization potential of atom C                        |
| gamma                          | gamma angle in the cell                               |
| Oxidation 1                    | Oxidation number of atom A                            |
| Oxidation 2                    | Oxidation number of atom A                            |
| Oxidation 3                    | Oxidation number of atom A                            |
