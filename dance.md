### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choreograph a Dance

## Step 1
Let's dance! Sequence together your ``||hoc2024:dance steps||`` to create a dance for the Agent to do.

#### ~ tutorialhint


```ghost
    hoc2024.dances()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc2024.dances(Dances.Move2)
    hoc2024.dances(Dances.Move2)
    hoc2024.dances(Dances.Move2)
    hoc2024.dances(Dances.Move1)
    hoc2024.dances(Dances.Move1)
    for (let i = 0; i < 3; i++) {
        hoc2024.dances(Dances.Move12)
    }
    hoc2024.dances(Dances.Move8)
    hoc2024.dances(Dances.Move8)
    hoc2024.dances(Dances.Move11)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts#v0.0.38
```