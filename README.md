# Facebook Messenger Data Grapher

## Dependencies

(be sure to install with pip3 to install for python3)

* Python 3 ****64 bit****
* Pandas
* Matplotlib
* BeautifulSoup4

## How To
1. Install all the dependencies
2. Download/clone this repository
3. On Facebook, go to Settings then select "Download a copy of your Facebook data"
4. Once you have that, find `messages.htm` inside the html folder and move that to the same folder as this repository
5. Edit `userinfo.py` and add your information
6. Run `python parser.py`
7. Run `python grapher.py`
8. Graphs will be generated and saved in the `graphs` folder

## Want to contribute? Here's some features to consider
* Additional parameters: who messaged first, average reply time.
* More permutations of existing parameters (sent/received, sex, date, number of messages, and number of people)
