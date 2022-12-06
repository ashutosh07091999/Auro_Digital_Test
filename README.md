# Auro Digital Test
Auro Digital Test conducted at IIT Delhi
Task Link: https://drive.google.com/drive/folders/1t1T7pU2MgQFIKMT9xGIcbJGbeeie-vix

Used heappq module to implement Priority Queue in Python.
Used threading to perform simultaneous execution.

Buy works as Delete From Heap using heap pop. $O(log N)$ time.

Sell works as Push in to Heap using heap push. $O(log N)$ time

Total Execution Time varies between 25 to 32 seconds depending on number of threads.

Further Ideas:
1. Using Multiprocessing module as Google Colab had 2 processors.
2. Using bitarray for maintaing delete (using more space rather to optimize time)
3. Using hashing ideas
