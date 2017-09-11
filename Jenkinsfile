#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.

// TEMP: change pipeline library
@Library('dcaf-scripts@fix-master-build')

//Modify the below parameters to match the values for this particular repo

def utfPaths = []
def vipbPaths = ["Distributed Control and Automation Framework (DCAF) Core.vipb"]
def lvVersion = "14.0"

//Leave the below line alone.  It pulls in the pipeline definition from the DCAF buildsystem repo so we don't duplicate code in every repo 
dcafPipeline(utfPaths,vipbPaths,lvVersion)
