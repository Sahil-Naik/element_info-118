#Program to find info about 118 elements from chemistry
#dictonary method is used
elements_dict = {'H' : 1.008,'HE' : 4.003, 'LI' : 6.941, 'BE' : 9.012,\
                 'B' : 10.811, 'C' : 12.011, 'N' : 14.007, 'O' : 15.999,\
                 'F' : 18.998, 'NE' : 20.180, 'NA' : 22.990, 'MG' : 24.305,\
                 'AL' : 26.982, 'SI' : 28.086, 'P' : 30.974, 'S' : 32.066,\
                 'CL' : 35.453, 'AR' : 39.948, 'K' : 39.098, 'CA' : 40.078,\
                 'SC' : 44.956, 'TI' : 47.867, 'V' : 50.942, 'CR' : 51.996,\
                 'MN' : 54.938, 'FE' : 55.845, 'CO' : 58.933, 'NI' : 58.693,\
                 'CU' : 63.546, 'ZN' : 65.38, 'GA' : 69.723, 'GE' : 72.631,\
                 'AS' : 74.922, 'SE' : 78.971, 'BR' : 79.904, 'KR' : 84.798,\
                 'RB' : 84.468, 'SR' : 87.62, 'Y' : 88.906, 'ZR' : 91.224,\
                 'NB' : 92.906, 'MO' : 95.95, 'TC' : 98.907, 'RU' : 101.07,\
                 'RH' : 102.906, 'PD' : 106.42, 'AG' : 107.868, 'CD' : 112.414,\
                 'IN' : 114.818, 'SN' : 118.711, 'SB' : 121.760, 'TE' : 126.7,\
                 'I' : 126.904, 'XE' : 131.294, 'CS' : 132.905, 'BA' : 137.328,\
                 'LA' : 138.905, 'CE' : 140.116, 'PR' : 140.908, 'ND' : 144.243,\
                 'PM' : 144.913, 'SM' : 150.36, 'EU' : 151.964, 'GD' : 157.25,\
                 'TB' : 158.925, 'DY': 162.500, 'HO' : 164.930, 'ER' : 167.259,\
                 'TM' : 168.934, 'YB' : 173.055, 'LU' : 174.967, 'HF' : 178.49,\
                 'TA' : 180.948, 'W' : 183.84, 'RE' : 186.207, 'OS' : 190.23,\
                 'IR' : 192.217, 'PT' : 195.085, 'AU' : 196.967, 'HG' : 200.592,\
                 'TL' : 204.383, 'PB' : 207.2, 'BI' : 208.980, 'PO' : 208.982,\
                 'AT' : 209.987, 'RN' : 222.081, 'FR' : 223.020, 'RA' : 226.025,\
                 'AC' : 227.028, 'TH' : 232.038, 'PA' : 231.036, 'U' : 238.029,\
                 'NP' : 237, 'PU' : 244, 'AM' : 243, 'CM' : 247, 'BK' : 247,\
                 'CF' : 251, 'ES' : 252, 'FM' : 257, 'MD' : 258, 'NO' : 259,\
                 'LR' : 262, 'RF' : 261, 'DB' : 262, 'SG' : 266, 'BH' : 264,\
                 'HS' : 269, 'MT' : 268, 'DS' : 271, 'RG' : 272, 'CN' : 285,\
                 'NH' : 284, 'FL' : 289, 'MC' : 288, 'LV' : 292, 'TS' : 294,\
                 'OG' : 294}

