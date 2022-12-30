


Do the following to created civ files from the excel files: 


---------------
Steps: 

1. In your terminal/command window, go to the folder with the python script and the excel files using cd/ls or similar. Then run these commeands: 

pip install -r requirements.txt
python3 format_changer.py

[If this does not work, first run: 
pip3 install openpyxl
and then run the above commands.] 

2. Check in the public folder, check if the civ files have been created/modified. To check if this works, you can delete the files first and then see if they were created after running the script. ---------------