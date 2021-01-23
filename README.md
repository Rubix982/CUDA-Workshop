# CUDA-Workshop

## Content

"CUDA For Engineers" is a workshop meant for people interested in looking into what the NVIDIA and GPU world have to offer for the growing trends of massively parallel and distributed computing platforms. It goes the basic introduction of what CUDA is and what the problems it is meant to solve, an exploration into the NVIDIA and CUDA Open Source ecosystem, and a demonstration of the CUDA work and how to get started with your first program. The talk is meant to take an approach for software engineers to get development up and running quickly.

The speaker is Saif Ul Islam, an undergrad from FAST NUCES, currently pursing and majoring in Computer Science, with a deep interest in Data Engineering, Data Science, and Software Development in general.

## Brief Description

CUDA is a run time environment for GPUs, offered by NVIDIA, and can be written in C/C++. CUDA is offered on a wide variey of platforms meant to serve mainly for computational and multi threading purposes.

It helps to provide an easy layer for developing, optimizing, deploying and as an abstraction layer between your application's business logic layer, on GPU-accelerated embedded systems, desktop workstations, enterprise data centers, cloud-based platforms and HPC supercomputers.

### Need To Know CUDA

GPU programming and CUDA are truly a game changing technology. You need to know about GPU-based parallel computing to keep up with developments in fields related to applied computation, engineering design and analysis, simulation, machine learning, vision and imaging systems, or any number of other computing-intensive fields. GPU-based parallel computing reduces the time for some computing tasks by orders of magnitude, so big computations (like training a machine learning system on a large data-set), that took weeks can now happen in hours, ad moderate-sized computations (like producing a 3D contour plot).

Some basic experience and exposure to C/C++ is good enough, and opens up a gateway for you to learn and understand the extensive and broad set of skills that GPU programming can bring to you. That is, if you know how to make,

1. Simple Functions
2. Variables
3. Loops
4. Connect header and source files
5. Compile, run, and debug your code.

You're ready to go!

### Why would you want to learn CUDA?

### Getting Started

On a hardware level, you need a decent and good enough computing system - just something with a GPU that has CUDA enabled. Not every GPU can provide a platform for CUDA. Specifically, the GPU should belong to NVIDIA, and should have a `compute capability` of greater than 2.0. You can check out the complete list of CUDA enabled Tesla, GeForce, and Titan products from [this](https://developer.nvidia.com/cuda-gpus) list.

However, if you are associated with a university or an organization that has these hardware facilities, just like there is at FAST NUCES in Karachi, you can use those resources as well, or ask your local network university / organization administrator for rights and privileges to connect to those hardware resources.

## So What Can You Do With CUDA?

## Is CUDA related to HPC or HTC? In what way? What kind of power does CUDA give me?

- CUDA is mostly related to HPC rather than HTC, as it is mostly used for scientific, research, and high performance needed systems that need to perform in batches a large, massive number of operations.  

- CUDA HPC Developer here are as follows, https://developer.nvidia.com/HPC

## Before moving onto CUDA, here are some resources given by NVIDIA for their platform for learning and educational purposes

## For more information, you can join the NVIDIA Developer Program

- Link is here, https://developer.nvidia.com/nvidia-developer-program

This includes,
- CUDA Toolkit Documentation
- CUDA Libraries Documentation
- Deep Learning Software Documentation
- NGC - A platform to accelerate AI, HPC and Visualization GPU workflows and thus, accelerating time to solution.
- Forums: Access Technical Content from Leading Industry Events, NVIDIA On-Demand is a searchable database of content from past NVIDIA GPU Technology Conferences (GTC) and other industry leading events. Explore the extensive catalog of sessions, podcasts, and demos. Learn at your own time, at your own pace, anywhere.

## Okay, so what do you need to run CUDA?

Technically, it's just a file that uses a specific compiler. IT can run on a command line, or even to a fully fledged IDE such as NSight Visual Studio.

Most of these tools deal with the memory aspects of the programs, to give you an in depth of

## Resources  

### [Libraries](https://developer.nvidia.com/gpu-accelerated-libraries)

- Contains already implemented many of the libraries that are needed for high performance, optimized computing, including libraries for data science, deep learning, math related libraries, IoT devices, Image and Video Libraries. Some are open sourced, and some are propierity belonging to NVIDIA.

### [CUDA Downloads](https://developer.nvidia.com/cuda-downloads)

Contains links for,

- [CUDA Documentation / Release Notes](https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html)
- MacOS Tools,
  - NVIDIA® CUDA Toolkit 11.2 GA no longer supports development or running applications on macOS.
  - NVIDIA is making macOS host versions of these tools that you can launch profiling and debugging sessions on supported target platforms.
  - Complete list of debuggers available for MacOS and Cuda are listed [here](https://developer.nvidia.com/nvidia-cuda-toolkit-developer-tools-mac-hosts)
- Training
- Sample code
- Forums
- FAQ
- Open Source Packages
- Bug submission

### [NVIDIA Deep Learning Institute, DLI](https://www.nvidia.com/en-us/training/)

- [Self Paced, Online Courses](https://www.nvidia.com/en-us/training/online/)
- Only two courses on Deep Learning are free at the moment,
  -[Getting Started With DeepStream Analytics On Jetson Nano](https://courses.nvidia.com/courses/course-v1:DLI+C-IV-02+V1/about)
  - [Getting Started With AI On Jetson Nano](https://courses.nvidia.com/courses/course-v1:DLI+S-RX-02+V2/about)
- Many more are free and available for free on [Infrastructure]()
- Contains courses on Deep Learning, Accelerated Computing, Data Science, Infrastructure

## Installation For CUDA

### Software Level

- For Windows,
  - A decent and recent enough machine with any version of Windows, starting from 7 to onwards, is good enough for CUDA development.
  - Recommended that you create a restore point
    - From the Windows Start Menu, select Control Panel and type 'Create a restore point' in the search box. Click on the search result to open the System Protection tab in the System Properties window. To create a restore point, click on the Create... button near the bottom of the window
  - Install the Microsoft Visual Studio IDE from [here](https://visualstudio.microsoft.com/vs/). Recommend you install this first as the CUDA extensions that come with Nsight work on top of the VS IDE.
  - The CUDA toolkit and resources are available at the [CUDA Developer Zone](https://developer.nvidia.com/CUDA-zone). It's a fully fledged experience with CUDA developer options and resources.
  - After signing up for the program, you can visit the CUDA Release Candidate page to get the package for your target machine. You can find the link for that [here](https://developer.nvidia.com/cuda-downloads)
