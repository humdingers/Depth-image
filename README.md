# A dataset of Snow-road

The images in this dataset are of actual road scenes captured while unmanned vehicle driving.

If this dataset is provided for research purposes, please see License section below.


## Files
Currently the dataset contains 6000 infrared images, visible light images and ground-truth depth maps.

```
-----------------------------------------------------
infrared images         | 6000 | 7.40M tokens
visible light images    | 6000 |  396K tokens
ground-truth depth maps | 6000 | 1.11M tokens
-----------------------------------------------------
```

## Format
The infrared images, visible light images and depth maps are croped to the resolution of 256×512.
we classify the depth map into 32 levels in the logarithmic space as training labels.

### infrared images

![/depth_images/Maxing out a 200mbit pipe](max-out-200mbit.png)

### visible light images

### wocka.json
Scraped from [wocka.com](http://wocka.com/).

Additional fields:

* `id` -- page ID on wocka.com.
* `category` -- see available categories [here](http://www.wocka.com/).
* `title` -- title of the joke.

```json
{
        "title": "Infants vs Adults",
        "body": "Do infants enjoy infancy as much as adults enjoy adultery?",
        "category": "One Liners",
        "id": 17
    }
```


## License
I provide this dataset for research purposes and make no ownership claim on any part of it. The question of copyright in the case of jokes is unclear and I recommend not using the dataset commercially.

For removal of copyrighted content, please contact me on GitHub.

## Citing
If you use this dataset in academic work, please cite as follows:

```bibtex
@misc{pungas,
        title={A dataset of English plaintext jokes.},
        url={https://github.com/taivop/joke-dataset},
        author={Pungas, Taivo},
        year={2017},
        publisher = {GitHub},
        journal = {GitHub repository}
}
```
