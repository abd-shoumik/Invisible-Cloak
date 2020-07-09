# Invisible-Cloak

## To run this code in your terminal:
* ***Open your terminal**
* ***Change directory to where you have downloaded this code***
* ***Install python3 if you have not, if installed already then it's ok!***
* **Run**  `  python3 -m venv venv  ` ***to create a virtual environment named venv.***
* **Run**   `  source venv/bin/activate  ` 
***to activate your environment!***

*  Run this to install the dependencies
```python
pip install -r requirements.txt
```
> First we need to choose the color to mask. The code works by masking a specific color.
```python
python range_det.py -f HSV --webcam
```
> when you run this, you will be presented with 3 camera views. Go to the one with the slider and the one which starts  with a white screen.

> Adjust the values of H, S & V till only the object you wish to make invisible becomes white and the rest is black. The precise you get this, the accurate your invisibility will be.

> Enter q to exit from all cameras

> After you do that. Run `Python3 invisible.py`

> Stay away from the webcam for a few seconds and come back holding the cloak and say 'Evanesco'😂. Congratulations! You will be like this:

