You have a SystemVerilog (SV) design created inside Intel Quartus, and you want to automatically generate a matching Tcl script or Verilog wrapper that correctly lists all the module ports (inputs, outputs, inouts) without having to manually rewrite them.

Right now, if you want to create a Tcl file that instantiates your top-level module or connects signals, you need to manually copy/paste the port list from the SystemVerilog file — which is slow, error-prone, and annoying when the design changes.


---FIRST ATTEMPT TO USE CURSOR