elements_name = {'H' : "Hydrogen(H)", 'HE' : 'Helium(He)', 'LI' : 'Lithium(Li)', 'BE' : 'Beryllium(Be)',\
                 'B' : 'Boron(B)', 'C' : 'Carbon(C)', 'N' : 'Nitrogen(N)', 'O' : 'Oxygen(O)',\
                 'F' : 'Flourine(F)', 'NE' : 'Neon(Ne)', 'NA' : 'Sodium(Na)',\
                 'MG' : 'Magnesium(Mg)', 'AL' : 'Aluminium(Al)', 'SI' : 'Silicon(Si)',\
                 'P' : 'Phosporus(P)', 'S' : 'Sulfur(S)', 'CL' : 'Clorine(Cl)', 'AR' : 'Argon(Ar)',\
                 'K' : 'Potassium(K)', 'CA' : 'Calcium(Ca)', 'SC' : 'Scandium(Sc)', 'TI' : 'Titanium(Ti)',\
                 'V' : 'Vandium(V)', 'CR' : 'Cromium(Cr)', 'MN' : 'Manganese(Mn)', 'FE' : 'Iron(Fe)',\
                 'CO' : 'Cobalt(Co)', 'NI' : 'Nickel(Ni)', 'CU' : 'Copper(Cu)', 'ZN' : 'Zinc(Zn)', 'GA' : 'Gallilium(Ga)', 'GE' : 'Germanium(Ge)',\
                 'AS' : 'Arsenic(As)', 'SE' : 'Selenium(Se)', 'BR' : 'Bromine(Br)', 'KR' : 'Krypton(Kr)',\
                 'RB' : 'Rubidium(Rb)', 'SR' : 'Strontium(Sr)', 'Y' : 'Yttrium(Y)', 'ZR' : 'Zirconium(Zr)',\
                 'NB' : 'Niobium(Nb)', 'MO' : 'Molybdenum(Mo)',\
                 'TC' : 'Technetium(Tc)', 'RU' : 'Ruthenium(Ru)', 'RH' : 'Rhodium(Rh)', 'PD' : 'Palladium(Pd)',\
                 'AG' : 'Silver(Ag)', 'CD' : 'Cadmium(Cd)', 'IN' : 'Indium(In)', 'SN' : 'Tin(Sn)',\
                 'SB' : 'Antimony(Sb)', 'TE' : 'Tellurium(Te)',\
                 'I' : 'Iodine(I)', 'XE' : 'Xenon(Xe)', 'CS' : 'Caesium(Cs)', 'BA' : 'Barium(Ba)',\
                 'LA' : 'Lanthanum(La)', 'CE' : 'Cerium(Ce)', 'PR' : 'Praseodymium(Pr)', 'ND' : 'Neodymium(Nd)',\
                 'PM' : 'Promethium(Pm)', 'SM' : 'Samarium(Sm)',\
                 'EU' : 'Europium(Eu)', 'GD' : 'Gadolinium(Gd)', 'TB' : 'Terbium(Tb)', 'DY' : 'Dysprosium(Dy)',\
                 'HO' : 'Holomium(Ho)', 'ER' : 'Erbium(Er)', 'TM' : 'Thulium(Tm)', 'YB' : 'Ytterbium(Yb)',\
                 'LU' : 'Lutetium(Lu)', 'HF' : 'Hafnium(Hf)',\
                 'TA' : 'Tantalum(Ta)', 'W' : 'Tungsten(W)', 'RE' : 'Rhenium(Re)', 'OS' : 'Osmium(Os)',\
                 'IR' : 'Iridium(Ir)', 'PT' : 'Platinum(Pt)', 'AU' : 'Gold(Au)', 'HG' : 'Mercury(Hg)',\
                 'TL' : 'Thallium(Tl)', 'PB' : 'Lead(Pb)',\
                 'BI' : 'Bismuth(Bi)', 'PO' : 'Polonium(Po)', 'AT' : 'Astatine(At)',\
                 'RN' : 'Radon(Rn)', 'FR' : 'Francium(Fr)', 'RA' : 'Radium(Ra)', 'AC' : 'Actinium(Ac)',\
                 'TH' : 'Thorium(Th)', 'PA' : 'Protactinium(Pa)', 'U' : 'Uranium(U)',\
                 'NP' : 'Neptunium(Np)', 'PU' : 'Plutonium(Pu)', 'AM' : 'Americium(Am)',\
                 'CM' : 'Curium(Cm)', 'BK' : 'Berkelium(Bk)', 'CF' : 'Californium(Cf)',\
                 'ES' : 'Einsteinium(Es)', 'FM' : 'Fermium(Fm)', 'MD' : 'Mendelevium(Md)', 'NO' : 'Nobelium(No)',\
                 'LR' : 'Lawrencium(Lr)', 'RF' : 'Rutherfordium(Rf)', 'DB' : 'Dubnium(Db)', 'SG' : 'Seaborgium',\
                 'BH' : 'Bohrium(Bh)', 'HS' : 'Hassium(Hs)', 'MT' : 'Meitnerium(Mt)',\
                 'DS' : 'Darmstadtium(Ds)', 'RG' : 'Roentgenium(Rg)', 'CN' : 'Copernicium(Cn)',\
                 'NH' : 'Nihonium(Nh)', 'FL' : 'Flerovium(Fl)', 'MC' : 'Moscovium(Mc)', 'LV' : 'Livermorium(LV)',\
                 'TS' : 'Tennessine(Ts)', 'OG' : 'Oganesson(Og)'}

