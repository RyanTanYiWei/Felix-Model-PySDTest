**Recommendations for Workflow Integration**

To effectively integrate this project into our workflow, I suggest pursuing the following steps:

1. **Evaluate Calibration Results**: Verify if the results from scipy.optimize are acceptable for calibration purposes.
2. **Develop Calibration Methods**: Identify the need for repeated calibration methods (e.g., parallel fitting, sampling methods) and create global functions to support these methods.
3. **Track Calibration Outputs**: Establish a workflow to keep track of calibrated outputs.

**Project Structure**

The project consists of the following folders and files:

**IPYNBs**
* **pysd-workflow_SimpleExample**: This notebook tests PySD's conversion of a sample file and its calibration capabilities. Last cell shows how you can callibrate with a single function.
* **pysd-workflow-FeliX**: This notebook debugging process of PySD's conversion of FeliX models. Runs with a flawed version of FeliX_v25
* **ema-workflow**: This notebook is used to test EMA's connectors with FeliX files.

**Vensim File Folders**
* **FeliXTests**: This folder contains FeliX GlobalV25 and its submodels.
* **PySDCookbookTest**: This is a test file for examples.




