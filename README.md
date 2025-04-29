# Sparkfun_Edge
Probably the last guy on this planet working with Sparkfun Edge

# Overview
- SparkFun Edge is the most energy-efficient microcontroller that is capable of running ML model  
- The purpose of this repo is to create a model for Sparkfun Edge -> deploy it on the device  

# NAS
The provided NAS finds the best architecture within the given search space: RAM, Flash, and MACC values  
It uses multi-exit(confidence-based) and quantization(uint8) to improve efficiency and reduce memory occupancy.  

# How to Deploy on Sparkfun Edge
In order to deploy the model, you have to use the provided AmbiqSuiteSDK. The original SDK has outdated/deprecated files, so it's been modified to work properly.  

# LICENSE
Everything is copyrighted by Aiden Seo  
The license of this repo is MIT - make sure to indiciate the copyright  
