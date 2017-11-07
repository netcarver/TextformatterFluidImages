TextformatterFluidImages
========================

A textformatting module for ProcessWire that strips the height attribute from any ```<img>``` tag and adds a
configurable CSS class. By default, the class ```image-width-control``` will be used.

To complete making the image tags fluid, add the following to your stylesheet

    .image-width-control {
      max-width:100%;
    }



Credits
-------

This is based upon the [RemoveHeights textformatter](https://gihub.com/ocorreiododiogo/PW-removeHeights) by Diogo Oliveira.
