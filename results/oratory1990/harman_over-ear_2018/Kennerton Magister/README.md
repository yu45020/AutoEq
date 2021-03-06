# Kennerton Magister
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -3.5; 23 -4.0; 25 -4.5; 28 -5.1; 31 -5.5; 34 -5.8; 37 -6.1; 41 -6.5; 45 -6.8; 49 -7.2; 54 -7.4; 60 -7.3; 66 -6.7; 72 -6.3; 79 -7.7; 87 -9.8; 96 -9.8; 106 -11.2; 116 -12.1; 128 -12.6; 141 -12.9; 155 -12.9; 170 -12.6; 187 -12.2; 206 -12.1; 227 -10.9; 249 -8.9; 274 -6.1; 302 -2.6; 332 -0.5; 365 -1.1; 402 -3.5; 442 -5.4; 486 -6.0; 535 -7.0; 588 -7.6; 647 -7.6; 712 -7.2; 783 -6.8; 861 -6.7; 947 -7.0; 1042 -6.9; 1146 -6.5; 1261 -5.9; 1387 -5.2; 1526 -4.5; 1678 -3.8; 1846 -3.5; 2031 -3.1; 2234 -3.3; 2457 -4.4; 2703 -5.7; 2973 -6.5; 3270 -6.8; 3597 -2.3; 3957 -5.9; 4353 -8.2; 4788 -11.3; 5267 -13.8; 5793 -13.0; 6373 -3.2; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.6; 13660 -10.2; 15026 -14.6; 16529 -16.0; 18182 -13.4; 20000 -8.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Kennerton Magister GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Kennerton Magister ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 176 Hz   | 0.8  | -7.4 dB  |
| Peaking | 332 Hz   | 2.8  | 9.9 dB   |
| Peaking | 5282 Hz  | 3.52 | -11.5 dB |
| Peaking | 7764 Hz  | 0.24 | 4.0 dB   |
| Peaking | 16433 Hz | 0.85 | -12.3 dB |
| Peaking | 14 Hz    | 0.75 | 4.8 dB   |
| Peaking | 1996 Hz  | 3.29 | 2.0 dB   |
| Peaking | 2979 Hz  | 6.14 | -2.6 dB  |
| Peaking | 6610 Hz  | 7.15 | 8.3 dB   |
| Peaking | 6683 Hz  | 2.15 | -3.1 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | 1.1 dB   |
| Peaking | 62 Hz    | 1.41 | 1.1 dB   |
| Peaking | 125 Hz   | 1.41 | -7.7 dB  |
| Peaking | 250 Hz   | 1.41 | 0.1 dB   |
| Peaking | 500 Hz   | 1.41 | 2.1 dB   |
| Peaking | 1000 Hz  | 1.41 | -1.9 dB  |
| Peaking | 2000 Hz  | 1.41 | 4.4 dB   |
| Peaking | 4000 Hz  | 1.41 | -2.7 dB  |
| Peaking | 8000 Hz  | 1.41 | 1.4 dB   |
| Peaking | 16000 Hz | 1.41 | -10.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/Kennerton%20Magister/Kennerton%20Magister.png)