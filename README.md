# Litterman-Climate
Python code

from zipfile import Zipfile
file_name = EZClimate-master.zip
with Zipfile(EZClimate-master.zip, 'r') as zip:
  zip.printdir()
  
  print('Extracting all the files now...')
  zip.extractall()
  print('Done)
