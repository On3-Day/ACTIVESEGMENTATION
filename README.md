# Active Segmentation plugin for ImageJ

This project is sponsored by Google Inc. as a part of the Google Summer of Code 2023 program: 

1. **Organization:** [International Neuroinformatics Coordinating Facility(INCF)](http://incf.org)
2. **Mentor:** Dimiter Prodanov, [INCF Belgian Node](https://www.incf.org/network/nodes/belgium)
3. **Student Developer:** [Aaryan Gautam](https://github.com/aaryan-gautam)


## Project description
This project is about to provide the general purpose environment that allows biologists and other domain experts to use transparently state-of-the-art techniques in machine learning to improve their image segmentation results.
ImageJ is a public domain Java image processing program extensively used in life sciences. Active Segmentation plugin is the redesign of existing Trainable Weka Segmentation (TWS) of ImageJ. The Active Segmentation provides generic functionality and user friendly interface so that the user can include the state of the art filters and machine learning frameworks from the WEKA library:
  1.  Active learning.
  2.  Multi-instance learning designed by third party in a robust manner

The Generic framework can be used for segmentation and classification.

The plugin provides a general-purpose environment that allows biologists and other domain experts to use transparently state-of-the-art techniques in machine learning to achieve excellent image segmentation and classification. ImageJ is a public-domain Java image processing program extensively used in life and material sciences. The program was designed with an open architecture that provides extensibility via plugins computing different filters and region descriptors (i.e. image features). 

# Getting Started

To get started with this repository, follow these steps:

1. **Fork the Repository**

   Click the "Fork" button at the top right corner of this repository's page on GitHub. This will create a copy of the repository in your own GitHub account.

2. **Clone the Repository to Your Machine**

   After forking, you need to clone the repository to your local machine. Open your terminal or command prompt and use the following command, replacing `<your-username>` with your GitHub username and `<repository-name>` with the name of your repository:


This will download the repository to your machine.

3. **Set Up JDK 8**

Make sure you have Java Development Kit (JDK) version 8 installed on your machine. You can download and install JDK 8 from the official Oracle website or any other trusted source.

4. **Add JAR Files**

The repository contains JAR files in the "jars" folder that your project depends on. To include these JAR files in your project, follow these steps:

- Open your Integrated Development Environment (IDE).
- Locate the project settings or project properties.
- Find the section for configuring external libraries or dependencies.
- Add the JAR files from the "jars" folder to your project's classpath. The exact steps may vary depending on your IDE, so consult your IDE's documentation for specific instructions.

5. **Add ImageJ (IJ) JAR File**

You also need to include the ImageJ (IJ) JAR file in your project. Here's how:

- Download the ZIP file from [https://sumit3203.github.io./](https://sumit3203.github.io./).
- Extract the contents of the ZIP file to a location on your computer.
- Locate the ImageJ JAR file within the extracted folder.
- In your IDE, go to the project settings or properties.
- Add the ImageJ JAR file to your project's external libraries or dependencies, similar to the previous step with the "jars" folder.

  ![image](https://github.com/aaryan-gautam/ACTIVESEGMENTATION/assets/64756497/01d3dcaa-c600-4505-89a1-5079c9e1cd57)


Now your project should be set up with the necessary dependencies and configurations to work with ImageJ and the specified plugin directory.

6. **Testing the Setup**

To test that everything is working correctly, you can run a testing script called "TestSQLCells.java". Follow these steps to run the script:

A sample datasetPath can be found [here](https://github.com/aaryan-gautam/ACTIVESEGMENTATION/tree/master/small_data).

- Open "TestSQLCells.java" in your IDE.
- Modify the `static String datasetPath` to specify the dataset path.
- Modify the `private int sessionID` to set the desired session ID for training.
- Run the script. It will create and train a session with the specified `sessionID` on the specified `datasetPath`.


7. **Viewing Sessions**

You can view the created sessions by running "SessionGUI.java". This allows you to browse through the data and inspect the results of your training sessions.

Now your project should be set up with the necessary dependencies and configurations. You can use the provided testing script and GUI to work with your data and trained sessions.

Feel free to update this README with any additional project-specific instructions or information as needed.
