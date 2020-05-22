#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This runtime is linear or O(n) because the size of the input will be directly related to the number of times it runs. This particular snippet will run "n" times.


b) This snippet will have a complexity of O(n log n). As the input size increases, the complexity will gradually grow as well. When "n" equals 2, the function will only run twice, but an input of 10 will cause it to run 40 times before exiting the loop.


c) This runtime is also linear/O(n). As the inputs increase the runtime will increase proportionally, in this case running twice for every input.

## Exercise II
In order to find floor "f", I believe it would be most efficient to start on the middle floor. If the egg breaks while falling from that floor, you would move to the floor that is halfway between the current floor and the ground level and try again. If it does not break, you would move up to the point halfway between the current floor and the top floor. You would then continue moving the midpoint based on whether or not the egg broke until you determined the minimum safe drop distance.
This solution is essentially a binary search tree and, as such, would have a runtime complexity of O(log n).

