# BibTeXML2DocBook ATL transformation

[Link - ATL Zoo](https://www.eclipse.org/atl/atlTransformations/#BibTeXML2DocBook)

Original valid transformation: ``BibTeXML2DocBook.atl``  
Input metamodel: ``BibTeX.ecore``  
Output metamodel: ``DocBook.ecore``  

* ``input_models/`` contains 4 models conforming to ``BibTeX.ecore`` in XMI format
* ``expected_output_models/`` contains 4 models conforming to ``DocBook.ecore`` in XMI format. They correspond to the models obtained after applying the orginal valid transformation on the input models.
* ``faulty_transformations/`` contains 20 versions of the original valid transformation in which 2 to 5 mutations were applied.
