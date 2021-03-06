# Meze 99 Neo with Classic Pads
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 5.9; 49 5.6; 54 4.9; 60 4.4; 66 4.2; 72 4.2; 79 3.8; 87 3.2; 96 2.7; 106 2.4; 116 2.2; 128 1.8; 141 1.4; 155 1.1; 170 1.4; 187 1.2; 206 1.2; 227 1.3; 249 2.1; 274 2.8; 302 3.3; 332 4.0; 365 4.5; 402 4.3; 442 3.6; 486 2.2; 535 1.2; 588 0.6; 647 0.2; 712 -0.2; 783 0.1; 861 0.2; 947 0.1; 1042 -0.2; 1146 -0.1; 1261 0.2; 1387 -0.0; 1526 -0.2; 1678 -0.4; 1846 -0.4; 2031 -0.0; 2234 -0.2; 2457 0.1; 2703 1.3; 2973 1.5; 3270 2.4; 3597 4.0; 3957 4.3; 4353 1.5; 4788 2.0; 5267 5.9; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Meze 99 Neo with Classic Pads GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Meze 99 Neo with Classic Pads ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 31 Hz   | 0.43 | 6.3 dB  |
| Peaking | 366 Hz  | 2.12 | 4.6 dB  |
| Peaking | 3670 Hz | 4.53 | 3.9 dB  |
| Peaking | 5934 Hz | 2.75 | 7.0 dB  |
| Peaking | 7837 Hz | 1.79 | -1.4 dB |
| Peaking | 448 Hz  | 6.92 | 0.8 dB  |
| Peaking | 674 Hz  | 1.98 | -0.6 dB |
| Peaking | 1702 Hz | 4.35 | -0.5 dB |
| Peaking | 2514 Hz | 2.51 | -1.0 dB |
| Peaking | 2719 Hz | 4.27 | 1.5 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Meze%2099%20Neo%20with%20Classic%20Pads/Meze%2099%20Neo%20with%20Classic%20Pads.png)