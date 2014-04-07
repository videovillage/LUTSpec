# LUTSpec for UTIs

There are no standard [Uniform Type Identifiers](https://en.wikipedia.org/wiki/Uniform_Type_Identifier) for LUTs.

This is especially problematic because LUTs have various and conflicting file extensions, so extensions alone cannot be used to disambiguate between LUT file formats.

This specification aims to also provide a standard specification for LUTs that developers of applications can use to provide a consistent user experience when opening files on Apple operating systems.

It should also provide enough information to disambiguate file types that share the same extension. It should also provide links to relevant specifications for the file format if available.

## Public LUT UTIs

- **public.plain-text**

  - **public.color-lookup-table** - A base UTI for any type of color lookup table.

    - **public.3d-color-lookup-table** - A [three-dimensional color lookup table](https://en.wikipedia.org/wiki/3D_lookup_table).

      - **com.autodesk.3dl** - Autodesk Lustre 3D LUT - `.3dl`

      - **com.blackmagicdesign.cube** -  DaVinci Resolve Cube LUT - `.cube` - [Adobe Specification (PDF)](http://wwwimages.adobe.com/www.adobe.com/content/dam/Adobe/en/products/speedgrade/cc/pdfs/cube-lut-specification-1.0.pdf)

    - **public.1d-color-lookup-table** - A one-dimensional color lookup table.

      - **com.blackmagicdesign.olut** - DaVinci Resolve 1D LUT - `.olut`

      - **com.discreet.lut** - Discreet 1D LUT - `.lut`


# Contributing

Contributions are welcome. Please open an issue or pull request.
