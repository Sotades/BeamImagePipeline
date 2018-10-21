# BeamImagePipeline
Image processing pipeline using Apache Beam
## Purpose
1. Evaluate suitability of using Apache Beam to perform image manipulation and processing in real time.
2. Stream in data direct from gigE camera.
3. Switch to batch processing for stored images in file format.
4. Check if this can be run in a Docker Docklet.
## References
[Apache Beam programming guide](https://beam.apache.org/documentation/programming-guide/ "Apache Beam Programming Guide")
## Notes
## Use Python version 2.7
That's what the Apache Beam documentation says.
### Install the Microsoft Visual C++ Compiler for Python 2.7
You need to ensure that this is installed on your system before installing Apache Beam for Python. It can be found [here](https://www.microsoft.com/en-us/download/confirmation.aspx?id=44266 "Microsoft Visual C++ Compiler for Python 2.7")
### Install Apache Beam SDK
This can be found from the Pycharm list of packages. Alternatively, use `pip install apache-beam`
