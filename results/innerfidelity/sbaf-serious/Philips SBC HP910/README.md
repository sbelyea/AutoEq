# Philips SBC HP910
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 5.7; 37 5.2; 41 4.4; 45 3.8; 49 3.3; 54 2.5; 60 2.0; 66 1.8; 72 1.2; 79 1.4; 87 1.1; 96 -0.1; 106 -0.7; 116 -1.1; 128 -1.4; 141 -1.5; 155 -1.5; 170 -1.2; 187 -1.3; 206 -1.2; 227 -1.0; 249 -0.7; 274 -0.4; 302 -0.1; 332 0.2; 365 0.5; 402 0.9; 442 1.2; 486 1.2; 535 1.3; 588 1.1; 647 1.9; 712 1.2; 783 1.0; 861 0.5; 947 0.2; 1042 -0.2; 1146 -0.3; 1261 -0.6; 1387 -0.7; 1526 -0.8; 1678 -1.3; 1846 -1.8; 2031 -2.0; 2234 -3.2; 2457 -4.0; 2703 -5.0; 2973 -5.5; 3270 -4.1; 3597 -2.0; 3957 -1.0; 4353 -0.1; 4788 -4.1; 5267 -3.1; 5793 0.2; 6373 -3.2; 7010 -6.6; 7711 -7.5; 8482 -8.5; 9330 -5.6; 10263 -0.1; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 0.0; 18182 0.0; 20000 -0.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Philips SBC HP910 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Philips SBC HP910 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc       |     Q | Gain     |
|:--------|:---------|:------|:---------|
| Peaking | 28 Hz    |  1.11 | 6.8 dB   |
| Peaking | 2530 Hz  |  0.59 | -5.5 dB  |
| Peaking | 2880 Hz  |  3.66 | -3.6 dB  |
| Peaking | 3307 Hz  |  0.22 | 3.6 dB   |
| Peaking | 8048 Hz  |  2.22 | -10.6 dB |
| Peaking | 163 Hz   |  1.3  | -2.0 dB  |
| Peaking | 538 Hz   |  1.82 | 0.9 dB   |
| Peaking | 4786 Hz  |  2.85 | 3.3 dB   |
| Peaking | 4935 Hz  |  7.27 | -6.9 dB  |
| Peaking | 10346 Hz | 10.9  | 2.1 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Philips%20SBC%20HP910/Philips%20SBC%20HP910.png)