# AudioFly AF160
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 4.6; 25 4.4; 28 4.3; 31 4.1; 34 4.0; 37 3.9; 41 3.7; 45 3.5; 49 3.3; 54 3.0; 60 2.7; 66 2.4; 72 2.1; 79 1.7; 87 1.3; 96 0.9; 106 0.6; 116 0.3; 128 -0.0; 141 -0.3; 155 -0.6; 170 -0.8; 187 -0.8; 206 -0.9; 227 -0.9; 249 -1.0; 274 -0.9; 302 -0.8; 332 -0.7; 365 -0.7; 402 -0.5; 442 -0.2; 486 -0.2; 535 0.0; 588 0.5; 647 0.6; 712 0.7; 783 0.8; 861 0.5; 947 0.2; 1042 -0.2; 1146 -0.5; 1261 -0.8; 1387 -1.3; 1526 -1.8; 1678 -2.0; 1846 -1.7; 2031 -1.3; 2234 -0.6; 2457 0.7; 2703 1.7; 2973 3.1; 3270 3.8; 3597 3.2; 3957 3.8; 4353 5.6; 4788 6.0; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`AudioFly AF160 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `AudioFly AF160 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 20 Hz   | 0.68 | 4.2 dB  |
| Peaking | 52 Hz   | 0.87 | 2.0 dB  |
| Peaking | 207 Hz  | 1.07 | -1.3 dB |
| Peaking | 1713 Hz | 2.55 | -2.8 dB |
| Peaking | 4867 Hz | 1.41 | 6.5 dB  |
| Peaking | 738 Hz  | 1.81 | 1.3 dB  |
| Peaking | 2044 Hz | 0.17 | -0.4 dB |
| Peaking | 3052 Hz | 4.7  | 2.1 dB  |
| Peaking | 6384 Hz | 3.73 | 4.2 dB  |
| Peaking | 7213 Hz | 1.66 | -2.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/AudioFly%20AF160/AudioFly%20AF160.png)