# OpenColor
OpenColor.jl provides minimalistic RGB color definition from [Open color](https://yeun.github.io/open-color/)

## Installation

```
julia> using Pkg; Pkg.add("OpenColor")
```

## Quickstart

```
julia> using OpenColor

julia> typeof(OCGRAY[0])
ColorTypes.RGB{Float64}

julia> @show OCGRAY[0]
OCGRAY[0] = RGB{Float64}(0.9725490196078431,0.9764705882352941,0.9803921568627451)
```

## Available Colors

Check https://yeun.github.io/open-color/.

OpenColor is based on open color v1.7.0.

## Exported Names
### Rule
* prefix "OC" is added to color name

### List
* OCGRAY, OCRED, OCPINK, OCGRAPE, OCVIOLET, OCINDIGO, OCBLUE, OCCYAN, OCTEAL, OCGREEN, OCYELLOW, OCORANGE
