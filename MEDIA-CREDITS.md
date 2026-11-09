# Media sources and equation conventions

## Photographs

- `assets/potentiometer.jpg`: “Potentiometer.jpg”, Iainf, Wikimedia Commons. Source: https://commons.wikimedia.org/wiki/File:Potentiometer.jpg . Reused under CC BY 2.5: https://creativecommons.org/licenses/by/2.5/ . Original file unchanged; scaled for display.
- `assets/strain-gauge.jpg`: “Strain gauge.jpg”, Bryan Tong Minh, Wikimedia Commons. Source: https://commons.wikimedia.org/wiki/File:Strain_gauge.jpg . Reused under CC BY-SA 3.0: https://creativecommons.org/licenses/by-sa/3.0/ . Original file unchanged; scaled for display. This licence applies to this photograph, not to unrelated lesson files.

## Original teaching media

The SVG diagrams, PNG posters, GIFs and MP4s were created for SenseLab. They are schematic teaching illustrations, not photographs or physical measurement recordings. Deformation is exaggerated for visibility; numerical readings use the explicitly stated ideal models. Each animation has native pause/seek controls and an adjacent text description. No sound or autoplay is used. GIF versions can be downloaded from the relevant chapter.

- `voltage-divider.svg`: two equal series resistors, with a high-input-resistance meter.
- `potentiometer-cutaway.svg`: three-terminal uniform track with wiper position measured from the 0 V end.
- `loaded-divider.svg`: load connected in parallel with the lower track.
- `measurement-chain.svg`: beam → gauges → bridge → amplifier → ADC → calibrated result.
- `potentiometer-motion.*`: 100 mm track, 10 V, no output loading.
- `strain-motion.*`: 100 mm initial length, 0–500 microstrain, R0 = 120 ohms, GF = 2.
- `cantilever-load.*`: illustrative bending activity with epsilon magnitude 1 microstrain/g and full-bridge sensitivity 0.010 mV/g at 5 V, GF = 2. This is not a universal beam relation.

## External video

Videos are embedded or linked from the creator; their media has not been downloaded or redistributed.

- The Engineering Mindset: “How Potentiometer Works”, https://www.youtube.com/watch?v=Xb-MZMoUtcQ . A privacy-enhanced YouTube embed is loaded only on click. Creator's companion page: https://theengineeringmindset.com/potentiometers-explained/ . Embedding or playback may depend on the viewer's region, browser, network and creator's settings. A direct link is provided.
- Texas Instruments: “Bridge amplifier circuit”, https://www.ti.com/video/6130991294001 . Opens on TI's website.

## Equation verification

Manufacturer reference: NI, “Measuring Strain with Strain Gages”, https://www.ni.com/en/shop/data-acquisition/sensor-fundamentals/measuring-strain-with-strain-gages.html . Different publications may number bridge arms differently; follow the on-page diagram.

The displayed equations use native MathML, which works offline in modern browsers without a library. R0 and L0 are original resistance and length. Bridge output is right midpoint minus left midpoint. Quarter-bridge exact output is Vs*d/[2*(2+d)], d = GF*epsilon, with R1 = R0*(1+d). Its small-strain approximation is Vs*d/4. Half/full outputs are Vs*d/2 and Vs*d for the specified equal tension/compression arrangements, assuming linear resistance response. Common thermal-factor cancellation is shown at zero mechanical strain. The laboratory model is deliberately ideal and explicitly labelled.
