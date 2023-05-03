I worked with pymc3 in this docker calling:

docker run -it --rm -v /home/amiklos/GitHub/resources/:/resources -v /home/amiklos/myGoogleDrive/projects/ECT:/ECT -p 8999:8888 amiklos/pymc3:1.1

once started:

- source activate stat-rethink2-pymc3

- jupyter notebook  --notebook-dir=/resources --ip='*' --port=8888     --no-browser --allow-root 
