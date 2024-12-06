# art-msra.github.io

Multi-layer image generation is a fundamental task that en-
ables users to isolate, select, and edit specific image layers,
thereby revolutionizing interactions with generative models.
In this paper, we introduce the Anonymous Region Trans-
former (ART), which facilitates the direct generation of
variable multi-layer transparent images based on a global
text prompt and an anonymous region layout. Inspired by
Schema theory1, this anonymous region layout allows the
generative model to autonomously determine which set of
visual tokens should align with which text tokens, which is
in contrast to the previously dominant semantic layout for
the image generation task. In addition, the layer-wise re-
gion crop mechanism, which only selects the visual tokens
belonging to each anonymous region, significantly reduces
attention computation costs and enables the efficient gener-
ation of images with numerous distinct layers (e.g., 50+).
When compared to the full attention approach, our method
is over 12 times faster and exhibits fewer layer conflicts.
Furthermore, we propose a high-quality multi-layer trans-
parent image autoencoder that supports the direct encoding
and decoding of the transparency of variable multi-layer
images in a joint manner. By enabling precise control and
scalable layer generation, ART establishes a new paradigm
for interactive content creation.
