# tf-cg-illust-classifier

This model can be used in Keras or Tensorflow.js to classify images about Cinderella Girls into illustrations or others.

Example: https://arisucool.github.io/tf-cg-illust-classifier/index.html


## Notes

* This repository and model does not contain any copyright material (e.g, illustrations, photos).

* This model was generated for the purpose of extracting illustrations about Arisu. We don't guarantee that it is suitable for other idols.

* Currently Limitations:

    * Images of U149 official comics and シンデレラガールズ劇場 are classified as fan_illust.

## Classification labels

1. `not_illust`
    * Photos and game screenshots are classified.
2. `official_illust`
    * In-game idol illustrations, screenshots of MV, and other official illustrations are classified.
3. `fan_illust`
    * Illustrations made by the fans are classified.


## License

Copyright (C) 2020 arisu.cool 🍓 Project (https://github.com/arisucool/).

This model is released under the MIT License, see [LICENSE](https://github.com/arisucool/tf-cg-illust-classifier/blob/master/LICENSE) for details.
