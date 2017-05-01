# PHP Lessons

This repository contains the __PHP Lessons__ sources for the free programming courses, held at the TU Dresden.

## Slides

The ready-to-go slides can be [found here](http://fsr.github.io/php-lessons/materials.html)
All files are available as `.tex` file in the repository.

## Exercises

Exercises to go along with the courses can be found in the slides itself or on [on GitHub pages](http://fsr.github.io/php-lessons/).
All exercices are related to a lesson. The corresponding PDF is linked automatically at the beginning of every task.

## Contributing

To add new slides, copy the template to the slides folder:
```
cp latex/slides/actual_slide.tex latex/slides/xx_fancy_name.tex
```

After you're done, add the name of the file to the `build_conf.json` to enable automatic building (remember to place a `,` on the line before!).
Also, add the information to the `_data/materials.yml` residing in the __gh-pages__ branch to link it on the _materials overview_.



These lessons are created and maintained by [@manniL](https://github.com/manniL).

