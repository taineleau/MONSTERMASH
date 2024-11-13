### iti-complex

The IWCP paper used 54 images for testing different line extraction methods.

The current release we removed 4.json becase of copyright issue. We labelled 100 image in total, and will release soon.

`metadata.csv` stores the metadata for the images, including title, shelfmark, description, etc.

The `images`foloder store all images and`teklia_json` stores the annotation with the following format:

```
{
    "img_size": [
        height,
        width
    ],
    "text_line": [
        {
            "confidence": 1.0,
            "polygon": [...]
        }
    ]
}

```
