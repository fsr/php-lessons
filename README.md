# PHP Lessons

This repository contains the __PHP Lessons__ sources for the free programming courses, held at the TU Dresden.

Exercises to go along with the courses can be found [on GitHub pages](http://fsr.github.io/php-lessons/) or on the `gh-pages` branch of this repository as Markdown sources.


### Teaching

The `tex` files are automatically rendered and can be found (SOON) at:
[http://fsr.github.io/php-lessons/materials.html](http://fsr.github.io/php-lessons/materials.html)

Almost every task is linked to a lesson. The corresponding PDF is linked automatically at the beginning of every task.


### Contributing

To add new slides, copy the template to the slides folder:
```
cp latex/actual_slide.tex latex/xx_fancy_name.tex
```

After you're done, add the name of the file to the `build_conf.json` to enable automatic building (remember to place a `,` on the line before!).
Also, add the information to the `_data/materials.yml` residing in the __gh-pages__ branch to link it on the _materials overview_.



These lessons are created and maintained by [@maniL](https://github.com/manniL).

