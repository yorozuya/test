Testing RestructuredText
========================

# Superscripts and subscripts

  H<sup>2</sup>O using `<sup><\sup>` tags.

  E = |mc2|
  
  water is |H2O|.


.. |H2O| replace:: H\ :sub:`2`\ O

.. |mc2| replace:: mc\ :sup:`2`


.. code:: python

  def foo(bar):
    return bar

More text following the code block.
