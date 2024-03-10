
# YouTube Made For Kid Checker

This project aim to help digital marketing professional to improve their Google Ads placements on YouTube campaign. 
It's always frustrating to see part of campaign budget going to videos with kid content. 
Unfortunately exclusion list available online are not the most reliable and up to date.

This graphic user interface will help you to build along your campaign custom YouTube channel exclusion list.


## Installation

**Install YouTube MadeForKid Checker with command line.**

This project requires python 3.10 you can download it [here](https://www.python.org/downloads/release/python-3100/).

```bash
git clone https://github.com/seexmax/YouTube-MadeForKid-Checker.git
```
Open the project directory with `cd` and install the requirements.
```bash
pip install -r requirements.txt
```
In the project directory run `main.py` file to execute the application
```bash
python3 main.py
```

**Install YouTube MadeForKid Checker with executable file.**

## Demo
**The application is made of two tabs.**  
* The first tab is where you will upload the Excel file with the YouTube channels you want to check.
Please note that you need to use the template available 
[here](/Users/v.mereau/workspace/YouTube-MadeForKid-Checker/template_excel_file.xlsx) 
for formatting purposes. Only `.xlsx` format can be uploaded on the application.

<img height="50%" src="/Users/v.mereau/workspace/YouTube-MadeForKid-Checker/image/Screenshot_1.jpg" width="50%"/>

* On the second tab you need to enter your YouTube API token. If you don't know to get one you can click on `How to get a token ?`.
Instructions to get a token will be shown. Note that a token is limited to 10.000 requests per day. If you would like
to process more than 10.000 channels you will need to use multiple API token or wait the next day.

<img height="50%" src="/Users/v.mereau/workspace/YouTube-MadeForKid-Checker/image/Screenshot_2.jpg" width="50%"/>

Once you enter a valid token and upload an Excel file matching the template, the application will show you
how many channels are in your file. Note that the button `Process channels` is now clickable to start the process.

<img height="50%" src="/Users/v.mereau/workspace/YouTube-MadeForKid-Checker/image/Screenshot_3.jpg" width="50%"/>

As the application processes the channels, the time left will be displayed. At anytime during the process you can click 
on `Stop & Save`, it will interrupt the process and save the data collected in your file.

<img height="50%" src="/Users/v.mereau/workspace/YouTube-MadeForKid-Checker/image/Screenshot_4.jpg" width="50%"/>

When the application is done, or you used `Stop & Save`, the data collected will be saved in your file on a new tab named
`Results`.

<img height="50%" src="/Users/v.mereau/workspace/YouTube-MadeForKid-Checker/image/Screenshot_5.jpg" width="50%"/>

If you didn't process all the channels of your file because you reached the quota limitation of your token, or you used
`Stop & Save`, you can always upload again your file to process the remaining channels. The application will automatically
detect your `Results` tab and start from where you left.  
_You can see from the example of the demo that the channels to process went from 9.750 to 9.096 when I upload the file 
again._

<img height="50%" src="/Users/v.mereau/workspace/YouTube-MadeForKid-Checker/image/Screenshot_6.jpg" width="50%"/>


## License

[MIT](https://choosealicense.com/licenses/mit/)