# Mixin Compass Sprite Retina

This is a simple mixin to build sprites and yours css classes.

## Requirement

`Sass` and `Compass`

## Usage

    // Import
    @import mixin-sprite-retina

    // Some Icons
    $some-map: sprite-map('sprites/some/*.png')
    $some-map-retina: sprite-map('sprites/some2x/*.png')
    +generate-sprites('some', $some-map, $some-map-retina)

Your HTML:

    <i class="some-stuff"></i>
    
## Contributors

 - [Thiago Lagden](https://github.com/lagden)
 
:beers:
