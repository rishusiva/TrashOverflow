#clean-dirty-garbage-containers-in-montevideo

This dataset contain manually curated images from clean and dirty containers from Montevideo. Most of them were photos taken in the street and contributed by several people, 
but there are also images take from news, Twitter, Facebook and Google Street View.

Dirty containers present different levels of dirtiness, but they are not distinguished.

first version: 19/05/2020
contact: r.laguna.queirolo@outlook.com

## Change log
20/05/2020 - Include more training samples
12/09/2020 - Include more training (+676) & testing (+64) samples: 
    * train/clean from 574 to 1005 (+431)
    * train/dirty from 365 to 610 (+245)
    * test/clean from 100 to 128 (+28)
    * test/dirty from 100 to 136 (+36)

21/12/2020 - Include more training (+367) & testing (+794) samples, including ~400 samples provided by pormibarrio.uy: 
    * train/clean from 1005 to 1111 (+106)
    * train/dirty from 610 to 871 (+261)
    * test/clean from 128 to 535 (+407)
    * test/dirty from 100 to 487 (+387)

14/02/2021 - Include more training (+239) & testing (+178) samples: 
    * train/clean from 1111 to 1206 (+95)
    * train/dirty from 871 to 1015 (+144)
    * test/clean from 535 to 600 (+65)
    * test/dirty from 487 to 600 (+113)

17/02/2021 - Remove corrupted files and not related images, training (-4) & testing (-5) samples: 
    * train/clean are still 1206 (-)
    * train/dirty from 1015 to 1011 (-4)
    * test/clean are still 600 (-)
    * test/dirty from 600 to 595 (-5)
    Add annotations in Pascal VOC format for object detection task, one xml file for each image. All containers are labeled simply as `container`, and they are under `annotations` folder.
