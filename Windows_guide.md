
## 🚀&nbsp; Installation
1. Clone the repo
```
> git clone https://github.com/kashyappathak/ai
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'env', type the following commmand in command prompt
```
> py -m venv env
```

3. Activate the Virtual environment with
```
> .\env\Scripts\activate
```

4. Now, run the following command in your Command Prompt to install the libraries required
```
> pip3 install -r requirements.txt
```

<p align="center">
  <img src="Readme_images/win_cmd.png">
</p>
<p align="center">Example</p>

## Running the project

1. Open terminal. Go into the cloned project directory and type the following command:
```
> python train_mask_detector.py --dataset dataset
```

2. To detect face masks in an image type the following command: 
```
> python detect_mask_image.py --image images/pic1.jpeg
```

3. To detect face masks in real-time video streams type the following command:
```
> python detect_mask_video.py 
```
3. To detect face masks in an image on webapp type the following command:
```
> streamlit run app.py 
```
