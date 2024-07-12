### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Design the sets

## Step 1
Let's design the sets! Choose which ``||hoc2024:biome, time, and weather||`` should be displayed for each portion of the show.

#### ~ tutorialhint
You can use a for loop instead of multiple blocks to keep a specific set up for longer.

```ghost
    hoc2024.seta()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc2024.seta(Biome.Biome1, Time.Time0, WeatherA.Weather0)
    hoc2024.seta(Biome.Biome1, Time.Time0, WeatherA.Weather0)
    for (let i = 0; i < 3; i++) {
        hoc2024.seta(Biome.Biome1, Time.Time1, WeatherA.Weather1)
    }
    for (let i = 0; i < 3; i++) {
        hoc2024.seta(Biome.Biome1, Time.Time2, WeatherA.Weather3)
    }
    for (let i = 0; i < 3; i++) {
        hoc2024.seta(Biome.Biome1, Time.Time3, WeatherA.Weather4)
    }
    
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts#v0.0.38
```