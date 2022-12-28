# PLODE
Precise Logic and Delay (PLODE) is a tool that converts a Structural Verilog to a Spice deck, executes Spice simulations using ngspice and performs analysis of the Spice results to extract output delays and logic values. It can handle hierarchical Verilog with nested module instantiations. It takes into consideration glitches at the outputs in computing the output logic values and delays.</br>

To download and run the program correctly:
1. Download ngspice from its website and do its installation.
2. Download QT Creator with QT5 and QTCharts support for ubuntu

    Install prerequisites
    sudo apt-get update && sudo apt-get upgrade
    sudo apt-get -y install build-essential openssl libssl-dev libssl1.0 libgl1-mesa-dev libqt5x11extras5
    
    Download the Qt installer
    https://www.qt.io/download-qt-installer

    Run the Qt installer
    cd directoryName/qt*.run
    chmod +x qt*.run
    ./qt*.run
    
    
    .....image....
    select QT5 & QTCharts

3. Once all downloaded, it can be opened on QT Creator by opening the .pro file with QT Creator.
4. After building, PLODE GUI is ready to go.

How to work for a single path extraction?
  choose a tab "single path".
  .....image....
  1- choose a full path for selected benchmark as a verilog code.
  2- write a path with using node names.
  the single path verilog file as named ".v" on a same directory.


