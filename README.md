Setup
-------
1. Run these commands
```
cd deephacks
wget https://s3-us-west-1.amazonaws.com/deephacks2017/pretrainedweights.tar.gz
tar -xvf images.tar.gz
tar -xvf pretrainedweights.tar.gz
jupyter notebook
```
2. Update the PATHS in the notebooks to point to your deephacks directory

3. (Optional) Set up jupyter connection from server to laptop
```
$laptop: ssh -l bfortuner@DEEPLEARNINGIP
$server: jupyter notebook --no-browser --port=8888
$laptop: ssh -NL 8888:localhost:8888 bfortuner@DEEPLEARNINGIP
```
Now you can visit http://localhost:8888 in your laptop’s browser and start editing the notebooks on your deep learning machine!
