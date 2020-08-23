# Matrix background
*Attention: Nothing for too weak processors*

### Matrix without boxes
![A matrix background with no static boxes configured](https://github.com/KneeNinetySeven/OBS-Stream-Assets/blob/master/_res/matrix_no_boxes.gif)

### Matrix with boxes
![A matrix background with static boxes configured](https://github.com/KneeNinetySeven/OBS-Stream-Assets/blob/master/_res/matrix_with_boxes.gif)

## Configuration
To configure the static box elements, please add these into the json object in the very beginning of the file.


```
const staticObjects = {
        boxes: [
            {
                anchor: {x: 4, y: 4},
                width: 40,
                height: 15
            },
            {
                anchor: {x: colCount - 47, y: 5},
                width: 43,
                height: 38
            }
        ]
    }
```

Further, you can change the text main color by updating the variable ```mainColorRGB```. It **MUST** be noted as RGB values, separated by a comma. No decimals or anything at the end. 







```Choice is an illusion created between those with power and those without.```
Have fun streaming. Cheers - The author.
