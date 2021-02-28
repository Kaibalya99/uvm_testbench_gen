# uvm_testbench_gen

# Intro
uvm_testbench_gen is a Novel GUI Based UVM testbench template builder used to generate single UVM component/object or complete UVM testbench loaded with features to configure as per the user requirements 

# Pre-Requisits
The current stable version of uvm_testbench_gen requires:
1. Python 3.*
2. openpyxl-2.5.4 or higher version.  

  Note: For further details on installation process please refer Documentation section 2 given below

# Usage / Commands To Run The Tool
1. The command to launch the tool in normal mode.<br/>`python uvm_testbench_gen.py`
2. The command to launch the tool in debug mode for dumping the debug information.<br/>`python uvm_testbench_gen.py debug`

   Note: The tool will dump out all the debug information in the following dbg_uvm_testbench_gen.log file
  
# Facts 
1. Tool GUI works well in Linux environment and its been tested in Windows as well.
2. It doesn't work well in MAC (Catalina OS) since there is some issue with respect to Tkinter libs.
3. The "comments" format used in the generated codes follows the "Natural Docs" formatting for class, functions, tasks. For further details on the Natural Docs and formatting used in the UVM base libraries please refer the section 5 in Documentation given below.

# Documentation, papers, links and other required details

1. Complete documentation about the tool operation.<br/>- [UVM Testbench Generator Docs](https://github.com/hellovimo/uvm_testbench_gen/wiki/The-Novel-GUI-Based-UVM-Template-Generator)

2. Steps To install Python locally to work with the tool without root permission.<br/>- [Local Python Installation](https://hellovimo.github.io/uvm_testbench_gen/localpythoninstall.html)

3. Short video about this tool can be found on the below youtube link<br/>- [UVM Template Generator Tool Demo](https://www.youtube.com/watch?v=DNopc-QDq0o)

4. Poster/Paper submitted for DAC2020 (Design Automation Conference) Conference in the link below.<br/>- [UVM Template Generator Tool DAC2020 Poster/Paper](https://github.com/hellovimo/uvm_testbench_gen/blob/main/Documents/DAC2020_Novel_GUI_Based_UVM_Template_Builder_Vignesh_Manoharan.pdf)

5. For UVM comments formatting, natural docs etc. please refer the links given below.<br/>- [Natural Docs](https://naturaldocs.org/)<br/>- [UVM Natural Docs Formatting Updates](https://sourceforge.net/p/uvm/code/ci/master/tree/)
