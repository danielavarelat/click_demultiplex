# click_demultiplex

[![pypi badge][pypi_badge]][pypi_base]
[![travis badge][travis_badge]][travis_base]
[![codecov badge][codecov_badge]][codecov_base]

Command Line Tool to Demultiplex a paired-end fastq file into several fastq files, based on unique barcodes.

## Features

* 📦 &nbsp; **Easy Installation**

        pip install click_demultiplex

* 🍉 &nbsp; **Usage Documentation**

        click_demultiplex --help

* 🐳 &nbsp; **Containers Support**

        # docker usage
        docker run --volume /shared_fs:/shared_fs --interactive --tty \
            click_demultiplex-image
            [click_demultiplex options]

        # singularity usage
        singularity run --workdir /shared_fs/tmp --bind /shared_fs:/shared_fs \
            click_demultiplex-singularity-image-path
            [click_demultiplex options]

## Contributing

Contributions are welcome, and they are greatly appreciated, check our [contributing guidelines](.github/CONTRIBUTING.md)!

## Credits

This package was created using [Cookiecutter] and the
[leukgen/cookiecutter-toil] project template.

<!-- References -->
[singularity]: http://singularity.lbl.gov/
[docker2singularity]: https://github.com/singularityware/docker2singularity
[cookiecutter]: https://github.com/audreyr/cookiecutter
[leukgen/cookiecutter-toil]: https://github.com/leukgen/cookiecutter-toil

<!-- Badges -->
[codecov_badge]: https://codecov.io/gh/leukgen/click_demultiplex/branch/master/graph/badge.svg
[codecov_base]: https://codecov.io/gh/leukgen/click_demultiplex
[pypi_badge]: https://img.shields.io/pypi/v/click_demultiplex.svg
[pypi_base]: https://pypi.python.org/pypi/click_demultiplex
[travis_badge]: https://img.shields.io/travis/leukgen/click_demultiplex.svg
[travis_base]: https://travis-ci.org/leukgen/click_demultiplex
