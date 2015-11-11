# tres_gen - Acceleo MOFM2T transformation to generate T-Res blocks in Simulink automatically

tres_gen is a model-to-text transformation written in Acceleo, that annotates a Simulink model with T-Res blocks from a SW implementation model in SysML. tres_gen parses a SW implementation model defined using the mapping profile in [cypbd_mapping](https://github.com/m-morelli/cypbd_mapping). Next, it generates automatically a set of Matlab script with model construction commands to recreate that model of the SW implementation in Simulink, using blocks from the [tres_bundle](https://github.com/m-morelli/tres_bundle) toolbox.

*tres_gen is in the early phases of development. Only blocks representing the real-time kernel and tasks can be automatically generated. Support for blocks representing networks and messages are still in progress.*

# Note on Licensing

tres_gen is released under the terms of the permissive, industry-friendly 3-Clause BSD License.
