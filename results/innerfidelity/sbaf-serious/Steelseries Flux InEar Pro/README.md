# Steelseries Flux InEar Pro
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.0dB
GraphicEQ: 21 0.0; 23 1.4; 25 1.4; 28 1.3; 31 1.2; 34 1.0; 37 1.0; 41 0.8; 45 0.7; 49 0.6; 54 0.3; 60 0.1; 66 -0.2; 72 -0.6; 79 -0.9; 87 -1.4; 96 -1.8; 106 -2.1; 116 -2.3; 128 -2.5; 141 -2.8; 155 -2.9; 170 -3.1; 187 -3.1; 206 -3.1; 227 -2.9; 249 -2.9; 274 -2.7; 302 -2.5; 332 -2.2; 365 -1.9; 402 -1.7; 442 -1.2; 486 -1.0; 535 -0.7; 588 -0.1; 647 0.2; 712 0.4; 783 0.7; 861 0.5; 947 0.2; 1042 -0.2; 1146 -0.5; 1261 -0.9; 1387 -1.5; 1526 -2.1; 1678 -2.5; 1846 -2.6; 2031 -2.7; 2234 -2.4; 2457 -1.2; 2703 0.1; 2973 2.1; 3270 4.1; 3597 4.3; 3957 2.4; 4353 -0.7; 4788 -0.4; 5267 3.3; 5793 5.8; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Steelseries Flux InEar Pro GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-59**.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Steelseries Flux InEar Pro ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 27 Hz    | 0.62 | 1.5 dB  |
| Peaking | 179 Hz   | 0.7  | -3.4 dB |
| Peaking | 1951 Hz  | 1.96 | -3.2 dB |
| Peaking | 3380 Hz  | 4.35 | 5.3 dB  |
| Peaking | 6062 Hz  | 4.49 | 6.6 dB  |
| Peaking | 787 Hz   | 2.71 | 1.3 dB  |
| Peaking | 1468 Hz  | 5.01 | -0.7 dB |
| Peaking | 4564 Hz  | 5.99 | -4.8 dB |
| Peaking | 4600 Hz  | 2.46 | 2.1 dB  |
| Peaking | 22050 Hz | 1.71 | 0.3 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Steelseries%20Flux%20InEar%20Pro/Steelseries%20Flux%20InEar%20Pro.png)