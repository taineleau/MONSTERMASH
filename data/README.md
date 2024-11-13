## iti-complex data v1.1

#### Overview

This dataset comprises 105 images and is accompanied by a `metadata.csv` file which stores essential metadata for each image, such as the title, shelfmark, and description.

#### Dataset Details

* **Number of Images:** 105
* **Metadata File:**`metadata.csv` contains metadata for the images, including title, shelfmark, description, etc.

#### Usage Notes

* The images indexed from 0 to 53 (54 images in total) were utilized in the IWCP paper to test various line extraction methods.
* **Image Removal Notice:** Image with `id=4` has been removed from the current release due to copyright issues.


#### Annotation format

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
