# UML2ER ATL transformation

Original valid transformation: ``SimpleUml2ER.atl``  
Input metamodel: ``SimpleUml.ecore``    
Output metamodel: ``ER.ecore``  

* ``input_models/`` contains 4 models conforming to ``SimpleUml.ecore`` in XMI format
* ``expected_output_models/`` contains 4 models conforming to ``ER.ecore`` in XMI format. They correspond to the models obtained after applying the orginal valid transformation on the input models.
* ``faulty_transformations/`` contains 20 versions of the original valid transformation in which 2 to 5 mutations were applied.
