# Sim See

The program is designed to read and show data from PSCAD's and CloudPss's simulation result files:

- Show charts of signals
- FFT Analysis
- Power Calculator

You can also export the charts as many types of files. Supported files include png, ps, eps, pdf, etc. Vector graphics are recommended for higher qualities.

#### How to use

- Run PSCADSee.jar
- Click the *File* menu, import *.inf* file and *.out* file (note the order).

#### Dependencies

- jcommon-1.0.23
- jfreechart-1.0.19
- jtransforms-3.1
- commons-maths3-3.6.1
- tablelayout
- FreeHEP VectorGraphics package

#### Note
- When a CloudPss data file is loaded, power calculator is unavailable. (In future versions we may solve this problem)