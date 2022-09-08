# Update Event Map Headers

## Setup and enviroment
Install anaconda and make sure the conda command is in your path

run the following code

```shell
# Create, activate and install the dependencies in a new conda enviroment
conda create -n update_event_map_headers python=3.9
conda activate update_event_map_headers
conda install -c conda-forge gemmi=0.4.5 fire

# Download the repository
git clone https://github.com/ConorFWild/update_event_map_headers.git

# Run the code to update the headers
python update_event_map_headers/update_event_map_headers.py path/to/pandda/dir
```


