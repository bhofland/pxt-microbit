# Smiley Knoppen

## Stap 1

Plaats een ``||input:on button pressed||`` blok om code uit te voeren wanneer knop **A** wordt ingedrukt.

```blocks
input.onButtonPressed(Button.A, () => { 
});
```

## Stap 2

Plaats een ``||basic:show leds||`` blok binnen ``||input:on button pressed||``
om een smiley op het scherm te laten zien.

```blocks
input.onButtonPressed(Button.A, () => { 
    basic.showLeds(`
        # # . # #
        # # . # #
        . . . . .
        # . . . #
        . # # # .`
        );
});
```

## Stap 3

Klik ``|Download|`` om je code naar je @boardname@ te sturen druk op **A**.

## Stap 5

Voeg ``||input:on button pressed||`` en ``||basic:show leds||`` blokken toe om
een verdrietige smiley te laten zien wanneer **B** ingedrukt wordt.

```blocks
input.onButtonPressed(Button.B, () => { 
    basic.showLeds(`
        # # . # #
        # # . # #
        . . . . .
        . # # # .
        # . . . #`
        );
});
```

## Stap 5

Klik ``|Download|`` om je code naar je @boardname@ sturen probeer de knoppen **A** en **B**.

## Stap 6

Voeg een geheime modus toe wanneer ``A`` and ``B`` tegelijk worden ingedrukt. 
Voeg meerdere ``||basic:show leds||`` blokken toe om een animatie te creëren.

```blocks
input.onButtonPressed(Button.AB, () => {
    basic.showLeds(`
        . . . . .
        # . # . .
        . . . . .
        # . . . #
        . # # # .
        `)
    basic.showLeds(`
        . . . . .
        . . # . #
        . . . . .
        # . . . #
        . # # # .
        `)    
})
```

## Stap 7

Klik op ``|Download|`` om je code naar je @boardname@ te sturen.
