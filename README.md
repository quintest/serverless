# Serverless
Based on this repository you can follow along with the Severless demo, created for use within my presentation or workshop context. Feel free to incorporate, re-use it in part or complete in your own workshop or tutorial.

This tutorial we'll create a function which converts SVG (Scalable Vector Graphic) images to a PNG (Portable Network Graphics) format. The application will be written in Javascript for a Node.js environment. The application will integrate with storage options of the Serverless platform. For a Serverless deployment there's still some testing to do to select a framework which works with multiple platforms. For local servless   

## What you need
A working account with the serverless cloud service providers mentioned in the tutorials or a working setup for a local deployment.

- account with Serverless Cloud provider or local Serverless platform,
- IDE or tekst editor (scenario's are made for Visual Studio Code and IntelliJ IDEA community edition),
- possibility to run Node.js whenrunning local testing



Current cloud providers:
- [x] GCP by Google, demo will make use of GraphicsMagic (prev. ImageMagic) gm npm capabilities in execution environment of Google Cloud Functions, the function will be a svg-to-png converter which first recognizes the scale of the original svg en than converts that to a png image, keeping scale intact but enlarging to at least 400px width or the original width when larger. The function can then be incorporated into web and/or mobile apps..
- [ ] Azure by Microsoft

Work in progress
- [ ] AWS by Amazon,
- [ ] IBM Cloud

Local providers 
- [ ] OpenFaas, 
- [ ] Kubeless (by Bitnami), 
- [ ] Knative

