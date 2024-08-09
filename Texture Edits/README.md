# Texture Edits

To apply a texture, choose a horse fom the game and rename the new textures to replace the ones you are modifying, then modify `horses.xml` as needed.

Files to know about include:

- `Bella Sara\Common\Metagame\horses.xml` contains most of the horse data such as the hair colour, size, stats and texture names
  - Caution!: Leave the ability names as-is since these are used to unlock the different gates!
  - The hair (tail) colour can be Brown, Red, Black or White (which appears grey). Hex codes do not seem to work, and other colour names seem to result in a missing texture.
- `Bella Sara\Win32\Models\Textures\BellaHorseTextures` contains the horse (body) and tack textures. Note that this folder also includes unused tack textures (the ones ending in '_0' are the ones used in game)
- `Bella Sara\Win32\Models\Textures` contains the mane and gate textures
  - Note that whichever texture is used for 'Thunder's' mane will also appear as feathering on 'Thunder's' model and will also be used as 'Jewel's' forelock
- `Bella Sara\Common\Graphics\Effects` contains the particle effects (bella_effect, fiona_effect, jewel_effect, Petals_effect and thunder_effect).
