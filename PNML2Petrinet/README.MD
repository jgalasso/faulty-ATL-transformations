# PNML2Petrinet ATL transformation

Original valid transformation: ``PNML2PetriNet.atl``  
Input metamodel: ``PNML.ecore``   
Output metamodel: ``PetriNet.ecore``   

* ``input_models/`` contains 4 models conforming to ``PNML.ecore`` in XMI format
* ``expected_output_models/`` contains 4 models conforming to ``PetriNet.ecore`` in XMI format. They correspond to the models obtained after applying the orginal valid transformation on the input models.
* ``faulty_transformations/`` contains 18 versions of the original valid transformation in which 1 to 5 mutations were applied.
