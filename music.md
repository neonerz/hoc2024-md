### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Music

## Step 1
Let's create music! First select an ``||hoc2024:instrument||`` and a ``||hoc2024:drum||`` beat. Then use the ``||hoc2024:keys||`` block to create the song. 

#### ~ tutorialhint
You can switch the ``||hoc2024:instrument||`` and/or ``||hoc2024:drum||`` at any time by adding a new one to your sequence.

```ghost
    hoc2024.instrument()
    hoc2024.key()
    hoc2024.drums()
    for (let i = 0; i < 5; i++) {}
```
```template
    hoc2024.instrument(Instruments.Piano)
    hoc2024.drums(Drums.Medium)    
    hoc2024.key(Keys.Do)
    hoc2024.key(Keys.Re)
    hoc2024.key(Keys.Mi)
    hoc2024.instrument(Instruments.Guitar)
    hoc2024.drums(Drums.Fast)  
    for (let i = 0; i < 5; i++) {
        hoc2024.key(Keys.Fa)
    }  
    hoc2024.key(Keys.So)
    hoc2024.key(Keys.La)
    hoc2024.key(Keys.Ti)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts#v0.0.32
```