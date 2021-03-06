# HiFiMAN HE-400 2014
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.6; 25 -0.7; 28 -0.9; 31 -1.0; 34 -1.1; 37 -1.1; 41 -1.1; 45 -1.2; 49 -1.3; 54 -1.4; 60 -1.5; 66 -1.9; 72 -2.5; 79 -3.0; 87 -3.3; 96 -3.8; 106 -4.0; 116 -4.2; 128 -4.5; 141 -4.7; 155 -4.8; 170 -4.9; 187 -5.1; 206 -5.4; 227 -5.5; 249 -5.8; 274 -5.9; 302 -6.0; 332 -5.7; 365 -5.3; 402 -5.2; 442 -5.6; 486 -6.2; 535 -6.2; 588 -5.7; 647 -5.1; 712 -5.3; 783 -5.3; 861 -4.8; 947 -4.2; 1042 -3.6; 1146 -3.3; 1261 -2.5; 1387 -2.2; 1526 -2.1; 1678 -1.8; 1846 -2.3; 2031 -3.3; 2234 -3.5; 2457 -3.9; 2703 -4.8; 2973 -4.7; 3270 -3.9; 3597 -4.1; 3957 -2.9; 4353 -6.0; 4788 -5.4; 5267 -3.9; 5793 -2.7; 6373 -6.3; 7010 -7.3; 7711 -7.8; 8482 -9.2; 9330 -7.6; 10263 -4.8; 11289 -4.8; 12418 -4.8; 13660 -4.8; 15026 -4.8; 16529 -4.8; 18182 -4.8; 20000 -8.4
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`HiFiMAN HE-400 2014 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `HiFiMAN HE-400 2014 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.3dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 19 Hz    | 0.53 | 4.0 dB  |
| Peaking | 56 Hz    | 1.14 | 2.1 dB  |
| Peaking | 471 Hz   | 0.42 | -1.3 dB |
| Peaking | 1495 Hz  | 1.24 | 3.4 dB  |
| Peaking | 8350 Hz  | 3.58 | -4.7 dB |
| Peaking | 517 Hz   | 8.64 | -0.5 dB |
| Peaking | 3863 Hz  | 7.71 | 2.2 dB  |
| Peaking | 5521 Hz  | 1.95 | -2.6 dB |
| Peaking | 5654 Hz  | 5.76 | 5.4 dB  |
| Peaking | 19851 Hz | 2.67 | -3.5 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 4.3 dB  |
| Peaking | 62 Hz    | 1.41 | 2.4 dB  |
| Peaking | 125 Hz   | 1.41 | -0.0 dB |
| Peaking | 250 Hz   | 1.41 | -0.8 dB |
| Peaking | 500 Hz   | 1.41 | -1.4 dB |
| Peaking | 1000 Hz  | 1.41 | 1.1 dB  |
| Peaking | 2000 Hz  | 1.41 | 2.0 dB  |
| Peaking | 4000 Hz  | 1.41 | 0.7 dB  |
| Peaking | 8000 Hz  | 1.41 | -3.0 dB |
| Peaking | 16000 Hz | 1.41 | 0.3 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/HiFiMAN%20HE-400%202014/HiFiMAN%20HE-400%202014.png)