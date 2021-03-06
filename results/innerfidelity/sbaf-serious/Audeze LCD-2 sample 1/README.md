# Audeze LCD-2 sample 1
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.5dB
GraphicEQ: 21 0.0; 23 5.8; 25 5.5; 28 5.2; 31 5.1; 34 5.1; 37 5.1; 41 5.0; 45 5.0; 49 4.8; 54 4.5; 60 4.1; 66 3.4; 72 3.0; 79 2.9; 87 2.6; 96 2.4; 106 2.2; 116 2.0; 128 1.8; 141 1.6; 155 1.4; 170 1.3; 187 1.1; 206 1.0; 227 1.0; 249 0.8; 274 0.7; 302 0.7; 332 0.5; 365 0.4; 402 0.4; 442 0.3; 486 0.3; 535 0.6; 588 0.6; 647 0.1; 712 -0.2; 783 -0.4; 861 -0.6; 947 -0.6; 1042 0.6; 1146 3.0; 1261 3.7; 1387 3.7; 1526 3.3; 1678 4.6; 1846 6.0; 2031 6.0; 2234 4.7; 2457 4.6; 2703 4.6; 2973 5.6; 3270 6.0; 3597 6.0; 3957 6.0; 4353 6.0; 4788 6.0; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audeze LCD-2 sample 1 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-65**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audeze LCD-2 sample 1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 12 Hz   | 1.1  | 5.9 dB  |
| Peaking | 32 Hz   | 0.36 | 4.6 dB  |
| Peaking | 1864 Hz | 1.58 | 4.9 dB  |
| Peaking | 3736 Hz | 1.55 | 5.2 dB  |
| Peaking | 5741 Hz | 3.09 | 4.6 dB  |
| Peaking | 952 Hz  | 2.46 | -3.5 dB |
| Peaking | 1193 Hz | 1.76 | 3.3 dB  |
| Peaking | 1544 Hz | 4.21 | -2.1 dB |
| Peaking | 6563 Hz | 7.53 | 2.1 dB  |
| Peaking | 7838 Hz | 2.17 | -1.5 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audeze%20LCD-2%20sample%201/Audeze%20LCD-2%20sample%201.png)