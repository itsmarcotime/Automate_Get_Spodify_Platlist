## Python Script to Get Spodify Platlist with OAuth
created by Marco Mata

## Table of Contents
1. [Description](#description)
2. [Built-with](#built-with)
3. [Contribution](#contribution)
4. [Usage](#usage)
5. [Questions](#questions)

## Description
The main purpose of writting this script was to help me get a better understanding of how OAuth works when making requests to the spotify api, and hope that this repo can help with your python scripts as well. In the script you will find a python flask set up that works with OAuth to make a request for a users spotify playlist by having the user login in with their own spotify account. Once the user logs in, there are requests made in the background for an access token to the spotify api. The big problem this script solves is that access tokens for the spotify api only last for one hour (at the time of writting this). However, the script takes advantage of response elements from the api such as 'expires_in' && 'refresh_token'. By using these responses the script will automatically request a new token and nothing has to be stressed over on the developers end of things. You can find more inforation here: https://developer.spotify.com/ 

## Built-with
This script was built using Python.

## Contribution
If you discover a bug or have an enhancement in mind, please don't hesitate to open an issue.

## Usage
Check back very soon...

## Questions
Questions? <br /> 
<a href="https://www.linkedin.com/in/marco-mata-8165bb175/">LinkedIn</a><br />
mmata3309@gmail.com