# Yosys Open Road Plugins

This repository contains plugins for
[Yosys](https://github.com/YosysHQ/yosys.git) developed as
[part of the Open Road project](https://github.com/The-OpenROAD-Project).

The plugin approach and Makefiles were copied from the SymbiFlow [plugin repo](https://github.com/SymbiFlow/yosys-symbiflow-plugins)
which is [part of the SymbiFlow project](https://symbiflow.github.io).

**NOTE** The plugin build depends upon having already downloaded and installed Yosys.
Also, the file yosys/kernel/cost.h needs to be manually copied to the 
/usr/local/share/yosys/include/kernel directory since it is needed but not copied by
the yosys install script.

## Summary

### orlo plugin

Adds two passes "orlo" and "orlo_reint".  See the documentation under "help orlo" in yosys

