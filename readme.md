# Video Widget

Magento 2 Video Widget making it possible to add responsive sized video clips in text editors. 

# Installation

Copy extension to /app/code

or

composer require idec/magento2-widget-video

Then run:

```bash
php bin/magento module:status
php bin/magento module:enable IDEC_VideoWidget
php bin/magento setup:upgrade
```

## Usage

In any content text editor, there will now be a new widget called _IDEC Video Widget_. Fields to fill in are:

 * Title - optional `h2` title that flies right above the video clip
 * Source - Youtube or Vimeo
 * ID - The ID of the movie clip. This is the same ID that can be found in the video URL at each video page
