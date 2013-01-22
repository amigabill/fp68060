fp68060
=======

PCB to plug FPGA softcore CPU into 68060 microprocessor socket

Licensed under GNU LGPL 2.1, or at user's option any later version of this same license.

PCB project is on Upverter at this link:
http://upverter.com/amigabill/215b379ff943fc80/FP68060/

Verilog/VHDL code related to this project will be found in this GitHub repo,
as is PCB data from other tools such as Eagle or KiCad, etc.


The directory structure here is based on the 
OpenCores Coding Guidelines 2009. Though I feel an IP block should
stay as it is intarred/unzipped, some IPs come with both Verilog and VHDL
subdirectories inside them, and I feel that is where the language split
should happen, rather than feeling like I should split an IP into two
separate locations for each half of it...


While this project began as a discussion about a 68060 replacement,
it's easy to see adapting it to 68040, 68030, etc. sockets as well.
So each variant has its own subdirectory here, and there is also a common
area for things that will be used unchanged in each variant, such as
processor core, PCB libraries, etc.
