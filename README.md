# PLODE
Precise Logic and Delay (PLODE) is a tool that converts a Structural Verilog to a Spice deck, executes Spice simulations using ngspice and performs analysis of the Spice results to extract output delays and logic values. It can handle hierarchical Verilog with nested module instantiations. It takes into consideration glitches at the outputs in computing the output logic values and delays.</br>

To download and run the program correctly:
1. Download ngspice from its website and do its installation. ( I don't use ngspice & delay measurement part)
2. Download QT Creator with QT5 & QTCharts for ubuntu.

    2.1. Install prerequisites
    
    sudo apt-get update && sudo apt-get upgrade
    
    sudo apt-get -y install build-essential openssl libssl-dev libssl1.0 libgl1-mesa-dev libqt5x11extras5
    
    2.2. Download the Qt installer
    
    https://www.qt.io/download-qt-installer

    2.3. Run the Qt installer
    
    cd directoryName/qt*.run
    
    chmod +x qt*.run
    
    ./qt*.run
    
    
    
    ![Alt text](/ss_setup_qt.png)
    
    select QT5 & QTCharts

3. Once all downloaded, it can be opened on QT Creator by opening the .pro file with QT Creator.
4. After building, PLODE GUI is ready to go.

5. How to work for a single path extraction?

  5.1. choose a tab "single path".
  
  [Alt text](/ss_singlePath.png)
  
  5.2. choose a full path for selected benchmark as a verilog code.
  
  5.3. write a path with using node names.
  
  5.4. the single path verilog file as named ".v" on a same directory.
  


