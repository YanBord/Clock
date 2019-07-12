from time import asctime, sleep

while True:
 print(asctime())
 sleep(1)
 print('\u001b[2A')
