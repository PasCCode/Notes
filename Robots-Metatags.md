# Robots Meta Tags

```
nosnippet
```

- with this metatag you specify that you don't want to textual snippet shown for this page

```
max-snippet:[number]
```

- specify a maximum text-length, in characters, of a snippet for your page

```
max-video-preview:[number]
```

specify a maximum duration in seconds of an animated video preview

```
max-image-preview:[number]
```

- specify a maximum size of an image preview to be shown for images on this page, using either `none`, `standard` or `large`

- these metatags can be combined, for example
```
<meta name="robots" content="max-snippet:50, max-image-preview:large">
```

***

- it is feasible to limit which part of a page is eligible to be shown as a snippet via the `data-nosnippet` HTML attribute on **span**, **div** and **section** elements
&rarr; with this snipped one can prevent that part of an HTML page from being shown within the textual snippet on the page
