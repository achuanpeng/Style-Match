I built Style Match, a single-page app. You upload a raw photo and a stylized reference, and it compares them and suggests edits. It runs entirely in your browser, so your photos are never uploaded anywhere.

What it gives you:
  1. Tone curve: a matched luminance curve plus R/G/B channel curves, drawn on a graph. It also lists nine anchor points (input→output) you can copy into Lightroom or Photoshop.
  2. Light & tone: approximate exposure, contrast, highlights, shadows, whites and blacks. It flags a lifted black point if the reference has a faded or matte look.
  3. White balance & saturation: temperature, tint and overall saturation shifts.
  4. Color mixer: hue, saturation and luminance changes for each of eight color ranges. It only lists colors present in both photos.
  5. Color grading: the tint to add in shadows and highlights, with hue angle and saturation.
  6. Live preview: your raw photo with the matched curves applied, with a strength slider.

How it works:
It matches the histograms of the two images for brightness and for each color channel to get the curves. It then compares average colors in the shadows, highlights and each hue range to get the color suggestions.
