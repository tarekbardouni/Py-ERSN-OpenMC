<html>
 <body>
</p>How to use the GUI to install openmc and prerequisistes under miniconda3</p>
</p>Prof. Tarek El Bardouni, University Abdelmalek Essaadi, Tetouan, Morocco
</p>
<p><b>A/  Install first gcc g++ and cmake if doesn't exist </b>

<b>B/ 	Before runing the GUI: install python3-pyqt5<b>
	
	sudo apt install python3-pyqt5

	or pyqt5-dev and pyqt5-dev-tools

<b>C/	run the application<b>
<b>run : python3 main.py<br>
	<br>1. install miniconda3 and update its packages<br>
	<br>2. close and reopen the terminal<br>
	<br>3. make sur the conda is activated<br>
	<br>4. as pyqt5 is not yet installed under conda lunch the GUI by runing :<br>
		<br>/usr/bin/python3 main.py <br>
	<br>5. install prerequisites<br>
	<br>6. install openmc<br>
	<br>7. download neutron data<br>

<b>D/	runing openmc under the GUI<b>
<b>Use the script bellow to lunch the gui to run openmc : <b>

<b>conda activate openmc-py3.7<b>
<b>export OPENMC_CROSS_SECTIONS=/home/tarek/Py-OpenMC-2020/data/endfb71_hdf5/cross_sections.xml<b>
<b># export OPENMC_CROSS_SECTIONS=/home/tarek/Py-OpenMC-2020/data/nndc_hdf5/cross_sections.xml<b>
<b>python3 gui.py<b>

<p><b>E/ License </b></>

<p>This software is free software; you can redistribute it and / or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version. For the complete text of the license see the GPL-web page.</p>
</article>
  </div>
</div>
  </body>
</html>
