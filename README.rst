Sentry Sphinx Extension
=======================

This repository contains sphinx support for embedding the documentation.

To use it, put this at the end of the `conf.py`:

.. sourcecode:: python

    sys.path.insert(0, os.path.abspath('_sentryext'))
    import sentryext
    sentryext.activate()
