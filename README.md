# r-ml-gpu-lite
Everything needed to test some machine learning concepts in RStudio

## create docker image

## run docker container 
docker run --rm    --gpus all   --network=host -v ~/dev:/home/rstudio/dev   --name nbt-lite  r-ml-gpu-lite

## use RStudio
The docker image exposes the ports 8787 and 54321
- open you browser on http://localhost:8787/ (depends also on your docker run parameters)
- use credentials:  user=rstudio, password=rstudio

have fun ;)
