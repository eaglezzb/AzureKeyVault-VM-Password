# AzureKeyVault-VM-Password
PowerShell and ARM Template to deploy an Windows VM on Azure with password stored in Azure Key Vault

==================================================================================================
= Demo Azure Key Vault - Stanislas Quastana - https://stanislas.io @squastana
==================================================================================================

English version 
purpose of this script is to create an Azure Key Vault and a secret inside this vault
this secret is a password that will be used during a Windows VM deployment with a ARM template
All you need is to to change name of Azure Subscription below and Azure PowerShell Module

version française
objectif de ce script et de ces fichiers json : 
1- créer un Azure key Vault et un secret dans ce Vault
2- définir dans ce vault un secret, ici un mot de passe 
3- déployer une VM Windows dont le mot de passe sera celui défini dans l'Azure Key Vault
   Cette VM est déployée à partir d'un modèle ARM ET d'un fichier de paramètres
Pré-requis : Vous avez besoin de l'ID de votre abonnement Azure et du module PowerShell Azure

====================================================================================================
