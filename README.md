<p align="center">
  <a href="http://www.imaginecup.com" target="_blank">
    <img src="https://raw.githubusercontent.com/ImagineCupGame/SuperFamilyAzureML/master/assets/ImagineCupLogo.png" width="80%" alt="Imagine Cup"/>
  </a>
</p>

# Churn Prediction and Intervention
*[Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/) and [Azure App Service](https://azure.microsoft.com/en-us/services/app-service/)*

## Overview
Churn is a term employed when consumers stop using a good or service. It is seen across a number of industries, and in many cases, companies devote additional resources to stop a customer from leaving. With online computer games, for example, substantial data is available to analyze individual and collective player behavior to help predict when a particular gamer may leave. Game creators may even take their capabilities a step further and intervene in-game to incentivize players to continue gaming. Additional bonuses, power-ups, and numerous other tactics are common methods employed to keep such players involved.

The *Super Family* game is a basic web app about a family of super heroes. Heroes battle villains, but there is a twist—the game uses the results of a predictive model to account for potential churn, and it provides a new helmet to a player if a churn event is imminent. If churn is not likely, the game does not provide the bonus.

You will have the opportunity to alter your machine learning experiment to try to make your churn prediction as accurate as possible. In the real world, misclassification can be costly. Imagine if a company provided a free month of service or a hotel provided a free stay, when the customer was not actually considering alternative services. Money or other resources would have been employed for no reason. The goal in this case is to reduce such false positives—when a churn event is predicted, but in reality, the consumer is not likely to churn.  
<p align="center">
  <img src="https://raw.githubusercontent.com/ImagineCupGame/SuperFamilyAzureML/master/assets/MrStrength.png" alt="Mr Strength"/>
</p>


## Objectives
This exercise is split into six activities that will help you gain an understanding of churn analysis and how to intervene to try to prevent churn. You will learn the basic process used to train, score and evaluate a predictive churn model. The first four activities utilize *Azure Machine Learning* (Azure ML) to prepare a model to determine whether or not a player may churn. The final two activities use *Azure App Service* and involve deploying a simple ASP.NET *Super Family* game that invokes your Azure ML model. Based on the prediction returned by Azure ML, in-game behavior changes to incentivize a player to continue playing. Using different selection of features and changes to model parameters, how accurate can you become at predicting churn?

- Activity 1 - Prepare data for a churn experiment
- Activity 2 - Train and score a model using Support Vector Machines
- Activity 3 - Train and score a model using Boosted Decision Trees
- Activity 4 - Publish your churn experiment as a web service
- Activity 5 - Create your *Super Family* game
- Activity 6 - Publish and play the *Super Family* game


## Requirements/Prerequisites
1.	A Microsoft account is required to access an Azure Machine Learning workspace. If you do not already have a Microsoft account, you can obtain one for free by following the link below:  
https://www.microsoft.com/en-us/account/default.aspx
2.	An Azure subscription is required to use Azure App Services and the associated publishing features of Visual Studio. Students can create a limited Azure subscription for free by signing up for the DreamSpark program using the relevant link below. If you are not a student or are unable to provide proof of education, you can obtain a free trial for Azure using the main Azure link:  
https://www.dreamspark.com/  
https://azure.microsoft.com/
3.	Visual Studio 2015 is required for the Super Family ASP.NET web app project. The free Visual Studio Community version is available using the link below:  
https://www.visualstudio.com/en-us/downloads/download-visual-studio-vs.aspx
4.	The Azure SDK version 2.8.1 is required to publish your Super Family app to Azure App Service using Visual Studio. The Azure SDK can be installed using the Web Platform Installer.  
https://www.microsoft.com/web/downloads/platform.aspx

## Acknowledgements
This lab was adapted from original content created by Wee Hyong Tok, Ph.D., Senior Program Manager on the Azure Machine Learning team at Microsoft.
