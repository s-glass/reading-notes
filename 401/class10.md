# 401 class 10 notes

My analogy for the Stacks and Queues reading is that stacks are like pringles chips and queues are like Oreos in a sleeve. 

**Stacks / Pringles:**

You can `push` Pringles into the can, or `pop` them out. The top Pringle in the can is always `top`. When you `peek` the top Pringle in a can, you can maybe check what kind of chip that specific chip is...sour cream & onion? Original? Pizza flavored Pringles? If you `peek` in the can but there's nothing there, an exception will be raised, and `IsEmpty` will return true. When there's chips in the can, it returns false.

Pringles cans are FILO (first in, last out) and LIFO (last in, first out).


**Queues / Oreos:**

You can add oreos to the sleeve by using `enqueue`, and remove them with `dequeue`. The first oreo is always the `front` cookie and the last is the `rear`. When you `peek`, you'll be able to see what's inside the `front` cookie - maybe it is double stuffed, or has mint or chocolate cream inside. If you try to peek when the sleeve is empty, an exception will be raised, and `IsEmpty` will return true. When there's Oreos in the sleeve, it returns false.

Oreo sleeves are FIFO (first in, first out), and LILO (last in, last out)