elements_radius = {'H' : 0.53, 'HE' : 0.31, 'LI' : 1.67, 'BE' : 1.12, 'B' : 0.87,\
                   'C' : 0.67, 'N' : 0.56, 'O' : 0.48, 'F' : 0.42, 'NE' : 0.38,\
                  'NA' : 1.90, 'MG' : 1.45, 'AL' : 1.18, 'SI' : 1.11, 'P' : 0.98,\
                  'S' : 0.88, 'CL' : 0.79, 'AR' : 0.71, 'K' : 2.43, 'CA' : 1.94,\
                 'SC' :1.84, 'TI' : 1.76, 'V' : 1.71, 'CR' : 1.66,\
                 'MN' : 1.61, 'FE' : 1.56, 'CO' : 1.52, 'NI' : 1.49,\
                 'CU' : 1.45, 'ZN' : 1.42, 'GA' : 1.36, 'GE' : 1.25,\
                 'AS' : 1.14, 'SE' : 1.03, 'BR' : 0.94, 'KR' : 0.88,\
                 'RB' : 2.65, 'SR' : 2.19, 'Y' : 2.12, 'ZR' : 2.06,\
                 'NB' : 1.98, 'MO' : 1.90, 'TC' : 1.83, 'RU' : 1.78,\
                 'RH' : 1.73, 'PD' : 1.69, 'AG' : 1.65, 'CD' : 1.61,\
                 'IN' : 1.56, 'SN' : 1.45, 'SB' : 1.33, 'TE' : 1.23,\
                 'I' : 1.15, 'XE' : 1.08, 'CS' : 2.98, 'BA' : 2.53,\
                 'LA' : 1.95, 'CE' : 1.85, 'PR' : 2.47, 'ND' : 2.06,\
                 'PM' : 2.05, 'SM' : 2.38, 'EU' : 2.31, 'GD' : 2.33,\
                 'TB' : 2.25, 'DY': 2.28, 'HO' : 2.26, 'ER' : 2.26,\
                 'TM' : 2.22, 'YB' : 2.22, 'LU' : 2.17, 'HF' : 2.08,\
                 'TA' : 2.00, 'W' : 1.93, 'RE' : 1.88, 'OS' : 1.85,\
                 'IR' : 1.80, 'PT' : 1.77, 'AU' : 1.71, 'HG' : 1.71,\
                 'TL' : 1.56, 'PB' : 1.54, 'BI' : 1.43, 'PO' : 1.35,\
                 'AT' : 1.27, 'RN' : 1.20, 'FR' : 'Unidentified', 'RA' : 'Unidentified',\
                 'AC' : 1.95, 'TH' : 1.80, 'PA' : 1.80, 'U' : 1.75,\
                 'NP' : 1.75, 'PU' : 1.75, 'AM' : 1.75, 'CM' : 'Unidentified', 'BK' : 2.00,\
                 'CF' : 'Unidentified', 'ES' : 'Unidentified', 'FM' : 'Unidentified', 'MD' : 'Unidentified', 'NO' : 'Unidentified',\
                 'LR' : 'Unidentified', 'RF' : 'Unidentified', 'DB' : 'Unidentified', 'SG' : 'Unidentified', 'BH' : 'Unidentified',\
                 'HS' : 'Unidentified', 'MT' : 'Unidentified', 'DS' : 'Unidentified', 'RG' : 'Unidentified', 'CN' : 'Unidentified',\
                 'NH' : 'Unidentified', 'FL' : 'Unidentified', 'MC' : 'Unidentified', 'LV' : 'Unidentified', 'TS' : 'Unidentified',\
                 'OG' : 'Unidentified'}

