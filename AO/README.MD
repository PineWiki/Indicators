![AO](image url.png 300H 800W)
# `AO` [Awesome Oscillator](AO)
## Dependencies
### Price 	
* `High` `Low`
### Temporal
* `Alpha`
* `Beta`

## Derivatives
* `( High + Low ) / 2`	**Mean**(**Spread**)

## Determinations
* oscillator non Indexed
* Range x ‹ 0 › x

## Adjustments
* none
// Index Range -1 ‹ 0 › 1 

## Calculation
//Graphical//
```
sma(**Mean**(**Spread**), Alpha) - sma(**Mean**(**Spread**), Beta)
```
//Programmatically//
```
sma(hl2, Alpha) - sma(hl2, Beta)
```
## Usage
### Trading Type
### Used to detect what ?
### What to look for
### Weaknesses

## Origin
* History
