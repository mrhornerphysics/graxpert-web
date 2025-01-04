---
title: What are Gradients?
weight: 1
---

{{% pageinfo color="warning" %}}
Translation Needed
{{% /pageinfo %}}


Gradients are, as the name suggests, gradual brightness progressions that are not part of astrophotography, but are caused by external interference. 
Causes can be, for example, light pollution or incorrect or missing flat correction, but also natural brightness gradients of the night sky, as well as peculiarities of the optics used (shading in the form of a vignette).
In order to edit deep sky photos, it makes sense to remove such gradients from the images. This not only looks better, but also makes further editing of the image easier. Color casts can also be removed in this way and it
generally makes sense to free the astrophoto from the amount of the sky background.

In short: Gradient removal is very useful, almost absolutely necessary. Various paid astro software offers very good tools for gradient removal such as PixInsight (DBE, ABE) or AstroPixelProcessor. You can also purchase
paid plug-ins for the Adobe Photoshop or Affinity Photo software to solve the problem. GraXpert is freely available open source software that was programmed exclusively for these purposes. It works stand alone, not as a
plug-in for any other software.

{{< cardpane >}}
  {{< card >}}
    {{% imgproc M81_mit_gradient.jpg Fill "473x314" %}}
    {{% /imgproc %}}
    Im Bild ist ein deutlicher Farbgradient zu erkennen.
    Der untere Teil des Bildes weist einen roten Farbton auf, während der obere Teil grünlich gefärbt ist.
  {{< /card >}}
  {{< card >}}
    {{% imgproc M81_ohne_gradient.jpg Fill "473x314" %}}
    {{% /imgproc %}}
    Im Bild ist der Gradient nach Anwendung von GraXpert vollständig entfernt.
  {{< /card >}}
{{< /cardpane >}}