elements_density = {'H' : 0.00008988,'HE' : 0.0001785, 'LI' : 0.534, 'BE' : 1.85,\
                 'B' : 2.34, 'C' : 2.67, 'N' : 0.0012506, 'O' : 0.001429,\
                 'F' : 0.001696, 'NE' : 0.0008999, 'NA' : 0.971, 'MG' : 1.738,\
                 'AL' : 2.698, 'SI' : 2.3296, 'P' : 1.82, 'S' : 2.067,\
                 'CL' : 0.003214, 'AR' : 0.0017837, 'K' : 0.862, 'CA' : 1.54,\
                 'SC' : 2.989, 'TI' : 4.54, 'V' : 6.11, 'CR' : 7.15,\
                 'MN' : 7.44, 'FE' : 7.874, 'CO' : 8.86, 'NI' : 8.912,\
                 'CU' : 8.96, 'ZN' : 7.134, 'GA' : 5.907, 'GE' : 5.323,\
                 'AS' : 5.776, 'SE' : 4.809, 'BR' : 3.122, 'KR' : 0.003733,\
                 'RB' : 1.532, 'SR' : 2.64, 'Y' : 4.469, 'ZR' : 6.506,\
                 'NB' : 8.57, 'MO' :10.22, 'TC' : 11.5, 'RU' : 12.37,\
                 'RH' : 12.41, 'PD' : 12.02, 'AG' : 10.501, 'CD' : 8.69,\
                 'IN' : 7.287, 'SN' : 7.287, 'SB' : 6.685, 'TE' : 6.232,\
                 'I' : 4.93, 'XE' : 0.005887, 'CS' : 1.873, 'BA' : 3.594,\
                 'LA' : 6.145, 'CE' : 6.77, 'PR' : 6.773, 'ND' : 7.007,\
                 'PM' : 7.26, 'SM' : 7.52, 'EU' : 5.243, 'GD' : 7.895,\
                 'TB' : 8.229, 'DY': 8.55, 'HO' : 8.795, 'ER' : 9.066,\
                 'TM' : 9.321, 'YB' : 6.965, 'LU' : 9.84, 'HF' : 13.31,\
                 'TA' : 16.654, 'W' : 19.25, 'RE' : 21.02, 'OS' : 22.59,\
                 'IR' : 22.56, 'PT' : 21.46, 'AU' : 19.282, 'HG' : 13.5336,\
                 'TL' : 11.85, 'PB' : 11.342, 'BI' : 9.807, 'PO' : 9.32,\
                 'AT' : 7, 'RN' : 0.009731, 'FR' : 1.87, 'RA' : 5.5,\
                 'AC' : 10.07, 'TH' : 11.72, 'PA' : 15.37, 'U' : 18.95,\
                 'NP' : 20.45, 'PU' : 19.85, 'AM' : 13.69, 'CM' : 13.51, 'BK' : 14.79,\
                 'CF' : 15.1, 'ES' : 8.84, 'FM' : 9.7, 'MD' : 10.3, 'NO' : 9.9,\
                 'LR' : 15.6, 'RF' : 23.2, 'DB' : 29.3, 'SG' : 35.0, 'BH' : 37.1,\
                 'HS' : 40.7, 'MT' : 37.4, 'DS' : 34.8, 'RG' : 28.7, 'CN' : 14.0,\
                 'NH' : 16, 'FL' : 14, 'MC' : 13.5 ,'LV' : 12.9, 'TS' : 7.2,\
                 'OG' : 7}

a = input("Enter elements initials : ")
a = a.upper()

weight = elements_dict.get(a)

radius = elements_radius.get(a)

density = elements_density.get(a)

name = elements_name.get(a)

print("Name and symbol of given element is : ",name)

print("Atomic weight = ", weight,"amu")

print("Atomic radius = ", radius,"Å")

print("Density = ", density,"kg/cubic m")
