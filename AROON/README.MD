![AROON](image url.png 300H 800W)
# `AROON` [Aroon](AROON)
## Dependencies
### Price 	
* `High` `Low`
### Temporal
* `Alpha`

## Derivatives
* `Highestbars( high, alpha )`		**Offset**(**Highest**)
* `lowestbars( 	low, alpha )`		**Offset**(**Lowest**)

## Determinations
* Indexed
* Range 0 › 100

## Adjustments
* none yet 
// Set Range 0 › 1

## Calculation
//Graphical//
* Aroon Up
```
( Alpha - Offset( Highest ))
———————————————————————————— * 100
		 ( Alpha )
```
* Aroon Down
```
( Alpha - Offset( Lowest ))
———————————————————————————— * 100
		 ( Alpha )
```
//Programmatically//
* Aroon Up
```
((Alpha - Highestbars( high, alpha ))/Alpha) * 100
```
* Aroon Down
```
((Alpha - lowestbars( 	low, alpha ))/Alpha) * 100
```
## Usage
### Trading Type
### Used to detect what ?
### What to look for
### Weaknesses

## Origin
* History
