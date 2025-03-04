# CorrectCoxVpulse-a-python-function-to-correct-space-clamp-errors-in-voltage-clamp-experiments
Successful modelling of how neurons integrate their synaptic inputs requires, among other things, knowledge of the voltage-dependence of the kinetic parameters characterising voltage-dependent membrane conductances. In attempting to develop such a model, the natural experimental methodology of choice is the whole-cell voltage-clamp test-pulse experiment. Unfortunately, when applied to neurons, whole-cell voltage-clamp suffers from the problem of poor space clamp. That is, the intracellular voltage is accurately controlled only at the recording/current-injection site. The use of membrane patches (inside-out, outside-out or even, for sufficiently low currents, cell attached) obviates this problem but presents its own difficulties. Therefore whole-cell recording - with an appropriate correction for space-clamp error - is still an invaluable tool for obtaining the data needed for accurate description and modelling of intrinsic signalling processes in neurons. The Python function CorrectCoxVpulse, together with a neuron model implemented in the simulator NEURON, allows for the correction of space-clamp errors in voltage-clamp test-pulse experiments. Details of the algorithm and an application can be found in: Murphy R., Alle H., Geiger J. and Storm J. (2025) "The Kv7/KCNQ/M current in hippocampal mossy fiber axons: I correction of space-clamp errors in voltage-clamp experiments", The Journal of Physiology (submitted). Their V-clamp data are provided as a .ZIP files (MFB1.zip etc.), as is CorrectCoxVpulse and its associated example files (see the .PDF documentation).
