---
permalink: /previous-projects/
---

### A Scalable Multi-Chip-Module-based Deep Neural Network Accelerator Designed with a High-Productivity VLSI Methodology (Nvidia)
**People: Brucek Khailany, Rangharajan Venkatesan†, Yakun Sophia Shao, Brian Zimmer, Jason Clemons, Matthew Fojtik, Nan Jiang, Ben Keller, Alicia Klinefelter, Nathaniel Pinckney, Priyanka Raina, Stephen G. Tell, Yanqing Zhang, William J. Dally, Joel S. Emer, C. Thomas Gray, Stephen W. Keckler**

In this work, a scalable deep neural network (DNN) inference accelerator consisting of 36 small chips connected in a mesh network on a multi-chip-module (MCM) was designed. The accelerator enables flexible scaling for efficient inference on a wide range of DNNs, from mobile to data center domains. The chip was implemented using a novel high-productivity VLSI methodology, fully designed in C++ using High-Level Synthesis (HLS) tools and leveraged an agile VLSI design flow. The 6 mm2 chip was implemented in 16nm technology and achieves 1.29 TOPS/mm2, 0.11 pJ/op energy effi- ciency, 4 TOPS peak performance on 1 chip, and 128 peak TOPS and 2,615 images/s ResNet-50 inference in a 36-chip MCM.

#### Publications
* R. Venkatesan, S. Shao, M. Wang, J. Clemons, S. Dai, M. Fojtik, B. Keller, A. Klinefelter, N. Pinckney, P. Raina, Y. Zhang, B. Zimmer, B. Dally, J. Emer, S. Keckler, B. Khailany, "MAGNet: A Modular Accelerator Generator for Neural Networks", IEEE/ACM International Conference On Computer Aided Design (ICCAD), Nov 2019. 
* S. Shao, J. Clemons, R. Venkatesan, B. Zimmer, M. Fojtik, N. Jiang, B. Keller, A. Klinefelter, N. Pinckney, P. Raina, S. Tell, Y. Zhang, B. Dally, J. Emer, C. T. Gray, B. Khailany, S. Keckler, "Simba: Scaling Deep-Learning Inference with Multi-Chip-Module-Based Architecture", IEEE/ACM International Symposium on Microarchitecture (MICRO), Oct 2019. 
* B. Khailany, R. Venkatesan, Y. S. Shao, B. Zimmer, J. Clemons, M. Fojtik, N. Jiang, B. Keller, A. Klinefelter, N. Pinckney, P. Raina, S. G. Tell, Y. Zhang, W. J. Dally, J. S. Emer, C. T. Gray, S. W. Keckler, "A 0.11 pJ/Op, 0.32-128 TOPS, Scalable Multi-Chip-Module-based Deep Neural Network Accelerator Designed with a High-Productivity VLSI Methodology", HotChips 2019.
* B. Zimmer, R. Venkatesan, Y. S. Shao, J. Clemons, M. Fojtik, N. Jiang, B. Keller, A. Klinefelter, N. Pinckney, P. Raina, S. G. Tell, Y. Zhang, W. J. Dally, J. S. Emer, C. T. Gray, S. W. Keckler, B. Khailany, "A 0.11 pJ/Op, 0.32-128 TOPS, Scalable Multi-Chip-Module-based Deep Neural Network Accelerator with Ground-Reference Signaling in 16nm", VLSI 2019.

### Tensorloop: A Systematic Approach to DNN Accelerator Evaluation (Nvidia)

**People: Angshuman Parashar, Priyanka Raina, Sophia Shao, Rangharajan Venkatesan, Yu-Hsin Chen, Brucek Khailany, Stephen W. Keckler, Joel Emer**

Tensorloop is an infrastructure for evaluating and exploring the architecture design space of deep neural network (DNN) accelerators. Timeloop uses a concise and unified representation of the key architecture and implementation attributes of  DNN accelerators to describe a broad space of hardware topologies. It can then emulate those topologies to generate an   accurate projection of performance and energy efficiency for a DNN workload through a mapper that finds the best way to  schedule operations and stage data on the specified architecture. This enables fair comparisons across different architectures and makes DNN accelerator design more systematic. 

