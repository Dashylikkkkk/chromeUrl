## Installing  
pip install -r requirements.txt 

## Check packeges
### Windows
pip list | Findstr /L "package"
### Linux
pip list | grep "package"

## Running the tests
-k kill chrome proccess ( deeper analysis ) -d deeper analysis
### Windows
python main.py -k -d
### Linux
./main.py -k -d
