#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.

// TEMP: change pipeline library
library identifier: 'dcaf-scripts', retriever: modernSCM(github(checkoutCredentialsId: 'SAME', id: 'ba0fa9a5-aaf7-4c95-9bbe-b088a0d9b35f', includes: 'fix-master-builds', repoOwner: 'LabVIEW-DCAF', repository: 'buildsystem', scanCredentialsId: 'DCAF-Build'))

//Modify the below parameters to match the values for this particular repo

def utfPaths = []
def vipbPaths = ["Distributed Control and Automation Framework (DCAF) Core.vipb"]
def lvVersion = "14.0"

//Leave the below line alone.  It pulls in the pipeline definition from the DCAF buildsystem repo so we don't duplicate code in every repo 
dcafPipeline(utfPaths,vipbPaths,lvVersion)