#### Publications
* A. Parashar, P. Raina, S. Shao, A. Mukkara, V. A. Ying, R. Venkatesan, Y. H. Chen, B. Khailany, S. Keckler, J. Emer, "Tensorloop: A Systematic Approach to DNN Accelerator Evaluation", ISPASS 2019.

#### Code
* [https://github.com/NVlabs/timeloop](https://github.com/NVlabs/timeloop)

* * * 

### Motion Magnification Accelerator (MIT)

**People: Priyanka Raina, Bill Freeman, Fredo Durand, Anantha Chandrakasan**

![Motion Magnification](img/motion.png)

* * * 

### An Energy-Scalable Accelerator for Blind Image Deblurring (MIT)

**People: Priyanka Raina, Mehul Tikekar, Bill Freeman, Fredo Durand, Anantha Chandrakasan**

![Deblurring](img/deblurring.png)

Camera shake is the leading cause of blur in cell-phone camera images. Removing blur requires deconvolving the blurred image with a kernel which is typically unknown and needs to be estimated from the blurred image. This kernel estimation is computationally intensive and takes several minutes on a CPU which makes it unsuitable for mobile devices.

This work presents the first hardware accelerator for kernel estimation for image deblurring applications. Our approach, using a multi-resolution IRLS deconvolution engine with DFT-based matrix multiplication, a high-throughput image correlator and a high-speed selective update based gradient projection solver, achieves a 78x reduction in kernel estimation runtime, and a 56x reduction in total deblurring time for a 1920 x 1080 image enabling quick feedback to the user. Configurability in kernel size and number of iterations gives up to 10x energy scalability, allowing the system to trade-off runtime with image quality. The test chip, fabricated in 40nm CMOS, consumes 105mJ for kernel estimation running at 83MHz and 0.9V, making it suitable for integration into mobile devices.

#### Publications and Talks
* P. Raina, M. Tikekar, and A. P. Chandrakasan, "An energy-scalable accelerator for blind image deblurring," IEEE Journal of Solid-State Circuits (JSSC), July 2017. (Invited) [Paper](https://ieeexplore.ieee.org/document/7891902)
* P. Raina, M. Tikekar, and A. P. Chandrakasan, "An energy-scalable accelerator for blind image deblurring," IEEE European Solid-State Circuits Conference (ESSCIRC), September 2016. [Paper](https://ieeexplore.ieee.org/document/7598255) **Best Young Scientist Paper Award**
* P. Raina, M. Tikekar, A. P. Chandrakasan, "An Energy-Scalable Co-processor for Blind Image Deblurring," IEEE International Solid-State Circuits Conference (ISSCC) Student Research Preview (SRP) Poster Session, February 2016. **2016 ISSCC Student Research Preview Award**

* * *

### Reconfigurable Processor for Computational Photography (MIT)

**People: Rahul Rithe, Priyanka Raina, Nathan Ickes, S. V. Tenneti, Fredo Durand, Anantha Chandrakasan** 

![HDR](img/hdr.png)

Computational photography refers to a wide range of image capture and processing techniques that extend the capabilities of digital photography and allow users to take photographs that could not have been taken by a traditional camera. Since its inception less than a decade ago, the field today encompasses a wide range of techniques including high dynamic range (HDR) imaging, low light enhancement, panorama stitching, image deblurring and light field photography. These techniques have so far been software based, which leads to high energy consumption and typically no support for real-time processing.

This work focuses on a hardware accelerator for bilateral filtering which is commonly used in computational photography applications. Specifically, the 40 nm CMOS test chip performs HDR imaging, low light enhancement and glare reduction while operating from 98 MHz at 0.9 V to 25 MHz at 0.9 V. It processes 13 megapixels/s while consuming 17.8 mW at 98 MHz and 0.9 V, achieving significant energy reduction compared to previous CPU/GPU implementations, enabling real-time computational photography applications on mobile devices. Live demonstration at the ISSCC Demo Session. [Video](http://player.vimeo.com/video/70417371)

#### Publications and Talks
* R. Rithe, P. Raina, N. Ickes, S. V. Tenneti, A. P. Chandrakasan, "Reconfigurable Processor for Energy-Efficient Computational Photography," IEEE Journal of Solid-State Circuits (JSSC), vol. 48, no. 11, pp. 2908-2919, Nov. 2013. [Paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6623206)
* R. Rithe, P. Raina, N. Ickes, S. V. Tenneti, A. P. Chandrakasan, "Reconfigurable Processor for Energy-Scalable Computational Photography," IEEE International Solid-State Circuits Conference (ISSCC), 164-165, February 2013. [Paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6487683)

#### In the News
* Picture Perfect: Quick, efficient chip cleans up common flaws in amateur photographs. ([MIT News](http://web.mit.edu/newsoffice/2013/computational-photography-chip-0219.html))
* Image Processor Makes for Better Photos and Performance ([IEEE The Institute](http://theinstitute.ieee.org/technology-focus/technology-topic/image-processor-makes-for-better-photos-and-performance))
* MIT imaging chip creates natural-looking flash photos. ([Engadget](http://www.engadget.com/2013/02/21/mit-imaging-chip-blends-shots-with-and-without-flash/))
* MIT's new chip promises 'professional-looking' photos on your smartphone. ([DPReview](http://connect.dpreview.com/post/2110851336/mit-photo-chip-smartphone-photos))
* Improve your smartphone's photo quality with this chip. ([Mashable](http://mashable.com/2013/02/21/photo-chip/))

* * * 

### A 3D Vision Processor for a Navigation Device for the Visually Challenged (MIT)

**People: Dongsuk Jeon, Nathan Ickes, Priyanka Raina, H. C. Wang, Anantha Chandrakasan**

3D imaging devices, such as stereo and time-of-flight (ToF) cameras, measure distances to the observed points and generate a depth image where each pixel represents a distance to the corresponding location. The depth image can be converted into a 3D point cloud using simple linear operations. This spatial information provides detailed understanding of the environment and is currently employed in a wide range of applications such as human motion capture. However, its distinct characteristics from conventional color images necessitate different approaches to efficiently extract useful information.

This chip is a low-power vision processor for processing such 3D image data. The processor achieves high energy-efficiency through a parallelized reconfigurable architecture and hardware-oriented algorithmic optimizations. The processor will be used as a part of a navigation device for the visually impaired. This handheld or body-worn device is designed to detect safe areas and obstacles and provide feedback to a user. We employ a ToF camera as the main sensor in this system since it has a small form factor and requires relatively low computational complexity.

#### Publications and Talks
* D. Jeon, N. Ickes, P. Raina, H. C. Wang, A. P. Chandrakasan, "24.1 A 0.6V 8mW 3D vision processor for a navigation device for the visually impaired," IEEE International Solid-State Circuits Conference (ISSCC), Feb. 2016. [Paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=7418084)

#### In the News

* A virtual “guide dog” for navigation. ([MIT News](http://news.mit.edu/2016/virtual-guide-dog-wearable-device-0202#.VrHZj9k0f5g))
* MIT researchers have developed a ‘virtual guide dog’. ([boston.com](https://www.boston.com/news/local-news/2016/02/03/mit-researchers-have-developed-a-virtual-guide-dog))
* Wearable with 3D camera to guide visually impaired. ([Pune Mirror](http://www.punemirror.in/others/scitech/Wearable-with-3D-camera-to-guide-visually-impaired/articleshow/50855649.cms))

More details about Priyanka's PhD work are on [Priyanka's MIT webpage](http://web.mit.edu/~praina/www/index.html).