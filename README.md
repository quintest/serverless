# Serverless
Based on this repository you can follow along with the Severless demo, created for use within my presentation or workshop context. Feel free to incorporate, re-use it in part or complete in your own workshop or tutorial.

## What you need
A working account with the serverless cloud service providers mentioned in the tutorials or a working setup for a local deployment.

Current cloud providers:
- [x] GCP by Google, demo will make use of GraphicsMagic (prev. ImageMagic) gm npm capabilities in execution environment of Google Cloud Functions, the function will be a svg-to-png converter which first recognizes the scale of the original svg en than converts that to a png image, keeping scale intact but enlarging to at least 400px width or the original width when larger. The function can then be incorporated into web and/or mobile apps..
- [ ] Azure by Microsoft

Work in progress
- [ ] AWS by Amazon,
- [ ] IBM Cloud

Local providers 
- [ ] OpenFaas, 
- [ ] Kubeless, 
- [ ] Knative

