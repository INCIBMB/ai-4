# AI-4

# Value Iteration
```
python gridworld.py -a value -i 100 -k 10
python gridworld.py -a value -i 5
python gridworld.py -a value -i 100 -g BridgeGrid --discount 0.9 --noise 0.2
```

# Q-Learning
```
python gridworld.py -a q -k 5 -m
python gridworld.py -a q -k 100 
python crawler.py
```

# Bridge Grid
```
python gridworld.py -a q -k 50 -n 0 -g BridgeGrid -e 1
```

# Approximate Q-Learning
```
python pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid 
python pacman.py -p PacmanQAgent -n 10 -l smallGrid -a numTraining=10
python pacman.py -p ApproximateQAgent -x 2000 -n 2010 -l smallGrid 
python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumGrid 
python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic 
```
