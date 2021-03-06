# Sony MDR-XB500
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -10.9; 23 -11.0; 25 -11.2; 28 -11.3; 31 -11.4; 34 -11.5; 37 -11.6; 41 -11.7; 45 -11.7; 49 -11.7; 54 -11.7; 60 -11.9; 66 -12.2; 72 -12.4; 79 -12.7; 87 -12.9; 96 -13.1; 106 -13.4; 116 -13.7; 128 -13.5; 141 -13.2; 155 -13.0; 170 -12.7; 187 -12.7; 206 -12.6; 227 -12.3; 249 -12.1; 274 -11.7; 302 -11.3; 332 -10.9; 365 -10.4; 402 -9.5; 442 -8.3; 486 -7.0; 535 -6.2; 588 -5.6; 647 -5.1; 712 -4.1; 783 -2.4; 861 -0.7; 947 -0.5; 1042 -0.5; 1146 -0.7; 1261 -2.3; 1387 -4.2; 1526 -5.3; 1678 -5.6; 1846 -5.6; 2031 -5.5; 2234 -4.9; 2457 -3.8; 2703 -2.3; 2973 -0.6; 3270 -0.5; 3597 -0.5; 3957 -1.4; 4353 -6.5; 4788 -9.8; 5267 -10.8; 5793 -9.9; 6373 -7.7; 7010 -5.1; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-XB500 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-XB500 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.7dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.3dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 31 Hz   | 0.24 | -3.9 dB |
| Peaking | 179 Hz  | 0.47 | -5.3 dB |
| Peaking | 943 Hz  | 1.53 | 7.3 dB  |
| Peaking | 3228 Hz | 3.39 | 6.9 dB  |
| Peaking | 526 Hz  | 6.17 | 1.1 dB  |
| Peaking | 1596 Hz | 6.49 | -1.0 dB |
| Peaking | 3896 Hz | 6.25 | 4.7 dB  |
| Peaking | 5203 Hz | 2.54 | -5.7 dB |
| Peaking | 7073 Hz | 5.5  | 2.4 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.6dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -4.7 dB |
| Peaking | 62 Hz    | 1.41 | -4.0 dB |
| Peaking | 125 Hz   | 1.41 | -5.8 dB |
| Peaking | 250 Hz   | 1.41 | -5.1 dB |
| Peaking | 500 Hz   | 1.41 | -0.8 dB |
| Peaking | 1000 Hz  | 1.41 | 6.3 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.4 dB  |
| Peaking | 4000 Hz  | 1.41 | 2.7 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.5 dB |
| Peaking | 16000 Hz | 1.41 | 0.2 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Sony%20MDR-XB500/Sony%20MDR-XB500.png)