Installation
------------
.. warning::
   Ensure that the :ref:`pre-requisites` from the previous section
   have been performed, checked and tested before proceeding.

.. note:: The library has been tested against Python 2.7, 3.4, 3.5 and 3.6.

   For **Python3** installation, substitute the following in the
   instructions below.

   * ``pip`` ⇒ ``pip3``,
   * ``python`` ⇒ ``python3``,
   * ``python-dev`` ⇒ ``python3-dev``,
   * ``python-pip`` ⇒ ``python3-pip``.

   It was *originally* tested with Raspbian on a rev.2 model B, with a vanilla
   kernel version 4.1.16+, and has subsequently been tested on Raspberry Pi
   (both Raspbian Jessie and Stretch) models A, B2, 3B, Zero, Zero W and
   OrangePi Zero (Armbian Jessie).

Install the latest version of the library directly from PyPI_::

  $ sudo apt install python-dev python-pip libfreetype6-dev libjpeg-dev build-essential libopenjp2-7 libtiff5
  $ sudo -H pip install --upgrade luma.oled

If you are upgrading from a previous version, make sure to read the
:doc:`upgrade <upgrade>` document.

.. _PyPI: https://pypi.python.org/pypi?:action=display&name=luma.oled
