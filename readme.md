# CodeIgniter Helper: PDF thumbnail generator (with Google Drive)

**ci-google-drive-pdf-thumbnail**

## About this helper

This CodeIgniter's helper generates a PNG thumb from a PDF file using Google Drive thumbnail generator.  

Its usage is recommended for CodeIgniter 2 or greater.

## Usage

```php
$this->load->helper('gpdf_thumb');

$pdf_file_url = "http://github-media-downloads.s3.amazonaws.com/GitHub.Quick.Facts.pdf";
$file_path = "./pdf_thumb.png";
saveGPDFThumb($pdf_file_url, $file_path);

// you can also set two more optional parameters
// - width (300 by default)
// - page number (1st by default)
```

![Ale Mohamad](http://alemohamad.com/github/logo2012am.png)