<p align="center">
  <strong><a href='http://graphics.stanford.edu/papers/neural_process/'>Neural Process Reconstruction from Sparse User Scribbles</a></strong><br>
  Mike Roberts, Won-Ki Jeong, Amelio Vazquez-Reina, Markus Unger<br>
  Horst Bischof, Jeff Lichtman, Hanspeter Pfister<br>
  <em>Medical Image Computing and Computer Assisted Intervention (MICCAI) 2011</em>
</p>

<a href='http://graphics.stanford.edu/papers/neural_process/'>![Alt text](/Documentation/Figures/overview-row.png)</a>

This repository contains a C#/C++/CUDA implementation of our paper <a href='http://graphics.stanford.edu/papers/neural_process/'>Neural Process Reconstruction from Sparse User Scribbles</a>. The source code and precompiled binaries available here are provided for non-commercial research purposes only.

### Requirements

* Windows XP/Vista/7/8
* Visual Studio 2010
* <a href='https://developer.nvidia.com/cuda-gpus'>CUDA-Enabled GPU</a> that also supports Direct3D 11
* <a href='https://developer.nvidia.com/cuda-downloads'>CUDA drivers</a>
* <a href='http://www.microsoft.com/en-us/download/details.aspx?id=8109'>DirectX End-User Runtimes (June 2010)</a>
* <a href='http://graphics.stanford.edu/papers/neural_process/github/NeuralProcessReconstructionFromSparseUserScribbles/Sdk.zip'>SDK zip file</a>

### Precompiled Binaries

Precompiled binaries are available <a href='http://graphics.stanford.edu/papers/neural_process/github/NeuralProcessReconstructionFromSparseUserScribbles/Bin.zip'>here</a>. If you intend to run the precompiled binaries and you don't have Visual Studio 2010 installed, you'll need the <a href='http://www.microsoft.com/en-us/download/details.aspx?id=5555'>Visual Studio 2010 Visual C++ Redistributable Package (x86)</a>.

### Build Instructions

* Unzip the SDK zip file into the code folder such that the Sdk folder is parallel to the Mojo.Wpf folder.
* Open Code\Mojo\Mojo.Wpf.sln in Visual Studio 2010.
* Set the Mojo.Wpf project to be the startup project.
* Set the Mojo.Wpf project's working directory to be the full path of the Code\Mojo\Bin folder.
* Set the platform to be x86.
* Select Build Solution from the Build menu.
* Now you can run and debug the application.

I have taken care to include all external compile-time dependencies in the SDK zip file, and always to reference them with relative paths. As a result, you should be able to follow the instructions above to build the solution with a single button click, regardless of your system configuration.

### Notes

* The video on the <a href='http://graphics.stanford.edu/papers/neural_process/'>project page</a> offers rough guidance on the intended usage of the application.
* Additional documentation is available <a href='http://graphics.stanford.edu/papers/neural_process/github/NeuralProcessReconstructionFromSparseUserScribbles/Documentation.zip'>here</a>.
