![ADL](image url.png 300H 800W)
# `ADL` [Accumulation Distribution](ADL)
## Dependencies
### Price
* `Close` `High` `Low`
### Volume
* `Volume`

## Derivatives
* `High – Close`		**Supra**
* `High – Low`			**Spread**
* `Close – Low`			**Sub**

## Determinations
* oscillator Indexed
* Range -1 ‹ 0 › 1

## Adjustments
* none

## Calculation
//Graphical//
```
( Sub - Spread )
———————————————— * volume
	( Supra )
```
//Programmatically//
```
((Close – Low) – (High – Close)) / (High – Low) * Volume
```
## Usage
### Trading Type
### Used to detect what ?
### What to look for
### Weaknesses

## Origin
* History
https://www.tradingview.com/wiki/Accumulation_Distribution_(ADL)
