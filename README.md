# Iranian_National_ID_Card_Detection
Detecting the Iranian National ID card in an image
- Detecting the Iranian National ID card in an image has its own challenges:
1. It has white edges, and detecting the edges is hard on white backgrounds,
2. Using adaptive thresholds doesn't work well for various illumination conditions.
- Therefore, in this project, we gathered a dataset of NID cards and trained an object detection method with Python. Consequently, we could detect cards in images successfully.
