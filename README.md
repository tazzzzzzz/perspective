# perspective
**perspective** - a simple application that can be used for performing perspective rectification and perspective rendering of images; using linear algebra techniques. 

## Getting Started
The application can be worked with at ***<a href = "https://tazzzzzzz.github.io/perspective/">perspective</a>***.

Users may upload an image using the **Upload Image** button.

After uploading the image, choose the four boundary points with respect to which perspective recitification must be done, and click on **Rectify** to perform said perspective rectification.

Once perspective rectification is completed, click on **Save** to save the image onto the machine. The image will be saved as _imagename-rectified.imageextension_ 

## Working with the source code
* To install all dependencies, run `npm install`.

* To start a development server that automatically recompiles the source code each time any changes are made to a file, run  `npm start`.

* To compile and build the directory that is to be served up, run `npm run build`.
  
* To publish the directory onto GitHub pages, run `npm run deploy`.

*  To remove the directory created after running `npm run build`, run `npm run clean`.


## Further Support
This project was developed as a requirement for Linear Algebra related coursework, and aims to only provide basic perspective rectification functions. Since these criteria have been met, I will no longer be updating this project.

However, this project still has a few issues, which have been mentioned, and any PR's in reference to these are always welcome, and will be reviewed.

## Previous Work and Due Credits
This project was initially cloned from <a href = "https://github.com/diogocampos">Diogo Campos's</a> work <a href = "https://github.com/diogocampos/rectify">Rectify</a>, and continues to be significantly based on the application developed by said individual as well. 
