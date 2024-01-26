# ASCII Versius
This repo contains ASCII art of the Versius robotic system for minimally invasive surgery, manufactured by CMR Surgical. The designs were created by Emma Rhodes and John Till, and are made available here for fair use. This is *not* an official product, and not approved in any official capacity by CMR. Any use should respect CMR's ownership of the Versius brand.

## Mugs
![Rendered preview of a mug](./previews/mug_preview.png "So cool!")

The ASCII art was used to produce a batch of mugs via VistaPrint. [ascii_versius_mug.png](./png/ascii_versius_mug.png) is the starting point for the digital design supplied to the printers. We changed the image colour in the VistaPrint editor to match the mug handle/inner colours as closely as possible.  For the non-black monochrome mugs we used:

- Orange `#FF7A00`
- Blue `#125E94`
- Red `#F63A2E`
- Pink `#F87B72`

There will always be some difference once the mugs are printed, for example our orange wasn't quite as bright as the mug interior.
We also created colour variations, such as [ascii_versius_mug_pride_progress.png](./png/ascii_versius_mug_pride_progress).

One of the learnings is that printing on black mugs uses a different printing process, where the image is printed on a white background and the black is filled in during printing. This introduces a risk that the background will bleed into the image, so the lines are thicker and brighter in the digital image to compensate. The dark SVG and PNG files in this repo take this into account, for example [ascii_versius_mug_darkmode.png](./png/ascii_versius_mug_darkmode).

![Rendered preview of a darkmode mug](./previews/mug_preview_darkmode.png "This took some learning and perseverence :)")

## Instruments

There are arm variations with different instruments. We started with [grasper](./txt/ascii_versius_mug.txt), then added [hook](./txt/hook.txt). We haven't included SVGs and PNGs for all the instrument variations in all the colour variations (e.g. no rainbow hook) but the SVGs can be edited with the contents of the text files.

## Font
The image requires a monospace font which supports a few unicode symbols used in the design (no, it isn't technically ASCII art). We used [Victor Mono](https://rubjo.github.io/victor-mono/) since it is licensed under the permissive Open Font License, and looks good!

![Rendered preview of a progress pride mug](./previews/mug_preview_pride.png "Nice mugshot")

### Line Spacing (why do the preview images look different?)

The preview images are based on the [earlier versions](./png/originals/) of the design which used 1.30 line spacing. The current design uses 1.20 spacing.

## Result

![Photo of three mugs](./photos/matching_trim_colours.png "Collect them all to form the whole picture")

![Photo of a darkmode mug with tea steeping](./photos/darkmode_cuppa.png "Now that's a nice cuppa")

![Photo of a progress-pride mug](./photos/progress_hook.png "Proud of the progress")
