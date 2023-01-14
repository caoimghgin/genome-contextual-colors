# genome-contextual-colors
Contextual colors allows the creation of white-label design system components and supports dark-mode. Unfortunately, there is no unified standard on how to name these colors. Using the genome color optimization and semantic+weighted palettes, this is an attempt to find common ground and begin a community-wide process of participation to achieve standardization.

#RULES
1. All colors (palette and contextul) are prefixed with a two to three alpha representation of the design system name. Here, we'll prefix with 'Genome' or gnm.
2. Pallete colors are identified with [prefix]-'palette', or 'gnm-palette'. Pallete colors should not be directly referenced in components (should not see 'gnm-palette')
3. Contextual colors are identified with [prefix]-'color', or 'gnm-color' and are preferred for consumption by components for white-label and mode support.