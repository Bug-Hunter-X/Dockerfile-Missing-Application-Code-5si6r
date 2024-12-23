# Dockerfile Bug: Missing Application Code

This repository demonstrates a common error in Dockerfiles: forgetting to copy the application code into the image.  The provided `Dockerfile` correctly installs the necessary Python dependencies using `pip`, but it fails to copy the actual Python script (`main.py`) resulting in a runtime error when the container tries to execute the `CMD`. 

The solution demonstrates how to correctly copy the application code to the image.