

# EdgeDetector
## Most popular and well-known Edge detector on the module

### Install

```bash
pip install EdgeDetector
```



### Example

```python
from AllEdgesDetection import EdgeDetector

EdgeDec=EdgeDetector("image.png")

image_edged=EdgeDec.detect_edges_canny()
# Show the image
plt.imshow(image_edged)

plt.show()

````
# Input

![SInput](img/input.jpeg)

# Result in gray scale

![Output in gray scale](img/output.png)
