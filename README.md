# Reactive grid system.
> Based on the frameless grid.

This grid system has a variable number of columns based on the viewport:

12 columns when the viewport is 960px or bigger (regular)
8 columns when the viewport is between 640px and 959px (table landscape)
6 columns when the viewport is between 480px and 639px (tablet portrait)
4 columns when the viewport is less or equal than 479px (mobile)

## Usage

    <div class="unit size8of12 size6of8 size4of6 size2of4"> ... </div>

the div is:

- eight columns wide when there are 12 columns
- six columns wide when there are 8 columns
- four columns wide when there are 6 columns
- two columns wide when there are 4 columns
