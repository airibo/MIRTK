.. Auto-generated by help-rst from "mirtk transform-image -h" output


Applies one or more transformations to an input image. Each voxel center
of the target image is mapped by the composition of the transformations to
the space of the source image. The output intensity for the target voxel is
the source image intensity interpolated at the mapped point and cast to
the output data type. When the input transformation is the identity map,
this command effectively resamples the input image on the finite discrete
grid of the :option:`transform-image -target` image.
