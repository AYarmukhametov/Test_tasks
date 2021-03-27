# Нахождение кончиков пальцев на изображении
# Find fingertips in the picture


Решение работает и для цветных фотографий ладони, но в этом случае необходимо вручную подбирать границы фильтров для создания черно-белого изображения. Также необходимо определить какой фильтр использовать:
- THRESH_BINARY, если рука светлее фона
- THRESH_BINARY_INV, если рука темнее фона 


Solution works for color pictures either, but in this case you need to manually set the thresholds of filters to create black and white photo. You need also to decide which filter you are going to use:
- THRESH_BINARY, if the hand is lighter than background
- THRESH_BINARY_INV, if the hand is darker than background