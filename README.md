# tsp
Traveling Salesman Problem using Self Organizing Maps

To run the code, only Python 3 and the dependencies (matplotlib, numpy and pandas, which are included in the Anaconda distribution by default) are needed. In case you are not using Anaconda, you can install all the dependencies with:

pip install -r requirements.txt

To run the code, simply execute:

cd som-tsp
python src/main.py assets/<instance>.tsp

The images generated will be stored in the diagrams folder. Using a tool like convert, you can easily generate an animation like the one in this file by running:

convert -delay 10 -loop 0 *.png animation.gif
