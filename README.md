# DIP-Workshop-4

## Basic Image Workouts:

### Code:

```
import cv2
import matplotlib.pyplot as plt
import matplotlib.image as mpimg
import cv2
import matplotlib.pyplot as plt
image = cv2.imread("Satellite.jpg")
fig, ax = plt.subplots()
ax.imshow(image)
ax.set_xticks(range(0, image.shape[1], 100))
ax.set_yticks(range(0, image.shape[0], 100))
plt.show()
image = cv2.imread("Satellite.jpg")
x, y = 500, 50
width = 200
height = 600
cv2.rectangle(image, (x, y), (x + width, y + height), (0, 0, 255), 5)
fig, ax = plt.subplots()
ax.imshow(image)
ax.set_xticks(range(0, image.shape[1], 100))
ax.set_yticks(range(0, image.shape[0], 100))
plt.show()
```
### Output:



