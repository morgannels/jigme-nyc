+++
date = "2017-09-13"
draft = false
publishdate = "2017-09-13"
title = "Only Black and White?"
description = "Why would someone pay so much money for a camera that doesn't capture color?"
tags = []

[amp]
    elements = ["amp-social-share"]

[structured]
    type = "Article"

[author]
    name = "Morgan Sandquist"

[sitemap]
  changefreq = "monthly"
  priority = 0.5
  filename = "sitemap.xml"

+++

A week and a half ago, I traded in my Leica M (Typ 262, as Leica numbered things for a couple of years, but don’t seem to any longer) and a largish pile of money for a Leica M Monochrom (Typ 246–yes, that’s 16 less). The Monochrom shoots only black and white pictures. Everyone’s reaction so far has been some variation on a head tilt and the not always fully articulated question, “Why?”

It’s a good question. Why would I trade a camera that can shoot in the full range of colors, including of course black and white, and a bunch of money for a camera that only shoots black and white? Is this a case of my having more money than sense? Perhaps. Is it some misguided hipsterish attempt to be different, and by extension superior? Perhaps. Is it a pretentious bid to simplify my photography to its purest essence? Perhaps. But in addition to all of these possibilities, I have another story I tell myself.

First and foremost, black and white pictures are just easier to deal with. I no longer have to worry about avoiding or correcting chromatic aberration, and there’s no more wrestling with white balance. Because I don’t take pictures with any particular end or purpose in mind, I don’t have to justify the results. For me, photography exists entirely in the taking and processing of pictures, so anything that gives me more control (like a rangefinder) or makes it easier (like the absence of color management) makes photography more rewarding for me. Based on the [first set of pictures](https://photos.app.goo.gl/cKjHs0KOZVk730lI2) I’ve taken and processed with the new camera, I’d guess it’ll cut my processing time in half.

Is that mere convenience worth the loss of all color? For me, the answer is a simple yes. But beyond that simple answer, there are a number of technical considerations that might argue convincingly in favor of black and white. The clearest way to summarize those considerations is to say that digital color photography is a barely successful hack. A monochrome digital sensor simply measures the amount of light reaching each photosensor (corresponding to a single pixel in the resulting image). This is relatively objective and efficient. A color digital sensor must measure the amount of light reaching each photosensor (easy) and the color of that light (impossible).

Some of the difficulty in measuring the color of light stems from the inherent, and often unexamined, [fuzziness of color as a concept](https://m.xkcd.com/1882/). I’m aware of at least two ways that manufacturers have attempted to solve the problem of measuring color: placing a grid of colored lenses in front of the sensor; or producing a sensor that determines the color by how deeply the light penetrates. In either case, the amount of light being measured by the photosensor is decreased by passing through a colored lens or by having to penetrate the sensor itself, meaning both methods reduce the efficiency of the sensor.

As to objectivity, both methods end up measuring color in terms of only red, green, and blue, and then algorithmically determining a color. The sensors that measure color based on depth of penetration (red light penetrates to one level, green another, and blue a third) can at least make that determination for each photosensor (or pixel) separately. Because sensors that depend on an array of color lenses can only measure the level of one color (red, green, or blue) at each photosensor, the determination of color can only be made algorithmically across groups of pixels.

Sensors with color arrays suffer from another potential problem. Because the array of colored lenses is generally arranged in a regular pattern, those sensors can produce moire in images of certain sorts of grids and stripes. One way manufacturers have addressed this problem is to place an anti-alias filter in front of the sensor (in addition to the array of colored lenses) in order to slightly blur the image and, ideally, eliminate any moire. Needless to say, this approach isn’t ideal with respect to either efficiency or sharpness. Another way manufacturers (specifically Fujifilm) have addressed this is to make the pattern of colored lenses in the array less obviously regular. This is effective in reducing moire, but it introduces a new set of algorithms to all of the software that must correctly interpret the image data produced by such sensors.

Finally, color sensors are susceptible to chroma noise (in addition to the luminance noise to which all sensors are susceptible), which can give the resulting image an unpleasantly “digital” appearance. Luminance noise on its own only introduces a graininess, which need not be unpleasant. As a result, a black and white sensor can produce perfectly presentable images with an ISO [as high as 12,500](https://photos.app.goo.gl/Jb3fHCCHFVKssTcx2), and likely higher.

In sum, giving up color means also giving up: chromatic aberration; fiddling endlessly with white balance, saturation, and the rest of color management; the application of an unsharp mask (or the removal of moire); and a more limited ISO range. For me, the way I take pictures and what I take them for, this looks like an easy tradeoff to make. Now I’ll see if any of this is borne out in practice.