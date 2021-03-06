# HiSoundAudio Hiphone HP4
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 -10.0; 23 -10.1; 25 -10.1; 28 -10.2; 31 -10.2; 34 -10.2; 37 -10.3; 41 -10.3; 45 -10.4; 49 -10.4; 54 -10.5; 60 -10.7; 66 -10.8; 72 -10.9; 79 -11.1; 87 -11.3; 96 -11.4; 106 -11.3; 116 -11.2; 128 -11.2; 141 -11.0; 155 -10.8; 170 -10.5; 187 -10.1; 206 -9.7; 227 -9.2; 249 -8.7; 274 -8.1; 302 -7.4; 332 -6.7; 365 -6.0; 402 -5.3; 442 -4.5; 486 -3.9; 535 -3.2; 588 -2.2; 647 -1.6; 712 -1.0; 783 -0.3; 861 -0.2; 947 -0.0; 1042 0.1; 1146 0.1; 1261 0.4; 1387 0.6; 1526 1.2; 1678 1.6; 1846 2.2; 2031 2.7; 2234 1.1; 2457 1.8; 2703 3.2; 2973 4.9; 3270 5.8; 3597 6.0; 3957 5.0; 4353 2.7; 4788 1.5; 5267 0.8; 5793 -1.2; 6373 -4.8; 7010 -2.8; 7711 0.1; 8482 0.0; 9330 0.0; 10263 0.0; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 -0.9; 18182 -0.5; 20000 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`HiSoundAudio Hiphone HP4 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `HiSoundAudio Hiphone HP4 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.9dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 26 Hz    | 0.22 | -9.6 dB |
| Peaking | 142 Hz   | 0.65 | -6.2 dB |
| Peaking | 304 Hz   | 1.11 | -3.3 dB |
| Peaking | 3408 Hz  | 1.45 | 6.0 dB  |
| Peaking | 6425 Hz  | 4.6  | -6.1 dB |
| Peaking | 482 Hz   | 5.34 | -0.6 dB |
| Peaking | 1971 Hz  | 1.86 | 2.3 dB  |
| Peaking | 2398 Hz  | 3.43 | -3.0 dB |
| Peaking | 3545 Hz  | 4.29 | 0.2 dB  |
| Peaking | 17442 Hz | 4.76 | -1.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/HiSoundAudio%20Hiphone%20HP4/HiSoundAudio%20Hiphone%20HP4.png)