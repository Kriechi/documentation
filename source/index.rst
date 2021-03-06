python-hyper: Low-Level HTTP-related Libraries for Python
=========================================================

Hyper is a set of related projects that provide HTTP/2 functionality to Python
projects. The aim is to provide a complete HTTP and HTTP/2 toolbox, ranging
from complete off-the-shelf solutions to projects that solve individual
specific problems. Developers should be able to compose these solutions
together to fit their specific use-cases, using the general-purpose code where
appropriate and writing code to well-defined interfaces where they have
specific requirements.

The hyper project is comprised of the following sub-projects:

- `hyper-h2`_, a complete HTTP/2 protocol stack that does not perform any I/O,
  intended to be independent of framework.
- `hyperframe`_, a HTTP/2 framing layer.
- `hpack`_, a HPACK implementation in pure-Python.
- `brotlipy`_, a CFFI-based library for Brotli compression.
- `priority`_, a Python implementation of the HTTP/2 Priority tree.
- `wsproto`_, an implementation of the WebSocket protocol that, like
  `hyper-h2`_, does not perform any I/O.

Please follow the links above for more details on each of those sub-projects.
The rest of this documentation applies to the project as a whole.

Contents
--------

.. toctree::
   :maxdepth: 2

   contributing
   one-of-the-team
   security


.. _brotlipy: https://python-hyper.org/projects/brotlipy/en/stable
.. _hpack: https://python-hyper.org/projects/hpack/en/stable
.. _hyper-h2: https://python-hyper.org/projects/hyper-h2/en/stable
.. _hyperframe: https://python-hyper.org/projects/hyperframe/en/stable
.. _priority: https://python-hyper.org/projects/priority/en/stable
.. _wsproto: https://python-hyper.org/projects/wsproto/en/stable
