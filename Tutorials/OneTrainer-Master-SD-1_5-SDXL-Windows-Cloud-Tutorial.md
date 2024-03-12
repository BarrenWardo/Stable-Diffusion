Download : https://www.cendio.com/thinlinc/download/

Help Documents : https://vm-docs.massedcompute.com/docs/category/product-overview

### How To Update OneTrainer To The Latest Version On MassedCompute Virtual Machine

* Open a terminal 
* Execute below to move into accurate folder
* ```cd apps/OneTrainer```
* Execute below to activate VENV of OneTrainer
* ```conda activate ot```
* Execute below to update OneTrainer to the latest version
* ```./update.sh```

### How To Update Automatic1111 SD Web UI On MassedCompute Virtual Machine

* Open a terminal 
* Execute below to move into accurate folder
* ```cd apps/stable-diffusion-webui```
* Execute below to activate VENV of OneTrainer
* ```git pull```

### How To Edit Automatic1111 SD Web UI Command Line Arguments On MassedCompute Virtual Machine

* Double click and start Stable Diffusion Settings on desktop
* Edit COMMANDLINE_ARGS having line as below and save
* ```export COMMANDLINE_ARGS="--xformers"```

### Download Links For Best Models For Training & Using
* Follow tutorial video to see how to download and move into accurate folder
* SDXL RealVisXL_V4 :  https://huggingface.co/SG161222/RealVisXL_V4.0/tree/main
* SD 1.5 Hyper Realism V3 : https://civitai.com/models/158959/hyper-realism