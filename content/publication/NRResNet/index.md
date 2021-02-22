---
title: "Adaptive image denoising using a deep neural network with a noise correction map"
authors:
- admin
- Jaesung Lee
- Youngjin Yoon
- Tammy Lee
date: "2020-08-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proceedings of SPIE, 11510, Applications of Digital Image Processing XLIII*"
publication_short: "" 
abstract: Smartphone camera is becoming the primary choice for photography among general users due to its convenience and rapidly improving image quality. However, it is more prone to noise compared to a professional DSLR camera due to a smaller sensor. Image noise, especially in low-light situations, is a critical problem that must be addressed to obtain high quality photos. Image denoising has thus remained an important low level vision topic over years with both traditional and learning based techniques used for mitigating this problem. We propose an adaptive Deep Neural Network based Noise Reduction (DNN-NR) algorithm to address the denoising problem in smartphone images. Image noise was modeled from photos captured under different light settings using a Poisson-Gaussian noise model which better approximates the signaldependence (photon sensing) and stationary disturbances in the sensor data. Using this noise model, synthetic noisy datasets were prepared to mimic photos captured under varying light conditions and train the network. A noise correction map based on camera and image information like ISO, vignetting map and image gray level was provided as an input to the network. This correction map provides an indication of the local noise level to help the network adaptively denoise photos. Experimental results show that our adaptive neural network based denoising approach produced a significantly better denoised image with higher PSNR and MOS quality scores in comparison to a standard denoising method like CBM3D across varying light conditions. In addition, using a locally varying noise map helped in preserving more detail in denoised images.

summary: ""


links:
- name: Link
  url: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11510/2567586/Adaptive-image-denoising-using-a-deep-neural-network-with-a/10.1117/12.2567586.short
url_pdf: '' 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" 
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}



