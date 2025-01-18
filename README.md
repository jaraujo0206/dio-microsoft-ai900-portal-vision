# dio-microsoft-ai900-portal-vision
 Reconhecimento Facial e transformação de imagens em Dados no Azure ML.  

![alt text]({D09A6931-40B2-44C6-BEF4-FF2E30AC6C28}.png)  
![alt text](20200202_081953.jpg)  
![alt text](image.png)

~~~JSON
[  
  {  
    "recognitionModel":   "reconhecimento_01",  
    "faceRectangle": {  
      "largura": 385,  
      "altura": 442,  
      "esquerda": 1195,  
      "topo": 1404  
    },  
    "faceMarcos": {  
      "pupilaEsquerda": {  
        "x": 1321,4,  
        "e": 1536,4  
      },  
      "pupilaRight": {  
        "x": 1467,3,  
        "e": 1594,1  
      },  
      "ponta do nariz": {  
        "x": 1352,3,  
        "e": 1633  
      },  
      "bocaEsquerda": {  
        "x": 1267,7,  
        "e": 1673,7  
      },  
      "bocaDireita": {  
        "x": 1411,  
        "e": 1730,4  
      },  
      "sobrancelhaEsquerdaExterna": {  
        "x": 1293,1,  
        "e": 1480,5  
      },  
      "sobrancelhaEsquerdaInterna": {  
        "x": 1366,9,  
        "e": 1507,9  
      },  
      "olhoEsquerdoExterno": {  
        "x": 1296,6,  
        "e": 1527,3  
      },  
      "olhoEsquerdoTopo": {  
        "x": 1326,7,  
        "e": 1529  
      },  
      "olhoEsquerdoInferior": {  
        "x": 1316,2,  
        "e": 1541,2  
      },  
      "olhoEsquerdoInterno": {  
        "x": 1346,1,  
        "e": 1547,8  
      },  
      "sobrancelhadireitainterna": {  
        "x": 1442,3,  
        "e": 1539,7  
      },  
      "sobrancelhaDireitaExterna": {
        "x": 1532,2,
        "e": 1584,4
      },
      "olhoDireitoInterior": {
        "x": 1441,1,
        "e": 1586,1
      },
      "olhoDireitoTopo": {
        "x": 1468,5,
        "e": 1583,8
      },
      "olhoDireitoInferior": {
        "x": 1465,5,
        "e": 1601
      },
      "olhoDireitoExterno": {
        "x": 1494,
        "e": 1605,5
      },
      "narizRaizEsquerda": {
        "x": 1365,3,
        "e": 1562,2
      },
      "narizRaizDireita": {
        "x": 1406,7,
        "e": 1577,9
      },
      "noseLeftAlarTop": {
        "x": 1332,8,
        "e": 1603.1
      },
      "noseRightAlarTop": {
        "x": 1398,8,
        "e": 1629,7
      },
      "noseLeftAlarOutTip": {
        "x": 1308,5,
        "e": 1623,4
      },
      "noseRightAlarOutTip": {
        "x": 1403,3,
        "e": 1663,8
      },
      "topo do lábio superior": {
        "x": 1338,8,
        "e": 1693,2
      },
      "lábiosuperiorinferior": {
        "x": 1332,1,
        "e": 1702
      },
      "underLipTop": {
        "x": 1325,6,
        "e": 1717,4
      },
      "sobLipBottom": {
        "x": 1318,9,
        "e": 1734,9
      }
    },
    "Atributos de rosto": {
      "máscara": {
        "tipo": "noMask",
        "narizEBocaCoberto": falso
      }
    }
  },
  {
    "recognitionModel": "reconhecimento_01",
    "faceRectangle": {
      "largura": 345,
      "altura": 355,
      "esquerda": 754,
      "topo": 1449
    },
    "faceMarcos": {
      "pupilaEsquerda": {
        "x": 922,4,
        "e": 1549,5
      },
      "pupilaRight": {
        "x": 1021,
        "e": 1645,3
      },
      "ponta do nariz": {
        "x": 941,4,
        "e": 1666,9
      },
      "bocaEsquerda": {
        "x": 832,5,
        "e": 1646,3
      },
      "bocaDireita": {
        "x": 930,7,
        "e": 1739,7
      },
      "sobrancelhaEsquerdaExterna": {
        "x": 895,5,
        "e": 1495,2
      },
      "sobrancelhaEsquerdaInterna": {
        "x": 973,6,
        "e": 1559,7
      },
      "olhoEsquerdoExterno": {
        "x": 903,3,
        "e": 1532,4
      },
      "olhoEsquerdoTopo": {
        "x": 930,8,
        "e": 1543,2
      },
      "olhoEsquerdoInferior": {
        "x": 916,6,
        "e": 1554,8
      },
      "olhoEsquerdoInterno": {
        "x": 938,9,
        "e": 1567,5
      },
      "sobrancelhadireitainterna": {
        "x": 1021,3,
        "e": 1607,5
      },
      "sobrancelhaDireitaExterna": {
        "x": 1071,6,
        "e": 1658,6
      },
      "olhoDireitoInterior": {
        "x": 1002,9,
        "e": 1632,2
      },
      "olhoDireitoTopo": {
        "x": 1028,1,
        "e": 1637,2
      },
      "olhoDireitoInferior": {
        "x": 1016,4,
        "e": 1651,2
      },
      "olhoDireitoExterno": {
        "x": 1036,6,
        "e": 1660,6
      },
      "narizRaizEsquerda": {
        "x": 958,9,
        "e": 1595,1
      },
      "narizRaizDireita": {
        "x": 988,
        "e": 1622,7
      },
      "noseLeftAlarTop": {
        "x": 925,5,
        "e": 1624,3
      },
      "noseRightAlarTop": {
        "x": 969,5,
        "e": 1663,4
      },
      "noseLeftAlarOutTip": {
        "x": 896,2,
        "e": 1630,8
      },
      "noseRightAlarOutTip": {
        "x": 960,7,
        "e": 1690,8
      },
      "topo do lábio superior": {
        "x": 904,3,
        "e": 1693,4
      },
      "lábiosuperiorinferior": {
        "x": 893,9,
        "e": 1701,4
      },
      "underLipTop": {
        "x": 875,4,
        "e": 1720,1
      },
      "sobLipBottom": {
        "x": 861,6,
        "e": 1734
      }
    },
    "Atributos de rosto": {
      "máscara": {
        "tipo": "noMask",
        "narizEBocaCoberto": falso
      }
    }
  },
  {
    "recognitionModel": "reconhecimento_01",
    "faceRectangle": {
      "largura": 112,
      "altura": 149,
      "esquerda": 1111,
      "topo": 1517
    },
    "faceMarcos": {
      "pupilaEsquerda": {
        "x": 1178,6,
        "e": 1590,5
      },
      "pupilaRight": {
        "x": 1193,1,
        "e": 1597,3
      },
      "ponta do nariz": {
        "x": 1190,2,
        "e": 1632,4
      },
      "bocaEsquerda": {
        "x": 1146,1,
        "e": 1640,4
      },
      "bocaDireita": {
        "x": 1159,5,
        "e": 1643,2
      },
      "sobrancelhaEsquerdaExterna": {
        "x": 1181,5,
        "e": 1569,8
      },
      "sobrancelhaEsquerdaInterna": {
        "x": 1201,6,
        "e": 1582
      },
      "olhoEsquerdoExterno": {
        "x": 1173,6,
        "e": 1587,1
      },
      "olhoEsquerdoTopo": {
        "x": 1181,8,
        "e": 1589,8
      },
      "olhoEsquerdoInferior": {
        "x": 1177,4,
        "e": 1592,7
      },
      "olhoEsquerdoInterno": {
        "x": 1181,8,
        "e": 1592,7
      },
      "sobrancelhadireitainterna": {
        "x": 1207,2,
        "e": 1586,4
      },
      "sobrancelhaDireitaExterna": {
        "x": 1202,8,
        "e": 1583
      },
      "olhoDireitoInterior": {
        "x": 1190,3,
        "e": 1596,7
      },
      "olhoDireitoTopo": {
        "x": 1196,3,
        "e": 1596,1
      },
      "olhoDireitoInferior": {
        "x": 1192,6,
        "e": 1599,5
      },
      "olhoDireitoExterno": {
        "x": 1193,3,
        "e": 1596,9
      },
      "narizRaizEsquerda": {
        "x": 1187,9,
        "e": 1597,3
      },
      "narizRaizDireita": {
        "x": 1193,3,
        "e": 1599,7
      },
      "noseLeftAlarTop": {
        "x": 1175,9,
        "e": 1615,8
      },
      "noseRightAlarTop": {
        "x": 1185,
        "e": 1617,8
      },
      "noseLeftAlarOutTip": {
        "x": 1166,8,
        "e": 1622,8
      },
      "noseRightAlarOutTip": {
        "x": 1177,7,
        "e": 1625,7
      },
      "topo do lábio superior": {
        "x": 1166,6,
        "e": 1644,2
      },
      "lábiosuperiorinferior": {
        "x": 1161,4,
        "e": 1645,8
      },
      "underLipTop": {
        "x": 1158,6,
        "e": 1648,3
      },
      "sobLipBottom": {
        "x": 1154,9,
        "e": 1653,6
      }
    },
    "Atributos de rosto": {
      "máscara": {
        "tipo": "outraMáscaraOuOclusão",
        "narizEBocaCoberto": falso
      }
    }
  },
  {
    "recognitionModel": "reconhecimento_01",
    "faceRectangle": {
      "largura": 88,
      "altura": 175,
      "esquerda": 1747,
      "topo": 1812
    },
    "faceMarcos": {
      "pupilaEsquerda": {
        "x": 1812,
        "e": 1888,6
      },
      "pupilaRight": {
        "x": 1793,8,
        "e": 1874,7
      },
      "ponta do nariz": {
        "x": 1760,9,
        "e": 1895,2
      },
      "bocaEsquerda": {
        "x": 1777,2,
        "e": 1943
      },
      "bocaDireita": {
        "x": 1759,
        "e": 1935
      },
      "sobrancelhaEsquerdaExterna": {
        "x": 1820,9,
        "e": 1880,1
      },
      "sobrancelhaEsquerdaInterna": {
        "x": 1805,8,
        "e": 1867
      },
      "olhoEsquerdoExterno": {
        "x": 1818,9,
        "e": 1893,2
      },
      "olhoEsquerdoTopo": {
        "x": 1811,3,
        "e": 1883
      },
      "olhoEsquerdoInferior": {
        "x": 1809,4,
        "e": 1891,3
      },
      "olhoEsquerdoInterno": {
        "x": 1808,3,
        "e": 1887
      },
      "sobrancelhadireitainterna": {
        "x": 1799,4,
        "e": 1861,9
      },
      "sobrancelhaDireitaExterna": {
        "x": 1795,7,
        "e": 1862,4
      },
      "olhoDireitoInterior": {
        "x": 1797,4,
        "e": 1879,6
      },
      "olhoDireitoTopo": {
        "x": 1793,9,
        "e": 1869
      },
      "olhoDireitoInferior": {
        "x": 1789,8,
        "e": 1876,7
      },
      "olhoDireitoExterno": {
        "x": 1794,3,
        "e": 1873,4
      },
      "narizRaizEsquerda": {
        "x": 1798,8,
        "e": 1883,2
      },
      "narizRaizDireita": {
        "x": 1793,4,
        "e": 1877,6
      },
      "noseLeftAlarTop": {
        "x": 1787,2,
        "e": 1903
      },
      "noseRightAlarTop": {
        "x": 1778,5,
        "e": 1895.1
      },
      "noseLeftAlarOutTip": {
        "x": 1784,8,
        "e": 1915,2
      },
      "noseRightAlarOutTip": {
        "x": 1773,3,
        "e": 1907,7
      },
      "topo do lábio superior": {
        "x": 1758,5,
        "e": 1921,9
      },
      "lábiosuperiorinferior": {
        "x": 1758,3,
        "e": 1927,4
      },
      "underLipTop": {
        "x": 1753,3,
        "e": 1941,9
      },
      "sobLipBottom": {
        "x": 1749,1,
        "e": 1947,5
      }
    },
    "Atributos de rosto": {
      "máscara": {
        "tipo": "faceMask",
        "narizEBocaCoberto": falso
      }
    }
  },
  {
    "recognitionModel": "reconhecimento_01",
    "faceRectangle": {
      "largura": 120,
      "altura": 128,
      "esquerda": 573,
      "topo": 1160
    },
    "faceMarcos": {
      "pupilaEsquerda": {
        "x": 625,6,
        "e": 1198,2
      },
      "pupilaRight": {
        "x": 667,1,
        "e": 1225,8
      },
      "ponta do nariz": {
        "x": 631,3,
        "e": 1231,5
      },
      "bocaEsquerda": {
        "x": 599,6,
        "e": 1242,7
      },
      "bocaDireita": {
        "x": 632,3,
        "e": 1265,8
      },
      "sobrancelhaEsquerdaExterna": {
        "x": 616,
        "e": 1180
      },
      "sobrancelhaEsquerdaInterna": {
        "x": 642,4,
        "e": 1195,8
      },
      "olhoEsquerdoExterno": {
        "x": 618,6,
        "e": 1194,3
      },
      "olhoEsquerdoTopo": {
        "x": 627,3,
        "e": 1195,9
      },
      "olhoEsquerdoInferior": {
        "x": 624,2,
        "e": 1200
      },
      "olhoEsquerdoInterno": {
        "x": 632,2,
        "e": 1202,6
      },
      "sobrancelhadireitainterna": {
        "x": 661,6,
        "e": 1208,3
      },
      "sobrancelhaDireitaExterna": {
        "x": 687,
        "e": 1227,1
      },
      "olhoDireitoInterior": {
        "x": 660,4,
        "e": 1221,6
      },
      "olhoDireitoTopo": {
        "x": 668,6,
        "e": 1223,2
      },
      "olhoDireitoInferior": {
        "x": 665,8,
        "e": 1227,6
      },
      "olhoDireitoExterno": {
        "x": 673,6,
        "e": 1230,8
      },
      "narizRaizEsquerda": {
        "x": 639,
        "e": 1208,8
      },
      "narizRaizDireita": {
        "x": 651,1,
        "e": 1216,6
      },
      "noseLeftAlarTop": {
        "x": 627,
        "e": 1220,1
      },
      "noseRightAlarTop": {
        "x": 644,4,
        "e": 1232
      },
      "noseLeftAlarOutTip": {
        "x": 616,9,
        "e": 1225,4
      },
      "noseRightAlarOutTip": {
        "x": 642,2,
        "e": 1243,5
      },
      "topo do lábio superior": {
        "x": 619,5,
        "e": 1249,3
      },
      "lábiosuperiorinferior": {
        "x": 616,6,
        "e": 1252,5
      },
      "underLipTop": {
        "x": 614,6,
        "e": 1255,2
      },
      "sobLipBottom": {
        "x": 610,7,
        "e": 1260,6
      }
    },
    "Atributos de rosto": {
      "máscara": {
        "tipo": "noMask",
        "narizEBocaCoberto": falso
      }
    }
  },
  {
    "recognitionModel": "reconhecimento_01",
    "faceRectangle": {
      "largura": 86,
      "altura": 128,
      "esquerda": 257,
      "topo": 903
    },
    "faceMarcos": {
      "pupilaEsquerda": {
        "x": 282,4,
        "e": 948,7
      },
      "pupilaRight": {
        "x": 294,1,
        "e": 955,1
      },
      "ponta do nariz": {
        "x": 261,8,
        "e": 966,4
      },
      "bocaEsquerda": {
        "x": 267,6,
        "e": 988,9
      },
      "bocaDireita": {
        "x": 279,2,
        "e": 996,4
      },
      "sobrancelhaEsquerdaExterna": {
        "x": 282,8,
        "e": 938,1
      },
      "sobrancelhaEsquerdaInterna": {
        "x": 284,8,
        "e": 939,5
      },
      "olhoEsquerdoExterno": {
        "x": 281,7,
        "e": 948,3
      },
      "olhoEsquerdoTopo": {
        "x": 282,2,
        "e": 946,9
      },
      "olhoEsquerdoInferior": {
        "x": 281,8,
        "e": 949,9
      },
      "olhoEsquerdoInterno": {
        "x": 283,7,
        "e": 949,6
      },
      "sobrancelhadireitainterna": {
        "x": 290,1,
        "e": 942,2
      },
      "sobrancelhaDireitaExterna": {
        "x": 306,7,
        "e": 951,7
      },
      "olhoDireitoInterior": {
        "x": 292,5,
        "e": 954,5
      },
      "olhoDireitoTopo": {
        "x": 293,8,
        "e": 952,8
      },
      "olhoDireitoInferior": {
        "x": 293,4,
        "e": 956,4
      },
      "olhoDireitoExterno": {
        "x": 296,9,
        "e": 956,9
      },
      "narizRaizEsquerda": {
        "x": 283,7,
        "e": 951,2
      },
      "narizRaizDireita": {
        "x": 286,4,
        "e": 953,1
      },
      "noseLeftAlarTop": {
        "x": 273,1,
        "e": 963,4
      },
      "noseRightAlarTop": {
        "x": 280,9,
        "e": 968,5
      },
      "noseLeftAlarOutTip": {
        "x": 270,3,
        "e": 970,3
      },
      "noseRightAlarOutTip": {
        "x": 280,1,
        "e": 977,7
      },
      "topo do lábio superior": {
        "x": 266,
        "e": 986,2
      },
      "lábiosuperiorinferior": {
        "x": 266,
        "e": 988,8
      },
      "underLipTop": {
        "x": 265,8,
        "e": 990,7
      },
      "sobLipBottom": {
        "x": 264,4,
        "e": 994,2
      }
    },
    "Atributos de rosto": {
      "máscara": {
        "tipo": "noMask",
        "narizEBocaCoberto": falso
      }
    }
  }
]
~~~